# Entrañas

El modo que tengo de entender los programas y herramientas que utilizo a diario, es conocer cómo trabajan, antes de lanzarme a intentar obtener un resultado que lo más probable es que no nos sirva para NADA.

### ¿En qué se basan los software fotogramétricos?

Siempre que vayamos a utilizar un software fotogramétrico \(Pix4D, Agisoft, CapturingReality, Meshroom, etc.\) vamos a utilizar **imágenes**. Éstas pasarán por un **primer procedimiento** en el cual se **extraen grupos distintivos de píxeles**. El método de detección de características más conocido es el algoritmo SIFT \(transformación de característica invariante de escala\). El objetivo inicial de SIFT es extraer parches discriminativos en una primera imagen que puedan compararse con parches discriminativos de una segunda imagen, independientemente de la rotación, la traducción y la escala.

{% hint style="info" %}
Ahora que conocemos el primer procedimiento, podemos llegar a una conclusión muy sencilla:

* Si tenemos imágenes con elementos que contengan texturas que ayuden a encontrar grupos distintivos de píxeles, falicitará al programa encontrarlos.
* Si por el contrario tenemos texturas sin contrastes, no se encontrarán, con lo cual no tendremos puntos
{% endhint %}

El **segundo paso** se trata de **encontrar las imágenes** que tengan la **misma área** en la escena. Dejando de lado el proceso que se realiza para encontrar las imágenes, llegamos a otra conclusión: si se facilita el proceso de búsqueda, ahorraremos tiempo de procesamiento y muy probablemente la cantidad de áreas en común entre las imágenes.

{% hint style="info" %}
Sea en la propia captura de datos o en postproceso, la secuencia de captura de las imágenes ha de ser consecutivamente lo mejor posible, es decir, que la secuencia con la que tomamos imágenes con solape entre ellas sea fiel a su consecución como fichero. Ejemplo: aa1.jpg, aa2.jpg ...
{% endhint %}

El tercer procedimiento puede que sea el más conocido cuando hablamos de fotogrametría, se trata del algoritmo **Structure From Motion** \(SfM \). 

El algoritmo de SfM determina posición y orientación de la cámara en relación con el sujeto de imagen para cada foto, que a través de un proceso iterativo cada vez se hacen más preciso \(suele elegir las 2 mejores imágenes para iniciar\). 

Los algoritmos SfM necesitan un conjunto de correspondencias de puntos coincidentes. Estos puntos coincidentes se encuentran en las fotografías que hemos tomado, utilizando su solape capturado desde diferentes posiciones y orientaciones en relación con el sujeto de la imagen. La forma en que se mueve la cámara en relación con el sujeto tiene un gran impacto en el grado de precisión \(incertidumbre posicional\) presente en las mediciones de la representación 3D asociada.

A partir de las coincidencias entre píxeles vecinos identificados en varias fotos se crean una serie de puntos dispersos. Es a partir de la intersección de los puntos encontrados, cuando la proyección de cada uno se proyecta en forma de nube dispersa 3D. La incertidumbre posicional de estos puntos se reduce a medida que aumentan las precisiones de las posiciones de los puntos.

El siguiente paso elige las mejores fotografías que ya tienen una posición en el espacio para recuperar el valor de profundidad de los píxeles y así crear volúmenes. Los siguientes pasos serían el mallado \(representación geométrica de la superfície de la escena\)  y la texturización \(mapeado UV\). 







