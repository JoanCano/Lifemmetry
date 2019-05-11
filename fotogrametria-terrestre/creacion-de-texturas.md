# CREACIÓN DE TEXTURAS

Ya tenemos nuestro modelo de alta resolución con textura y nuestro modelo de baja resolución con nuevas coordenadas de mapeado. El siguiente paso en el proceso consiste en usar la información de nuestro modelo de alta resolución para crear nuevos mapas para el modelo optimizado. Esta tarea puede realizarse con multiples aplicaciones como xNormal, el propio ZBrush, etc. En nuestro caso hemos preferido usar Substance Designer por si facilidad de uso, sus excelentes resultados y la posibilidad de automatizar el proceso en múltiples modelos a la vez.

 **Albedo:** Es la textura generada por Photoscan proyectada sobre las nuevas coordenadas de mapeado.  
**NormalMap:** Contiene la información de altura del modelo de alta resolución en forma de mapa de normales.  
**Linear Displacement:** Información de altura del modelo original en escala de grises.  
**AO/Curvature:** Util para añadir volumen “artificial” a nuestra textura, puede ser interesante en video juegos.  
**Local Normal:** Mapa de normales local que puede ser de utilidad para hacer _delighting_ manual si es necesario.  
**Glossiness:** En nuestro caso este mapa se obtiene de forma manual usando una combinación de albedo, altura y fotografías de referencia.

Además de una geometría optimizada, todos los modelos de este pack cuentan con texturas y materiales PBR para **V-Ray 3.5 o superior**.

El albedo ha sido obtenido a partir de fotografías lineales calibradas con color checker, el mapa de normales ha sido extraído directamente de la geometria de alta resolución y los modelos donde es necesario, cuentan con un mapa de glossiness. Todas las texturas se ofrecen en 2 resoluciones:

**Versión Pro:** 4K recomendado para renders de alta resolución o planos de detalle.  
**Versión Lite:** 2K para uso general.

Todos los materiales PBR de este pack han sido diseñados para **Vray 3.5 o superior** para poder aprovechar la opción **“Glossy Fresnel”** del motor de render que permite obtener los mejores resultados de la forma más efectiva. El resultado en versiones anteriores de V-Ray puede variar respecto a las imágenes del catálogo.

