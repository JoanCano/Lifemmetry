# Cómo capturar fotos

## Configuración de cámara



* Comience su proyecto utilizando una lente gran angular. La primera selección de lentes de CHI generalmente tiene una distancia focal de 24 mm.
* Elija su distancia del sujeto y establezca el enfoque. Luego, ajuste la lente en "enfoque manual" y pegue el anillo de enfoque en su lugar.
* Utilice lentes de primera calidad en lugar de lentes de zoom. Si se debe usar una lente de zoom, use la extensión más cercana o más alejada del zoom.
* La apertura de la cámara debe permanecer constante durante la secuencia de captura. En una cámara de 35 mm, es una buena práctica no ajustar la abertura más pequeña que f / 11. Con aberturas más pequeñas \(más altas\) que f / 11, se producen efectos de difracción que desenfocan la imagen, reduciendo significativamente la resolución de la cámara.
* Use la configuración ISO más baja posible. Cuanto más alto sea el ajuste ISO, más ruido electrónico se genera en el sensor de la cámara. Este ruido hace más difícil la correspondencia de píxeles en diferentes fotografías.
* Desactive la estabilización de imagen y gire automáticamente las funciones de la cámara.
* En condiciones de luz variable \(por ejemplo, un día parcialmente nublado\), la cámara debe configurarse en modo manual o con prioridad de apertura \(use f/5.6 – f/11 para obtener las imágenes más nítidas\). La prioridad de apertura bloquea la apertura y nivela la exposición variando la velocidad de obturación. Es necesario mantener el punto de medición de la exposición en el sujeto de la imagen para obtener resultados consistentes. Ponga su cámara en el modo de medidores de punto central .
* Para obtener los resultados de mayor precisión, asegúrese de que la configuración de la cámara no cambie para una secuencia de fotos determinada.
* Si es necesario cambiar la configuración de la cámara o la lente, incluido el enfoque, agrupe las fotos subsiguientes en un conjunto diferente de las fotos anteriores. Calibre los conjuntos de fotos por separado, cada uno en su propio grupo de calibración.

#### Cómo tomar las fotografías

![](../.gitbook/assets/image%20%282%29.png)

Es importante mantener una distancia suficientemente constante del sujeto para mantener el enfoque nítido. Use una aplicación de calculadora de profundidad de campo en un teléfono celular para comprender cuánta libertad de movimiento en profundidad desde el sujeto está disponible para la configuración de su cámara y lente.

![](../.gitbook/assets/image%20%283%29.png)

Para sujetos redondos, capture fotos cada 10 a 15 grados y superponga las fotos de inicio y final para completar el circuito. Repita el procedimiento anterior para capturar tres filas de fotografías colocadas correctamente. Para proyectos de giradiscos, el fondo del sujeto debe estar enmascarado para permitir que solo aquellos píxeles que caen sobre el sujeto en el subsiguiente proceso de procesamiento de SfM. Si no enmascara el fondo puede dañar su proyecto.

los conjuntos de captura fotográfica se pueden adquirir usando combinaciones de cámara / lente no calibradas.

Debe colocar la cámara digital en un trípode o soporte de cámara para lograr estabilidad y eliminar la vibración durante la captura de imágenes. Las bolsas de arena u otros pesos pueden ayudarlo a estabilizar aún más los trípodes

El método recomendado es conectar la cámara a la computadora y usar la computadora para Contrólalo para probar tu configuración, y al disparar las imágenes. De esta manera, puedes disparar la cámara.

usar un dispositivo de activación remota para la cámara,Utilice un fondo neutro; Fondos de colores pueden reflejar su color sobre el tema. Trate de usar un blanco, Fondo negro o gris neutro \(según corresponda para el contraste con el objeto de destino\). Si el tema es adecuado para colocarlo en una superficie plana, puede colocarlo sobre una tela o superficie de color neutro. Del mismo modo, si está en posición vertical, intente crear un fondo neutro si es posible, colgando en una pared de color neutro o en un lugar encima de una sábana o tabla detrás de ella.

Una tarjeta gris neutra \(18% gris\) o una tarjeta de referencia fotográfica que incluye una escala de grises neutros con valores conocidos, es esencial para un balance de color adecuado, y también se puede utilizar como una referencia valiosa para determinar la exposición adecuada.

Para obtener un rendimiento óptimo de su lente, evite usar aberturas más pequeñas que f / 11 \(dependiendo de su lente\). Las aperturas más pequeñas \(números f / más altos\) pueden provocar la degradación de la imagen; la profundidad total de El campo aumenta, pero pierdes nitidez. Puede investigar la “difracción de la lente” para obtener más detalles de por qué Es tan. Un buen rango de apertura objetivo está entre f / 5.6 y f / 11, si es posible.

