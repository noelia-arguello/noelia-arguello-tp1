Etapa de Diseño y Prototipado (Figma)
El proceso comenzó con el desarrollo de un wireframe de baja fidelidad en Figma para establecer la estructura inicial. Tras definir la paleta cromática y los estilos tipográficos, escalé el diseño hacia un wireframe de alta fidelidad. Para optimizar el flujo de trabajo, creé una página específica de componentes donde estructuré el header y el footer, proyectándolos de manera responsiva para evitar deformaciones al adaptar sus contenedores en formatos de escritorio. En este espacio configuré también los botones utilizados posteriormente en la sección "Sobre mí".
En el armado de las páginas, definí la composición del hero y las secciones de los diferentes frames. Inicialmente, utilicé rectángulos grises y texto simulado (placeholder) para esquematizar el espacio, los cuales sustituí más tarde por el contenido e imágenes reales.
Para la página de inicio (index), diseñé una galería interactiva donde las imágenes thumbnail de los diseños destacados redirigen a sus respectivos proyectos individuales.
En la sección "Sobre mí", proyecté la inclusión de un menú desplegable tipo hamburguesa; dado que aún no dominaba su animación en Figma, plasmé la idea visualmente para priorizar su desarrollo en la etapa de código. 
Por su parte, la sección de contacto se estructuró siguiendo los videos del campus virtual.

2. Adaptación Mobile y Optimización
Una vez resuelta la versión de escritorio para el index, realicé la adaptación a maquetación mobile tomando como base el ancho estándar más compacto (320px). En esta instancia, reorganicé la jerarquía de la información y reajusté las escalas tipográficas y de las imágenes para garantizar la legibilidad en pantallas pequeñas. En paralelo, preparé y exporté una carpeta con todos los recursos visuales optimizados para web.
Con la información definitiva cargada, utilicé el sistema de prototipado de Figma para vincular los flujos entre pantallas. 
Finalmente, ordené el archivo renombrando las capas con etiquetas semánticas y apliqué Auto Layout de manera concéntrica (desde los elementos internos hacia los contenedores padre).

3. HTML y CSS
El traspaso al código HTML se vio facilitado por la organización previa de las capas en Figma, lo que me permitió comprender con mayor claridad la segmentación semántica mediante <section>, <div> y demás etiquetas estructurales.
La etapa más compleja radicó en la implementación de las propiedades de Flexbox y en la gestión de las diferentes unidades de medida (píxeles, porcentajes, vh, rem); requirió un tiempo de experimentación asimilar cuál era la unidad óptima para cada contexto. 
El desarrollo de una hoja de estilos unificada (estilos.css) representó un desafío. Debido a la extensión del archivo, tengo dudas sobre posibles redundancias en el código, aunque a nivel general la interfaz se comporta como lo planifiqué.

En lo personal, el comportamiento elástico del contenedor general presenta ciertos desafíos pendientes; por ejemplo, al reducir la pantalla en escritorio, las secciones de ilustraciones y diseño tienden a alinearse a la izquierda en lugar de mantenerse centradas. Sin embargo, el proyecto consolidó mi comprensión sobre el comportamiento de los atributos de contenedores y elementos, y significó un avance sustancial en el aprendizaje del diseño adaptativo e interactivo. 
Sobre github, sigue siendo complejo para mí el utilizarlo, aunque supongo que cuando lo aprenda a usar va a resultar muy útil.

Tamaño de la pantalla:  1366x768
Editor de código: Visual Studio Code
Link a Figma:
https://www.figma.com/design/i4Pd5jmm6cEcvGqX6WiBkm/arguello_portfolio?node-id=2-4&t=xV753CZuGvHXyEAM-1
