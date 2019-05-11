# Principios básicos

## Ideas para la redacción

técnica de captura de imágenes

Estructura desde el movimiento \(SfM\). determina posición y orientación de la cámara en relación con el sujeto de imagen, para cada foto. Durante el procesamiento, la calibración y la postura de cada cámara se hacen cada vez más precisas a través de un proceso iterativo. Los puntos en la nube dispersa se crean a partir de coincidencias de vecindarios de píxeles similares identificados en varias fotos. Si se encuentran vecindarios de píxeles coincidentes en dos, o preferiblemente más, fotos, las áreas ocupadas por los vecindarios de píxeles en las fotos respectivas se proyectan en la escena virtual en 3D. Estas proyecciones se intersecan en forma de un volumen común en la escena 3D y se representan como un punto en la nube dispersa. La incertidumbre posicional \( precisión\) de estos puntos se reduce A medida que aumentan las precisiones de las posiciones de los puntos, también aumentan las precisiones de la calibración y la postura de la cámara.

los conjuntos de captura fotográfica se pueden adquirir usando combinaciones de cámara / lente no calibradas.

os algoritmos SfM necesitan un conjunto de correspondencias de puntos coincidentes. Estos puntos coincidentes se encuentran en las fotografías superpuestas de una red de imágenes planificada, capturadas desde diferentes posiciones y orientaciones en relación con el sujeto de la imagen. La forma en que se mueve la cámara en relación con el sujeto tiene un gran impacto en el grado de precisión \( incertidumbre posicional \) presente en las mediciones de la representación 3D asociada.

Sin la inclusión de objetos de longitud conocida en el proyecto, la fotogrametría genera representaciones 3D sin escala.