puede usar el histograma de la cámara para verificar las exposiciones de las imágenes más claras y más oscuras, y para asegurarse de que no salgan blancos, ni sombras demasiado oscuro.

Si es necesario, use un filtro de densidad neutra para bloquear la luz ambiental y volver a verificar sus exposiciones iluminadas con el filtro.

Para obtener la mejor calidad, le recomendamos que tome sus imágenes en formato RAW, aunque es posible toma imágenes JPEG y sigue produciendo un RTI. Una de las muchas razones para disparar en RAW es que usted tiene el control completo de todo el procesamiento aplicado a la Imagen, y, muy importante, un registro del procesamiento aplicado. Si disparas JPEG, la cámara aplica. Procesamiento a las imágenes según algoritmos propios. No puedes controlarlo, y no tienes un registro de lo que se hizo. Si decide tomar imágenes JPEG, elija la configuración de su cámara que reduzca la cantidad de Procesamiento en la cámara tanto como sea posible. Para obtener más información sobre este compromiso

### PASO 1. OBTENER LAS FOTOGRAFÍAS

Sin duda la parte mas importante del proceso es la correcta captura de las fotografías de nuestro objeto, con el objetivo de obtener resultados consistente y buena calidad

la **fotogrametría que consiste en usar cientos de fotografías de un mismo objeto tomadas desde diferentes ángulos para reconstruir la geometría de un modelo complejo usando software especializado**. Una de las ventajas de la fotogrametría respecto a otros métodos de escaneo es que podemos escanear la geometría y el color de nuestro objeto simultáneamente para crear un modelo  fotorealista listo para usar en nuestros proyectos.

Para garantizar un buen nivel de detalle en nuestros modelos usamos **cámaras de alta resolución** \(50MP+\) y **más de 200 fotografías por objeto** en condiciones de **iluminación controlada** para producir un solo modelo 3D con millones de polígonos y **albedo lineal correcto**. Pero dada la gran cantidad de polígonos iniciales, es necesario adaptarlos para su uso en proyectos reales, mediante retopología reducimos la carga poligonal de los modelos 3D y creamos texturas PBR de 4K y 2K.

El resultado es excelente, pero este método requiere equipo especial muy costoso \(cámara de alta resolución, luces de estudio, software, etc\) y hace falta mucho tiempo para producir un solo modelo terminado \(escaneo, creación de geometría, retopología, bakeo de texturas, materiales, etc\). 

El primer paso es reunir varias fotos del objeto desde varios ángulos. También es necesario reúna información adicional para referencia, métrica de escala y exposición correcta de las fotos.

**ISO:** Generalmente la más baja posible permitida por la cámara \(ISO 100 en nuestro caso\) para evitar el ruido, ya que el ruido puede confundir al software durante el proceso de escaneo.

**F-Number:** Generalmente intentaremos usar un diafragma lo más cerrado posible para aumentar la profundidad de campo y evitar así pérdida de nitidez por desenfoque. Valores entre f8 y f22.

**Velocidad de obturación:** Aunque estemos usando un buen trípode, recomiendo usar velocidades de disparo rápidas para maximizar la nitidez. Dependiendo de la óptica 1/125s por ejemplo.

**Iluminación y fondo:** Es importante usar fuentes de luz grandes situadas de forma frontal para eliminar sombras indeseadas en nuestro modelo. Si se trata de objetos brillantes esféricos \(como frutas\) es preferible usar un fondo negro y evitar luces laterales para neutralizar al máximo los especulares. Para objetos menos brillantes como rocas, etc podemos usar un chroma que nos facilitara la tarea de crear las máscaras posteriormente, pero a título personal, prefiero usar un fondo neutro para evitar contaminación y especulares. Otra alternativa sería usar polarización cruzada con un “ring Flash” o 2 luces situadas a 45º respecto a la cámara.

**Cantidad de fotos:** Normalmente es necesario un 75-80% de superposición de datos entre fotografías para obtener buenos resultados. Yo recomiendo un mínimo de 64 fotografías para cada rotación completa y suele ser necesario hacer 3 o 4 alturas diferentes. Por regla general son necesarias 150-200 fotografías como MÍNIMO por modelo para obtener buenos resultados.

**Encuadre:** Cada pixel de nuestra fotografía es información útil que el programa de fotogrametría puede usar para añadir detalle, de manera que trataremos siempre de llenar el encuadre con nuestro modelo para desperdiciar la mínima cantidad de pixels posibles. Si se trata de objetos muy pequeños, necesitaremos una lente macro para poder acercarnos más y poder enfocar.

**Exposición:** Para aprovechar al máximo la información contenida en el negativo digital hay que intentar “derechear”  el histograma \(exponer para las altas luces\) sin sobre-exponer partes importantes del modelo.

