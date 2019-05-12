# Principios básicos

### **Structure From Motion**

El algoritmo de SfM determina posición y orientación de la cámara en relación con el sujeto de imagen, para cada foto, que a través de un proceso iterativo cada vez se hacen más precisos. 

A partir de las coincidencias entre píxeles vecnios identificados en varias fotos se crean una serie de puntos dispersos. Es a partir de la intersección de los puntos encontrados, cuando la proyección de cada uno se proyecta en forma de nube dispersa 3D. La incertidumbre posicional de estos puntos se reduce a medida que aumentan las precisiones de las posiciones de los puntos.

los conjuntos de captura fotográfica se pueden adquirir usando combinaciones de cámara / lente no calibradas.

os algoritmos SfM necesitan un conjunto de correspondencias de puntos coincidentes. Estos puntos coincidentes se encuentran en las fotografías superpuestas de una red de imágenes planificada, capturadas desde diferentes posiciones y orientaciones en relación con el sujeto de la imagen. La forma en que se mueve la cámara en relación con el sujeto tiene un gran impacto en el grado de precisión \( incertidumbre posicional \) presente en las mediciones de la representación 3D asociada.

Sin la inclusión de objetos de longitud conocida en el proyecto, la fotogrametría genera representaciones 3D sin escala.



La fotogrametría es una tecnología fundamentalmente democrática: puede realizarla cualquier persona con una cámara de teléfono y acceso a un software gratuito de fotogrametría. Sin embargo, para producir el tipo de modelos 3D de alta resolución que capturan con precisión la geometría y el detalle de la superficie de un objeto, se requiere un alto nivel de habilidad tanto para la grabación de datos como para el procesamiento de datos. En general, cuanto mejor sea el sensor de la cámara y la capacidad de resolución de la lente, mejores serán los datos. La habilidad del operador, la calidad y el número de imágenes capturadas y la distancia del sensor de la cámara a la superficie del objeto también juegan un papel importante en la determinación de la resolución y el detalle de los datos 3D.

### Tipo de fotografías

* En función de su posición
  * Aérea o terrestre
  * Vertical, oblicua, horizontal
* En función del tipo de cámara
  * Métricas \(fotogramas\)
  * No métricas \(fotografías\)
* Tipo se sensor
  * Analógico o digital
  * Matricial, lineal o puntual

Lo más común es que para fotogrametría con un fin cartográfico se utilicen cámaras aéreas, verticales y métricas. Sin embargo, desde que los drones han entrado en el mercado, se está realizando mucha cartografía en base a sus cámaras, por lo que estamos delante de cámaras aéreas, verticales, no métricas, digitales y matriciales.

{% hint style="info" %}
Tener una cámara de matriz lineal o matricial nos puede aportar ventajas y desventajas. Para mi son mejor las matriciales para evitarnos el efecto _rolling shutter_ 
{% endhint %}

![](../.gitbook/assets/image%20%281%29.png)

