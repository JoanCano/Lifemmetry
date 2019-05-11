# Psotproceso imágenes

Necesitará las siguientes herramientas para el posprocesamiento. No necesitan ser instalados para la captura de imágenes, y no necesariamente tienen que estar instalados en la misma computadora:  Herramientas para convertir archivos RAW al formato recomendado de Conversor de Negativo Digital \(DNG\). Adobe Los productos como Photoshop, Lightroom y Adobe Bridge incluyen Adobe Camera Raw, que es una entorno para realizar esta conversión, así como para realizar ajustes en las imágenes.

Primero se deben calibrar las fotos \(balance de blancos\), luego enviarlas a una aplicación de reconstrucción. los La aplicación de reconstrucción compara las formas en las fotos \(alineación\) para generar una alta resolución. Malla 3D. El color contenido en las imágenes se transfiere a los colores del vértice de la malla \(Colorear\) o texturas usadas en la superficie de la malla.

Nota: El software de reconstrucción puede generar una malla de muy alta resolución, que no es adecuada para uso en motores en tiempo real, por lo tanto es necesario generar una resolución más baja para este propósito. Es posible crear una malla de resolución más baja al tiempo que conserva los detalles de la malla de alta resolución Generando un mapa normal con herramientas para hornear. Las herramientas de cocción transferirán información de alta frecuencia. desde la malla de alta resolución hasta las texturas de mapa normales de la malla de baja resolución. A continuación, se debe crear una malla de baja resolución para el proceso de horneado: una resolución media a baja la malla se exporta desde el software de reconstrucción y se modifica en una herramienta de software 3D para ser utilizada como Destino de las herramientas de cocción \(Retopología y paso de diseño UV\). Las herramientas para hornear se utilizan para generar texturas. Entonces, las texturas necesitan tener luz eliminada. Esto se debe a que las texturas son generadas desde real. Fotos del mundo, que inevitablemente tendrán luz visible y sombras presentes. Para poder tener un trabajo activo en cualquier condición de iluminación, se requiere eliminar la iluminación \(paso de extracción de luz, un paso también saber como desiluminación\) información al horno en texturas generadas. A veces en este paso las texturas son También hecho enlosable.

Finalmente, la malla de baja resolución para hornear se convierte en una malla lista para el juego \(Malla con Orientación, pivote y conjunto uv\) en una aplicación de software 3D.

La fotogrametría es una forma muy eficiente de crear mallas y texturas de alta resolución, pero no ayuda con otros procesos que son necesarios para la preparación de la malla del juego \(como el paso de retopología, el paso de diseño UV\). Si ahorra tiempo o no en comparación con la creación de activos en 3D tradicional depende de la complejidad del objeto en cuestión. Usar el proceso de fotogrametría en producción no es una tarea sencilla, ya que varía según la complejidad del objeto y el tiempo de retopología. Por lo general, es una victoria, pero puede ser difícil cuantificar el tiempo ahorrado.

### SOFTWARE

DCRaw: Convert RAW to TIFF Windows: [http://www.centrostudiprogressofotografico.it/en/dcraw/](http://www.centrostudiprogressofotografico.it/en/dcraw/)

Adobe Photoshop CC: White balancing, artefacts correction [http://www.photoshop.com/products/photoshop](http://www.photoshop.com/products/photoshop)

Reality Capture: Photogrammetry processing software [https://www.capturingreality.com/](https://www.capturingreality.com/)

3dsMax \(or any related 3D software\): Retopology, UV, LOD [https://www.autodesk.fr/products/3ds-max/overview](https://www.autodesk.fr/products/3ds-max/overview)

Instant Mesh: Retopology. [https://github.com/wjakob/instant-meshes](https://github.com/wjakob/instant-meshes)

Knald: Baking textures [https://www.knaldtech.com/](https://www.knaldtech.com/) Note: A good GPU card is recommended. 8GB of Vram is advised for very high meshes \(&gt;400M of polygons\)

Xnormal: Baking textures [http://www.xnormal.net/downloads.aspx](http://www.xnormal.net/downloads.aspx)

Substance designer: Baking textures [https://www.allegorithmic.com/products/substance-designer](https://www.allegorithmic.com/products/substance-designer)

Unity Light Removal Tool: remove lighting from albedo baking. [https://github.com/Unity-Technologies/DeLightingTool](https://github.com/Unity-Technologies/DeLightingTool)

Artomatix: automatic tiling material. [https://artomatix.com/](https://artomatix.com/)

Substance painter: Manual tiling material. [https://www.allegorithmic.com/products/substance-painter](https://www.allegorithmic.com/products/substance-painter)

VLC media player: Video to frames [http://www.videolan.org/index.fr.html](http://www.videolan.org/index.fr.html)