**Formato de archivo:** Este es un aspecto muy importante de la captura de fotografías para fotogrametría. Yo recomiendo usar el formato RAW de nuestra cámara para obtener imágenes de 14-16bpc que nos permitirán posteriormente obtener la información lineal para nuestro albedo. Si buscamos un albedo lo más correcto posible, necesitaremos crear una versión lineal de nuestro archivo RAW usando por ejemplo DCRAW. Si el resultado es demasiado “lavado” podemos hacer dos versiones de nuestras fotografías: Una versión lineal para proyectar las texturas de albedo al completar el proceso y una versión más contrastada para facilitar la tarea del software de fotogrametría.

A la hora de tomar las fotografías es muy importante ser extremadamente metódico, por ejemplo, podemos marcar nuestra peana giratoria para usar siempre la misma cantidad de grados en cada posición \(entre 5º y 10º\) y hacer las fotografías siempre en el mismo orden.



Antes de organizar un viaje de fotogrametría, se recomienda estar familiarizado con el proceso. Presentado en este tutorial y tener una buena práctica de cámara.

### Las 3 W: ¿Qué, dónde y cuándo?

El primer paso es conocer el tipo de entorno que se utilizará en el juego y comenzar a recopilar una lista de activos que deben ser producidos para un nivel de juego. Es necesario comprobar qué activos se encuentran. Compatible con el proceso de fotogrametría y cuáles realmente lo requieren. Comprender cómo funciona el software de reconstrucción le ayudará a comprender qué tipo de superficies Se adapta mejor a un proceso de fotogrametría. Para reconstruir la geometría a partir de un conjunto de imágenes, una reconstrucción. El software recupera la posición mundial en 3D de los distintos píxeles de las imágenes en función de la cámara. información, entonces, si hay un grupo espacial de píxeles con suficientes similitudes, se hace un punto. El resultado De este proceso se le llama "nube de puntos". Hay algunos tipos de superficie que son malos candidatos para la fotogrametría. Si el sujeto se esta moviendo \(por ejemplo, follaje en el viento\), o si es brillante o tiene reflejos fuertes \(como superficies metálicas, húmedas\). Superficies\), si es líquido, o si es transparente \(como superficies de vidrio\), entonces el software de reconstrucción no puede hacer coincidir los colores de píxeles en todas las fotos del objeto. Puede ser difícil o imposible ser bueno Bastante resultado con tales objetos. La imagen de abajo muestra algunos ejemplos de temas que no están adecuado para la fotogrametría:

Información para distinguir grupos de similitudes de píxeles ya que todos tienen el mismo color. Nota: Para objetos de colores planos, es posible ayudar al software de reconstrucción pintando en la Objetos o proyectando patrones de luz fijos. Sin embargo, en este caso, solo se extrae la geometría y Las texturas deben producirse por separado. El siguiente ejemplo muestra a la izquierda un activo de color plano Eso es demasiado difícil de reconstruir correctamente. El resultado es que se crean múltiples nubes de puntos separados lo que no se desea. A la derecha, al mismo objeto plano se le han aplicado patrones de pintura. lo que da una Buen resultado: solo se crea una nube de puntos:

La fotogrametría funciona muy bien con un activo estático, sólido y rugoso. Es importante tener en cuenta el costo de producción al crear un activo con fotogrametría. Incluso si un objeto cumple con los requisitos para un proceso de fotogrametría, no significa que sea la mejor manera de hacerlo. Algunos objetos simples o fabricados suelen ser más eficientes para crear con las técnicas tradicionales de modelado 3D. A continuación se muestra un ejemplo de una taza que es más rápida de modelar en software 3D, ya que tiene una forma simple de color plano, que el uso de fotogrametría.

Preste atención a los objetos complejos, especialmente con partes finas como pequeñas raíces. El tiempo de procesamiento de un activo complejo puede ser realmente costoso. A continuación se muestra un ejemplo de un activo que tardará mucho tiempo en procesarse:

3.1.2. ¿Dónde? 

Viajar a varios lugares para fotografiar objetos lleva tiempo, así como el despliegue de los diversos dispositivos de captura. Es necesario planificar cuidadosamente el viaje de tiro para minimizar la cantidad de viajes y evitar el tiempo perdido. Las buenas áreas son donde se puede capturar el número máximo de activos en la misma ubicación. Si está capturando geografía ambiental, Google Earth puede ser de gran ayuda para encontrar la ubicación correcta.

Nota: Hay propiedades privadas o protegidas en todas partes que deben ser respetadas. Muchas áreas son también Prohibido \(como zona militar\) y las grandes ciudades tienden a prohibir el vuelo de los drones. Tenga cuidado con las leyes locales y las reglas de la ubicación del viaje. Además, tenga en cuenta que cuando el sujeto está en un espacio público, puede ser Es difícil evitar que las personas se muevan frente a la cámara.

