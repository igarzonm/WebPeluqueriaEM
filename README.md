# Página Web del Cliente - Peluquería Elisa Martín
### En esta página hemos requerido del uso de HTML y CSS, ayudándonos con componentes de Bootstrap
En este documento se describirá de forma simplificada los componentes e información utilizados. Para la estructura de la web, podemos decir que se reparte en una página principal (index) y 4 subpáginas, en las cuales encontramos el contacto, una galería, quiénes somos y los servicios que ofrece la empresa. Aclaramos que todas las webs dichas anteriormente son Responsive.

- La página principal **Index** la hemos estructurado de la siguiente forma: primero, hemos utilizado dos navs, uno en el que vemos una breve descripción del horario, junto con el teléfono y enlaces a redes sociales, y el otro Nav que será la barra de navegación. Esta barra de navegación dispondrá también del logo de la empresa junto con su nombre, además de los botones para acceder a las otras subpáginas. También se ha incluido un botón en el cual colapsará el nav en cierto tamaño de la pantalla.<br>
Después de los navs, encontraremos un Carousel, en el que se presentan 3 imágenes con sus correspondientes textos relacionados y botones de acceso a otras subpáginas. Además de esto, debajo de ese carousel tenemos un formulario para coger cita en esa peluquería.<br>
Debajo del bloque anterior, encontraremos información simplificada de los que serían los servicios que se ofrecen, todos ellos estructurados mediante filas y columnas dentro de un container, con su márgen y padding idóneo. Además de eso, tenemos un botón de enlace a la galería de la empresa.<br>
Por último, encontramos el footer, en el que se muestra el nombre de la peluquería e información de contacto.

*A continuación explicaremos la estructura de las subpáginas. Cabe destacar que los navs y footer de todas ellas son similares al index, por lo cual no serán descritas en los siguientes puntos.*

- La primera subpágina sería la de **quiénes somos**. En esta subpágina queremos enseñar breves descripciones, tanto del equipo como de las instalaciones de la peluquería. Para ello, hemos requerido de la utilización de filas con offsets y columnas, de forma que tenga la estética que se puede contemplar, además de CSS para tamaños y posicionamiento tanto con Bootstrap como estilo puro.<br>
Debajo de éste, podemos observar un horario y un iframe de la página de Facebook.

- En la segunda subpágina encontramos los **servicios**. Para mostrar los servicios hemos utilizado una estructura  de bloques separados con offsets y márgenes. En cada bloque se muestra un servicio, junto con una descripción y una imagen. Estos bloques tiene un estilo propio con :hover para dar interacción y sea intuitivo para el cliente.

- En la tercera subpágina, la **galería**, podemos ver todo el repertorio de imágenes que tiene la empresa. Para mostrarlas, tenemos un carousel con botones para avanzar o volver atrás. Las imágenes de ese carousel las tenemos estructuradas gracias a columnas con la clase Card. Aparte de dicho carousel, también se puede ver un botón con el que acceder al Instagram de la peluquería.