3.1.3. ¿Cuando? 

Cuando se dispara en ambientes al aire libre, el clima es el factor más importante a tener en cuenta. El clima tiene un gran impacto en el proceso de fotogrametría. La lluvia y la nieve son las peores situaciones. Las superficies se pueden mover \(el agua se desliza sobre ellas, la nieve cae\), la reflexión es más fuerte y la lente se modifica con gotas de agua o copos de nieve. Se recomienda cancelar el Disparo en estas condiciones. El viento es otro elemento difícil de tratar. El viento puede hacer que los árboles, el césped, el polvo y la arena se muevan de posición en sus imágenes, lo que puede resultar en un mal resultado de reconstrucción. Para objetos pequeños \(piezas de madera, ramas, piñas\), puede recolectarlos y traerlos de vuelta a un área interior para fotografiarlos en un lugar más seguro. Sin embargo, algunos objetos que son susceptibles de moverse en el viento solo pueden capturarse en el lugar, como árboles, arbustos y pasto. Para esto, deberá asegurarse de fotografiarlos en un día sin viento para que los objetos permanezcan completamente inmóviles. El sol produce reflejos y fuertes sombras direccionales. Una situación que debe evitarse ya que es difícil tener una buena exposición con un alto rango de exposición resultante. En un alto contraste. Foto, el ruido tiende a aparecer en sombras fuertes. Además, los reflejos o las sombras direccionales son difíciles de eliminar de la textura de albedo difusa generada, un paso que se requiere para poder volver a encender un objeto capturado. A continuación se muestra un ejemplo de una ubicación con una fuerte iluminación direccional que proviene del sol a través de las hojas. La textura generada desde esta ubicación exhibe mucha iluminación y una fuerte oclusión que son difíciles de eliminar.

Disparar en un día nublado sin lluvia proporciona una iluminación constante y sombras muy suaves que facilita la eliminación de la luz de la imagen más adelante. Sin embargo, la luminosidad es baja y la ISO debería ser levantado \(ver la sección de configuración de la cámara más adelante\).

Las condiciones preferidas para el Shoot son durante los días soleados, pero con el uso de un oclusor para aislar El sujeto de la iluminación direccional. Produce fotos más suaves similares a un cielo nublado, pero con un Mejor nivel de luminosidad para la captura.

Por último, tener una iluminación estable es importante tener imágenes consistentes para el software de reconstrucción. Las nubes rápidas que pasan frente al sol pueden convertirse en un problema. El segundo factor más importante es la temporada. Las diferencias de iluminación estacionales influyen en la apariencia. de objetos orgánicos / vivos como hojas, árboles o flores \(especialmente en otoño\). Además, la gama EV varía según la temporada y en días de invierno la gama EV disponible para la captura de los sujetos es más estrecho. Disponible la luz del día también varía con las estaciones.

### Ajuste de la cámara

Los mejores resultados durante la reconstrucción se obtienen a partir de imágenes nítidas sin sujeción del color. distancia. La nitidez es un factor muy importante aquí.

1- Ejemplo de mala exposición. Las áreas oscuras o fijas proporcionan una mala reconstrucción. 2- Ejemplo de una mala imagen con demasiado desenfoque, apertura de f / 2.8. El borde del cono de pino es. Totalmente borrosa debido a la profundidad de campo y la reconstrucción es un fracaso. 3- Ejemplo de enfoque y exposición correctos. La configuración predeterminada recomendada tiene como objetivo tener la imagen más nítida posible: se utiliza una apertura de f8 con el enfoque automático activado como resaltado por esta comparación de varias aperturas:

Si está filmando al aire libre, las condiciones de iluminación pueden variar debido al sol o las nubes que se mueven. Por lo tanto, a Ahorre tiempo, no se recomienda el uso de un trípode. ¡Tampoco pases un día para capturar una roca! El obturador la velocidad debe ser de 1/160 o menos para adaptarse a este rápido disparo manual mientras se mantiene una nitidez imagen.

ISO debe ajustarse a 100 o menos para evitar el ruido, especialmente en áreas más oscuras que no son buenas para el software de reconstrucción.

En la práctica, en el caso de condiciones de poca luz, primero debe aumentar el ISO, luego la apertura. Puede ser necesario ajustar un poco la apertura para contrarrestar el ruido producido por un ISO alto. Con un trípode, es posible jugar con la velocidad de obturación; sin embargo, usar un trípode puede agregar un tiempo excesivo entre los disparos como se describe anteriormente. Establezca el formato de salida en RAW. El formato RAW tiene mayor precisión para la reconstrucción y permite un mejor balance de blancos en las imágenes. Antes de comenzar la captura de activos, el nivel de exposición debe controlarse con el histograma de la cámara para no tener píxeles sujetos al sujeto y tener un buen rango de exposición. El siguiente ejemplo muestra a la izquierda una imagen donde el rango es demasiado pequeño para hacer una reconstrucción y muchos píxeles están sujetos. La imagen correcta representa un buen rango para procesar una reconstrucción. El sujeto está representado en medio del histograma: Es importante tener un nivel de exposición en el centro del rango de iluminación porque el software de reconstrucción recomendado \(Reality Capture\) no usa el rango completo de 14 bits capturado por la cámara y las fotos se convierten a 8 bits.



Proceso de captura Antes de viajar a su ubicación de captura de imágenes, mire la lista de verificación. Tenga cuidado de que las baterías estén cargadas, que los lentes estén limpios y que las tarjetas de memoria estén vacías. 4.1. Cómo capturar un objeto \(excepto los pequeños\) 4.1.1. Selección de activos Recuerde que la fotogrametría se adapta mejor a los objetos que requieren mucho tiempo para producirlos en el software de escultura en 3D. No uses la fotogrametría para formas simples como un cubo. No trates de capturar todo en la ubicación, piensa en términos de piezas utilizables. Seleccione un subconjunto que le permita reconstruir el entorno. Centrarse en la calidad en lugar de la cantidad de capturas. El siguiente ejemplo muestra la identificación de las piezas del entorno que proporcionarán un conjunto de herramientas de elementos que le permitirán construir un nivel de juego con varios recursos de instancia:

Nota: los objetos grandes que no se pueden capturar completamente desde todos los ángulos se deben capturar en la posición que se usarán en el juego. Las rotaciones mostrarán partes no reconstruidas. Hacer que dichos objetos sean reutilizables para cada ángulo de rotación requiere que los artistas vuelvan a escribir las partes faltantes del activo como en una tubería tradicional y no están cubiertos en esta documentación. Al capturar un objeto, tenga cuidado de que no haya obstáculos que le impidan ver todos los lados del objeto: Presta atención a las sombras y luces. Use un oclusor si es apropiado como se describe en ¿Cuándo? sección.



4.1.2. Disparar Configuración del corrector de color Se utiliza un comprobador de color para equilibrar el blanco de las fotos, pero también como una métrica de escala para el activo virtual. Saber el tamaño de los objetos reconstruidos es importante ya que el proceso de fotogrametría pierde esto información. Encuentra una buena ubicación para el corrector de color. Lo suficientemente cerca del tema, pero no debería ser A la sombra de él. Encuentre un lugar en la escena que pueda eliminarse fácilmente durante el proceso, o digitalmente pintarlo El corrector de color por lo general debe estar mirando hacia el cielo.

Opción de distancia / resolución También es necesario evaluar la importancia del objeto a capturar. Los activos que aparecen cerca de la cámara en su juego requerirán más resolución de textura en el juego que los activos de fondo. Debe definir presupuestos de textura para sus diversos activos, y estas decisiones impulsarán las elecciones que realice en su Shoot. La distancia de disparo desde el objeto depende del tamaño del objeto en sí, el zoom de la lente y el presupuesto de textura. El objeto debe llenar la mayoría de sus imágenes para maximizar la calidad de la reconstrucción. Cuando se desea una resolución más alta, se necesitan imágenes más cercanas. Tenga en cuenta que puede llevar mucho tiempo cubrir un objeto grande como un tocón de árbol con una resolución micro \(consulte la sección Textura detallada\). Además, Reality Capture tiene un límite en el número de fotos que puede proporcionar como fuente para la reconstrucción en función de la licencia elegida. En la práctica, para la captura de un objeto grande como este tocón de árbol con una textura final de 4096x4096, las fotos deben tomarse a una distancia de entre 1 y 2 metros.

Ubicación de los disparos Al disparar un objeto, es importante tener una cobertura completa de él. Todas las partes del objeto deben estar cubiertas por varias imágenes para que el software de reconstrucción pueda crear grupos de píxeles similares, de modo que el activo final no tenga agujeros o áreas debajo del muestreo. Idealmente La ubicación de los disparos debería tener este aspecto \(Captura de pantalla de 3dsMax\):

El patrón se realiza moviendo alrededor del objeto y tomando muchos tiros lejanos, y algunos disparos más cortos para proporcionar más detalles en el paso de reconstrucción. En cada ubicación horizontal de la cámara, es importante cubrir también el sujeto verticalmente. En la práctica, puede ser difícil seguir este camino ideal y puede terminar con algo que se parece más a la imagen de abajo \(Captura de pantalla de Reality Capture\):

Es fácil perderse elementos durante el rodaje. No dude en tomar muchas fotos y validarlas en una computadora si es posible \(Ver 4.1.1. Probar la alineación de las imágenes\). . Una vez que finaliza el viaje, es costoso regresar al mismo lugar y es difícil de igualar con el clima y las condiciones de iluminación. Además, se puede hacer un video GoPro 4k rápido del objeto siguiendo una ruta similar. Este video se puede usar más tarde como una copia de seguridad para extraer el área faltante o en el caso de un área de submuestreo o mal reconstruida \(consulte Alinear imágenes\). Es rápido de hacer y puede ahorrar muchos días de corrección de reconstrucción. El verificador de color debe estar en el video para poder equilibrar los cuadros extraídos. El Gopro puede usarse también para cubrir áreas difíciles para una cámara. Por ejemplo, la cámara no puede hacer la parte inferior del muñón.



Cobertura de disparos El software de reconstrucción debe tener suficientes píxeles similares dentro del conjunto de imágenes para producir la nube de puntos. Para una reconstrucción precisa, se recomienda tener una superposición del 90% entre las imágenes.

En términos prácticos, simplemente significa que entre cada toma, realice un paso lateral de unos 30 centímetros y mantenga el enfoque de la cámara en los sujetos, luego haga fotos de arriba a abajo para cubrir los objetos. No dudes en tomar más fotos de las necesarias. Tenga cuidado de disparar solo cuando la cámara esté estable. Cualquier movimiento al disparar resultará en una foto borrosa. Métrica de escala Por lo general, es importante mantener la misma proporción entre el mundo real y sus activos virtuales reconstruidos, según el contexto de su juego. Para lograr esto, se requiere tener un objeto de referencia de un tamaño conocido en la malla reconstruida que se pueda usar para definir la escala. Cualquier objeto puede ser utilizado. El comprobador de color es un buen candidato, ya que está ubicado cerca del sujeto e incluye una regla de 5 cm:

Para objetos más grandes como un castillo, podría medir una parte de él para que sepa la escala del mundo real.

Objetos enormes Se recomienda utilizar la grabación de video con drones en lugar de imágenes para objetos tan grandes, ya que la calidad no es significativamente mejor y el video le permitirá tener una cobertura fácil de los objetos. Nota: Es posible mezclar tomas cercanas tomadas a mano con tomas lejanas tomadas por el drone. Alternativamente, el avión no tripulado se puede usar para crear un área de marcador de posición o un elemento temporal. El siguiente ejemplo muestra un área reconstruida con Reality Capture con fotos extraídas de un video de avión no tripulado. Se puede utilizar como un diseño rápido de marcador de posición:

4.2. Cómo capturar una superficie. El proceso de fotogrametría se puede usar para capturar una superficie que luego se usa en un juego como material.

4.2.1. Preparar el area Primero, busque un lugar sin sombras o use un oclusor para protegerlo de una iluminación directa significativa. Eliminar los elementos no deseados. Preste atención a los elementos o patrones significativos, especialmente si el objetivo es crear un material enlosable. Evite caminar en el área que se va a capturar para no dejar huellas o romper elementos naturales. En la ubicación, use marcadores \(Ej .: estacas para tiendas para superficies blandas, tizas para superficies duras\) para definir el área a capturar \(marcada con flechas rojas en la foto de abajo\). Para texturas de 2Kx2K y una proporción de texel de 1K texel Por metro en un juego, use un área de 2mx2m. Es importante mantener la misma proporción entre el mundo real y el activo virtual. Coloque el marcador de color cerca del área para capturar:

4.2.2. Disparar Capturar un terreno Como referencia \(recordatorio de ubicación o para realizar un seguimiento de los disparos\), se recomienda tomar fotografías del entorno circundante antes de escanear la superficie del suelo. Para escanear una superficie del suelo, tome fotografías de la vista superior siguiendo una trayectoria en espiral desde el exterior hacia el centro. Muévete de lado con la cabeza orientada hacia el centro. Asegúrese de no interactuar con elementos de tierra en el Pise el suelo y preste atención a la sombra de su cuerpo y a sus propios pies, de lo contrario la reconstrucción sufrirá por ello:

A continuación se muestra un ejemplo de resultado en Reality Capture. Como se esperaba, no es posible tener un camino perfecto, solo debe asegurarse de que toda el área esté cubierta. 179 fotos tomadas:

Capturando una superficie vertical: Como referencia \(recordatorio de ubicación o para realizar un seguimiento de la sesión\), se recomienda tomar fotografías del entorno circundante antes de escanear la superficie. Para escanear una superficie vertical, tome fotografías siguiendo una trayectoria de lado a lado como se muestra en el ejemplo a continuación. Coloque el comprobador de color paralelo a la superficie si es posible. La captura se puede hacer dos veces, la segunda vez en una posición más cercana para proporcionar más detalles al material.

Estos materiales se pueden usar en geometrías hechas a mano o geometrías reconstruidas a partir de una GoPro o un video de drone. El video en este caso es una forma realmente rápida de crear activos, ya que es realmente rápido de capturar sin sacrificar la calidad de los activos. La geometría proporcionará la información detallada gruesa mientras que los materiales proporcionan los detalles finos.



4.2.3. Texturas de detalle

Las texturas de detalle son una capa secundaria de texturas que se utiliza en combinación con la textura principal para agregar detalles en una escala diferente. Por ejemplo, una textura de roca que cubre una gran área de un modelo puede mejorarse al agregar una textura de detalle de mayor resolución a una escala mucho más pequeña que muestra pequeñas grietas e imperfecciones en la roca. \(Para obtener más información, consulte [https://docs.unity3d.com/Manual/StandardMaterialParameterDetail.html](https://docs.unity3d.com/Manual/StandardMaterialParameterDetail.html)\) El material escaneado puede beneficiarse de la misma técnica, escaneando primero a un nivel aproximado y luego realizando un segundo escaneo detallado que se puede combinar cuando Dibujando el material en el juego. El proceso de captura para texturas detalladas es el mismo que para las superficies normales, excepto que las tomas son Enfocado más de cerca en un área pequeña. El área elegida para producir la textura de los detalles debe ser lo más genérica posible, ya que las texturas de los detalles se suelen colocar en mosaico muchas veces en el objeto en comparación. Con la textura principal. En la práctica, los disparos se realizan en el límite de enfoque automático más cercano. El siguiente ejemplo muestra a la izquierda el sujeto grueso, utilizado para crear la geometría y el material base, y a la derecha el Área detallada escaneada para producir texturas de detalle. La distancia es el mínimo permitido por el enfoque automático:

Solo debe seleccionar un área pequeña para usar como una textura de detalle. Si intenta utilizar grandes áreas de su objeto, ya que la textura de los detalles dará como resultado texturas que tienen una resolución demasiado alta y perderán tiempo durante el proceso de disparo. La siguiente imagen es un resumen de la distancia correcta del sujeto para cada propósito: Geometría: fotos globales para capturar la forma principal de un objeto. Geometría de detalle / Material: fotos más cercanas para traer más detalles de la geometría y producir un material utilizable. Detalle de la textura: Fotos hechas en primer plano en el límite de enfoque automático. Se utiliza para producir texturas de detalle.



4.3. Cómo capturar un objeto pequeño Los objetos pequeños a menudo se usan para poblar una escena mediante la duplicación de muchos de los mismos objetos pequeños en diferentes áreas. Se pueden rotar, escalar y reflejar para crear variedad. Para tales objetos, se requiere cubrir todas las partes desde todas las direcciones para reconstruir activos completos.

4.3.1. Establecer un soporte Para poder capturar un objeto pequeño desde todos los ángulos, es necesario poder girarlo desde todos los ángulos. Los objetos pequeños se pueden sostener frente a la cámara usando una abrazadera de soporte, idealmente con tan poco contacto con el objeto como sea posible. Entonces, el primer paso es encontrar un buen soporte. La naturaleza exacta del soporte que necesitará dependerá de la forma y estructura del objeto que está capturando. Debido a que es difícil transportar todo el equipo durante un viaje, a menudo puede ser preferible reunir objetos pequeños, traerlos de vuelta a su estudio y capturarlos en un lugar seguro cerca de la computadora con el software de reconstrucción. Esto también te permite tener control total de la iluminación. La imagen de abajo muestra algunos ejemplos de soportes. A la izquierda, se utilizan un trípode y un tornillo para capturar todas las partes del cono de pino. A la derecha, se utilizan pinzas de sujeción para poner la raíz de hiedra en una buena posición para el capturar.

El tipo de soporte requerido varía según el objeto, pero las pautas comunes son: ■ Coloque el objeto en una posición donde todas las partes a capturar sean visibles. ■ Minimice la parte del soporte que debería borrarse más tarde. ■ El soporte y el sujeto deben ser estables. 4.3.2. Disparar No hay una recomendación específica para la cantidad de imágenes necesarias para capturar un objeto por completo. Objetos complejos como un cono de pino pueden requerir miles de fotos. Usa un camino serpenteante de izquierda a derecha Alrededor del objeto para obtener una buena cobertura. Ejemplo de ubicación del disparo \(posiciones teóricas simuladas con 3dsMax\):

Deje la escena en su lugar y verifique la alineación de la foto \(consulte Alinear imágenes\). Si el software de reconstrucción no puede hacer que las imágenes coincidan entre sí para generar una sola nube de puntos \(y por lo tanto, genere múltiples mallas en lugar de una sola\) y luego haga fotos adicionales donde falle. En la imagen de abajo, las cámaras rojas representan una segunda sesión de disparo para aumentar la coincidencia de imágenes y producir una sola nube de puntos. No dude en hacer más fotos para resolver el problema, es más rápido que usar las funciones y los ayudantes del software.

4.4. How to capture the diffuse albedo only

4.4. Cómo capturar el albedo difuso solamente.

El albedo difuso es el color independiente de la vista del objeto. El proceso regular para recuperar el albedo difuso de las texturas generadas del proceso de fotogrametría se explica en otra sección e implica un paso de eliminación de la luz \(consulte Eliminar iluminación\). El proceso detallado en esta sección le permite crear una textura que está cerca de difundir el albedo de un objeto directamente desde las fotos. El proceso no es simple y no se puede usar con cientos de fotos; está dirigido a tomar 1 o 2 fotos que se pueden usar directamente como una textura de albedo difusa para elementos pequeños \(consulte Cómo capturar follaje\) o como referencia para Valide el resultado del paso de eliminación de la luz. Después de un disparo, se recomienda tomar una imagen cercana del albedo difuso del objeto con el método descrito aquí. Como se explica, ayudará a validar el albedo reconstruido después del proceso de remoción de luz.

Para capturar un buen albedo difuso, necesita usar dispositivos específicos: un anillo de flash y dos filtros polarizadores. Un polarizador de lente para la cámara, un filtro polarizador lineal para la fuente de luz. El objetivo es eliminar cualquier efecto dependiente de la vista como la reflexión. Configuración de los filtros polarizadores Los filtros polarizadores se pueden girar para permitir más o menos admisión de luz polarizada. El primer paso es identificar la orientación de los filtros. Esto se puede hacer con una pantalla LCD. Pantallas LCD de uso lineal. filtros polarizados, por lo que si otro filtro polarizador cubre la pantalla con un ángulo de 90 °, se bloquea la iluminación de la pantalla. A 0 ° pasará la iluminación. Con esta prueba, la película polarizada y el filtro polarizado se pueden alinear fácilmente.

Para poder capturar un color cerca del albedo difuso, es necesario eliminar la mayor cantidad posible de información de luz direccional. El objetivo del método de esta sección es tomar fotos en las que solo se ve la iluminación filtrada controlada de un flash en los sujetos. Esto significa que la iluminación proveniente del flash debe ser más brillante que la del ambiente y, por lo tanto, más visible.

Se recomienda un flash de anillo sobre un flash de cobra, ya que produce sombras paralelas a la vista que no son muy visibles en la foto. El anillo de flash se aumenta con una película de filtro polarizador lineal en las luces led para Polarizar linealmente la iluminación del flash. Luego se usa un polarizador de lente para que la cámara elimine el reflejo del flash. Con esta configuración, el filtro polarizador de la lente se puede girar a 0 ° o 90 ° para obtener fotos con o sin especular \(lo que significa que tanto el filtro de la lente como el filtro de flash son paralelos o perpendiculares\). El siguiente ejemplo ilustra el resultado de usar la configuración anterior. A la izquierda, con la orientación del filtro del objetivo a 0 ° \(es decir, los filtros del polarizador de la lente y la luz tienen la misma orientación\), se ve el especular del flash. A la derecha, con una orientación del filtro del objetivo de 90 ° \(es decir, los filtros del polarizador de la lente y la luz tienen una orientación diferente\), la mayor parte de la reflexión del flash se filtra. Para minimizar la reflexión del entorno, ajuste la exposición con una velocidad de obturación inferior a 1/180 \(velocidad de flash CANON MR-14EX II\). Con esta configuración, solo la iluminación proveniente del flash debe estar presente en la foto. Estas fotos pueden proporcionar información para producir una textura de rugosidad / suavidad. La foto polarizada debe ser blanca balanceada con el comprobador de color para tener la exposición correcta \(ver Balance de blancos\). El resultado es una foto que representa cómo se ve el albedo. Si todos los disparos se pudieran tomar con este método, el proceso de extracción de la luz puede no ser necesario. Sin embargo, hay algunos problemas con este enfoque: ● La oclusión del soporte del filtro de la lente implica que se requieren más fotos ya que hay menos cobertura. ● Las baterías del flash no son lo suficientemente potentes para ser utilizadas intensivamente. Las baterías están vacías después de algunos disparos. ● El tiempo de captura aumenta mucho, ya que es necesario esperar la recarga instantánea, lo que hace que el proceso sea impráctico. ● Esta configuración no funciona si el sujeto está bajo una iluminación fuerte como el sol. El sol es tan poderoso que todavía produce sombras y especular \(flechas rojas en el ejemplo a continuación\) en las fotos iluminadas por flash. La solución es utilizar un oclusor. Ejemplo de foto tomada con flash de anillo con velocidad de obturación en 1/4000:



Sin la inclusión de objetos de longitud conocida en el proyecto, la fotogrametría genera representaciones 3D sin escala.

More tips























