Bienvenidos a Yavu CMS
======================

Acerca de
---------
**Yavu CMS** es un sistema de gestión de contenidos (las siglas corresponden a Content Manager System) desarrollado por el Centro Superior para el Procesamiento de la Información (CeSPI), con el fin de brindar una solución integral a todas las dependencias de la Universidad Nacional de La Plata, y otros, para la elaboración, puesta en producción y mantenimiento de sitios web.

Estructura
----------
Antes de comenzar a utilizar Yavu CMS, es necesario conocer su estructura. Sobre el servidor del administrador de contenidos pueden instalarse diversas **aplicaciones cliente**, es decir, micrositios que estarán compuestos de los elementos descritos a continuación.

Cada aplicación cliente puede tener uno o más **suplementos**, que funcionan a modo de subsitios, pues tiene una estructura particular que está dada por las **secciones** que organizan temáticamente el contenido periodístico. Una universidad, por ejemplo, puede agrupar los contenidos según sean institucionales, académicos, de investigación, de extensión, etc.

A su vez, existen otros elementos llamados **ediciones**, que organizan el contenido de los suplementos de manera temporal. Un diario, por ejemplo, puede tener un suplemento con ediciones diarias, para mostrar el contenido de su página principal, y suplementos con ediciones semanales, como los dedicados a juventud, cocina, cultura, etc.

Es importante saber que tantos las secciones como las ediciones son útiles para mostrar e invisibilizar contenido a los usuarios. Por poner otro ejemplo, una universidad podría crear ediciones anuales para ocultar contenido que ya no sea útil a sus alumnos y docentes.

Resta agregar que los contenidos de las secciones son, principalmente, **artículos** a los que se asociacian **medios**, es decir, imágenes, audios, videos, archivos y cualquier contenido externo.

Organización - Usuarios
-----------------------
**Yavu CMS** reconoce tres grupos de usuarios genéricos, a los que otorga una serie de permisos y funciones que entenderemos como **roles**; a saber:

###Administrador
Es el encargado de crear usuarios y establecer los roles de cada uno de ellos; debe configurar el sistema, administrar las aplicaciones, los componentes y los servidores, así como la estructura del sitio (categorías, ediciones, suplementos, secciones y portadas). Además de las funciones específicas propias de su rol, tiene permisos para realizar las tareas de los periodistas y diseñadores.

###Diseñador
Es el encargado de establecer la estructura y diseño visual de los diversos suplementos y portadas del sitio.

###Periodista
Es el encargado de cargar los artículos y las multimedias asociadas, es decir, imágenes, videos, audios y demás elementos que complementan la información escrita.

Artículos
=========

Se llama *artículo* a todo contenido periodístico que, para ser visible, debe incorporarse en la portada de un suplemento. Los mismos se asociacian a *secciones*, elementos que permiten organizar temáticamente la información, y pueden tener asociados uno o más *medios*, es decir, imágenes, archivos, audios o contenidos externos embebidos.

Creación de artículos
---------------------
**Usuario:** Periodista

**Acceso:** Articulos>Nuevo

Completar los campos de texto:
- **Volanta**
- **Título**
- **Bajada**
- **Cuerpo:** por defecto Yavu CMS ofrece un editor de texto básico que además de las opciones de formato y estilo, permite maximizar la interfaz de redacción y cambiar al modo Fuente HTML para incrustar código en el interior de los artículos.
- **Firma:** campo opcional para indicar quién es el autor del artículo.
- **Categorías:** son palabras clave que mejoran la indexación de los contenidos. Al redactar las primeras tres letras, el sistema intentará autocompletar las palabras para que coincidan con aquellas que ya hayan sido utilizadas. En caso de que no existan, redacte la o las palabras separadas por comas para crear la categoría. Si el periodista no completa este campo, un algoritmo definirá las palabras más importantes del texto en cuestión.
- **Hora:** es posible especificar la hora de publicación. El formato es HH:mm 24 hs.
- **Sección** 
- **Edición**
- **Artículos relacionados:** si desea vincular artículos, comience a escribir el o los títulos en cuestión y seleccione alguna de las opciones del autocompletado que le ofrece el sistema.
- **¿Es visible?:** para publicar un artículo en alguno de los suplementos de su sitio, tilde este campo. Si, en cambio, desea trabajar en el artículo sin publicarlo, deje sin tildar este campo.
- **Ocultar en portadas de sección**
- **Atributos extra**
- **Estadísticas:** puede establecer votos positivos, votos negativos y visitas de base.

Al finalizar, hacer clic en *Crear artículo*. Acto seguido, Yavu CMS mostrará una vista previa del artículo y la meta información que lo acompaña. Desde allí, podrá modificar, duplicar y borrar el artículo en cuestión, o bien, ir al listado que muestra todos los artículos que hayan sido creados.

Administración de multimedias
-----------------------------
**Usuario:** Periodista

**Acceso:** hacer clic en la opción *Modificar* y, a continuación, acceder a *Administrar Medios*.

Existen tres opciones para asociar contenidos multimediales a un artículo:
- **Seleccionar medios existentes:** mediante esta opción puede buscar imágenes, audios, archivos o contenidos embebidos que hayan sido previamente cargados; ya sea porque forman parte de un archivo, porque fueron utilizados en artículos anteriores o porque los cargó un colega. Para filtrar los resultados puede ingresar palabras clave en el cuadro de Búsqueda rápida, comenzar a escribir el título de un artículo al cual se encuentra asociado el contenido multimedia que busca, rastrearlo por los tipos detallados al inicio de este párrafo, o bien, por la fecha en que fueron utilizados. Recuerde hacer clic en *Buscar* para hacer efectiva la búsqueda. Posteriormente, seleccione con un tilde el elemento a asociar.
- **Subir medios de su equipo:** la segunda opción consiste en subir a la web elementos que se encuentren en su computadora. Para ello, simplemente hay que seleccionar el tipo de medio a subir (imágenes, audios o archivos) y arrastrarlos a la zona gris de la interfaz, o bien, hacer clic donde dice *Arrastre aquí los archivos a subir o haga click aquí para seleccionarlos* y navegar por el explorador para encontrarlos.
- **Agregar contenido embebido:** la última opción le permite crear una referencia en el sistema a contenidos multimediales que se encuentran en otros sitios web, es decir, embeberlos para mostrarlo en su página. De esta manera es posible asociar videos de Youtube, Vimeo y otros; audios de Souncloud, Goear y otros; mapas de Google, Bing, Mapbox, CartoDB y otros; publicaciones de Facebook, Twitter, Instagram, etc. así como cualquier contenido con un código embebed. Para hacerlo, simplemente hay que ingresar una descripción del contenido, establecer la fecha de carga o aquella a la que pertenece el elemento y pegar en el campo *Contenido* el código en cuestión.

Al asociar contenidos multimediales de cualquiera de las tres maneras, se desplegará una fila en la interfaz que mostrará los medios que han sido asociados al artículo. Para cada uno de ellos podrá establecer *Epígrafe*, *Título* y *Texto alternativo*. Este última se utiliza para la indexación de las imágenes y para brindar información a los lectores de pantalla utilizados por personas con discapacidad.

En el caso de que haya asociado más de una imagen, podrá seleccionar con un tilde aquella que debe ser la *Imagen principal*, a mostrarse en los módulos de artículos con imagen.

Al finalizar, recuerde hacer clic en *Listo*, para ingresar los cambios.

Acciones sobre el listado de artículos
--------------------------------------

**Usuario:** Periodista

**Acceso:** Artículo>Listado

En el listado de artículos se muestra una vista rápida de todos los artículos que hayan sido cargados, que consta del título, la bajada y la metainformación que acompaña a los artículos. Por defecto, este listado se encuentra ordenado según la fecha de publicación.

El usuario puede modificar el orden por defecto de los artículos haciendo clic en los encabezados: *Artículo, Sección, Última actualización y Fecha*.

Por defecto, el administrador muestra 20 artículos, número que puede ser modificado dirigiéndose al margen inferior izquierdo del administrador. Los resultados, además, se encuentran paginados.

Para buscar un artículo específico, puede acudir a la *Búsqueda simple* introduciendo palabras clave en el campo de texto que se encuentra en el margen superior derecho del administrador y presionar enter, o hacer clic en el botón que muestra una lupa. Para obtener resultados más precisos, haga clic en *Filtro avanzado* y complemente la búsqueda con información adicional: textuales, categorías, sección, fecha de edición, actualización y publicación. De estas dos maneras, el sistema filtrará los resultados según la información solicitada. Para volver a ver el listado completo de artículos, haga clic en *Limpiar*.

Sobre cada uno de los artículos se pueden ejercer las tres acciones que figuran en la vista previa de los artículos creados:

- **Modificar:** para editar el artículo, la metainformación y asociar contenido multimedia.
- **Duplicar:** para crear una copia del artículo en cuestión.
- **Borrar:** para eliminar el artículo.

Medios
======

Se llama *medio* al contenido multimedial que acompaña a los artículos, es decir, imágenes, archivos, audios o contenidos externos embebidos.  

Creación de medios
------------------

**Usuario:** Periodista

**Acceso:** Contenido>Medios

Para cargar imágenes, archivos, audios y crear referencias a contenidos externos para embeberlos en su sitio, debe hacer clic en Nuevo medio y seleccionar el tipo de medio a crear.

En todos los casos, deberá completar:

- **Descripción:** texto que le permita encontrar el elemento posteriormente.
- **Fecha:** de creación del elemento o de captura.
- **Tags:** etiquetas o palabras clave que mejoran la indexación de los contenidos.

Al cargar imágenes, audios o archivos, encontrará una cuarta opción.

- **Archivo:** haga clic en *Choose File* para ingresar al explorador y escoja el archivo que corresponda.

Al crear una referencia a contenidos externos, encontrará un cuadro de texto. 

- **Contenido:** pegue el código HTML para embeberlo en su sitio.

Al finalizar, hacer clic en Crear medio

Acciones sobre el listado de medios
-----------------------------------

**Usuario:** Periodista

**Acceso:** Contenido>Medios

En el listado de medios se muestra una vista rápida de todos los medios que hayan sido cargados, que consta del *Tipo de elemento* (imagen, audio, archivo o contenido embebido), la *Descripción* y la *Vista previa* del mismo.

Por defecto, el administrador muestra 20 artículos, número que puede ser modificado dirigiéndose al margen inferior izquierdo del administrador. Los resultados, además, se encuentran paginados.

Para buscar un medio específico, puede acudir a la *Búsqueda simple* introduciendo palabras clave en el campo de texto que se encuentra en el margen superior derecho del administrador y presionar enter, o hacer clic en el botón que muestra una lupa.

Para obtener resultados más precisos, haga clic en *Filtro avanzado* y complemente la búsqueda con información adicional: artículo asociado, tipo y rango temporal de publicación. De estas dos maneras, el sistema filtrará los resultados según la información solicitada. Para volver a ver el listado completo de medios, haga clic en *Limpiar*.

Sobre cada uno de los medios se pueden ejercer tres acciones:

- **Modificar:** para editar el medio y la metainformación.
- **Duplicar:** para crear una copia del elemento.
- **Borrar:** para eliminar el elemento.

Galería de medios
=================

Las *Galerías de medios* son elementos que agrupan medios y deben ser asociados a los *artículos*. 

Creación de galerías de medios
------------------------------

**Usuario:** Periodista

**Acceso:** Contenido>Galerías

Para crear una galería de elementos multimediales y asociarla a un artículo, debe hacer clic en *Nueva galería de medios*. A continuación, deberá otorgarle un *Título* y luego utilizar una o varias de las opciones que se ofrecen para seleccionar medios que hayan sido cargados al sistema: puede buscar medios asociados a un artículo específico, rastrearlo por el *Tipo* (imagen, archivo, contenido embebido o audio), empleando palabras clave o ingresando la fecha de publicación.

Posteriormente, hacer clic en el botón Buscar.

A continuación, deberá seleccionar con un tilde los medios que desea agrupar para luego asociar a un artículo específico.

Al finalizar, haga clic en *Crear galería*.

Portadas
========

Las *Portadas* son elementos que agrupan artículos para presentarlos a los usuarios de un sitio web. Las mismas se encuentran asociadas a los *suplementos*.

Visualización de artículos (agregar en portada)
-----------------------------------------------

**Usuario:** Editor

**Acceso:** Estructura>Portada

Una vez publicados los artículos, es necesario que el editor o periodista les otorgue un lugar en la portada del sitio para que sean visibles para los usuarios del sitio Web. Para ello, debe dirigirse a la pestaña *Portada*, hacer clic en *Acciones* y seleccionar la opción *Modificar portada*.

A continuación verá un maquetado gris de la estructura del sitio con espacios de trabajo/edición en blanco. Cada bloque destinado a contenido periodístico puede albergar uno o varios módulos, nombre con el que se designa a una representación particular de artículos periodísticos, creada por el diseñador del sitio. Por ejemplo, un bloque puede contener un módulo con un artículo que ocupe todo el ancho del sitio y muestre una foto, y debajo otro módulo que represente el título de tres noticias de menor importancia sin imagen.

![Editor de portadas](http://i.imgur.com/4UPQ0s1.png)

Para agregar un módulo a un bloque, debe hacer clic sobre la opción *Nuevo módulo* y luego pararse con el puntero sobre el módulo y seleccionar la opción *Configurar este módulo*, para acceder a la interfaz de edición. Realizando la misma acción, puede cambiar de lugar y borrar módulos que hayan sido creados.

1. **Tipo de módulo:** seleccionar la representación del módulo

2. **Asociar artículo:** filtre los artículos por *Fecha de edición* y *Sección* para visualizar el listado de artículos. Luego arrástrelos de la columna derecha a la izquierda.

Al finalizar, haga clic en *Listo* y, posteriormente, diríjase al final de la página para *Verificar* y *Publicar* cambios, o bien, guardarlos a modo de borrador. La primera opción hace que la edición que realizó se represente a modo de vista previa para que pueda corroborar el correcto funcionamiento de la portada, aún sin publicar sus cambios. Si está satisfecho con las modificaciones, haga clic en *Publicar borrador*. La segunda opción almacena los cambios para ser publicados posteriormente.

Categorías
==========

Las *categorías* son palabras clave que se relacionan a los artículos y medios para mejorar la indexación de los contenidos.

Creación de Categorías
----------------------

**Usuario:** Periodista

**Acceso:** Estructura>Categorías

Las categorías pueden ser creadas de manera muy sencilla en la instancia de edición de los artículos y medios escribiendo las palabras y separándolas con una coma, lo cual permite crear categorías de más de una palabra, como Universidad Nacional de La Plata. En esta instancia abordaremos su administración.

Para crear una categoría, haga clic en *Nueva categoría*. A continuación complete:

- **Nombre:** palabra clave de al menos tres letras. Por ejemplo: Universidad, La Plata, Educación.

- **Nombre único:** este campo es opcional y corresponde al nombre que figurará en la url de búsquedas, que por lo general coincide con el nombre. Por ejemplo, la categoría La Plata puede tener por nombre la_plata o simplemente LP.

- **En la lista prohibida de categorías:** si se tilda esta opción, la categoría dejará de mostrarse a los visitantes del sitio y sólo servirá para uso interno.

Al finalizar, haga clic en *Crear categoría*.

Acciones sobre el listado de categorías
---------------------------------------

**Usuario:** Periodista

**Acceso:** Estructura>Categorías

En el listado de categorías se muestra una vista rápida de todas las categorías que hayan sido creadas, que consta del *Nombre* y el *Nombre único*.

Por defecto, el administrador muestra 20 galerías, número que puede ser modificado dirigiéndose al margen inferior izquierdo del administrador. Los resultados, además, se encuentran paginados.

Para buscar una categoría específica, puede acudir a la *Búsqueda simple* introduciendo palabras clave en el campo de texto que se encuentra en el margen superior derecho del administrador y presionar enter, o hacer clic en el botón que muestra una lupa. De esta manera, el sistema filtrará los resultados según la información solicitada. Para volver a ver el listado completo de galerías, haga clic en *Limpiar*. Además de este filtro, hay una opción que le permite mostrar la lista de categorías prohibidas.

Sobre cada una de las categorías se puede ejercer una serie de acciones: *Ver detalles, Modificar, Unificar, Agregar a la lista prohibida y Borrar*

Unificación de categorías
-------------------------

La unificación de distintas categorías bajo una misma se utiliza para evitar confusiones al momento de categorizar los contenidos. Las categorías unificadas dejarán de estar disponibles para su uso, aunque internamente se los utilizará para hacer más inteligentes las búsquedas que se realicen utilizando categorías. Por ejemplo, si en el listado encontramos categorías similares como *La Plata, La Pata y Laplata*, podemos unificarlas bajo la etiqueta correcta: *La Plata*. Para ello, haga clic en *Unificar* y busque las categorías incorrectas en el campo de texto *Buscar entre las categorías disponibles* si el sistema no las identificó automáticamente. Al finalizar, haga clic en *Unificar*.

Ediciones
=========

Las *ediciones* son elementos que organizan el contenido de los suplementos de manera temporal. Un diario, por ejemplo, puede tener un suplemento con ediciones diarias, para mostrar el contenido de su página principal, y suplementos con ediciones semanales, como los dedicados a juventud, cocina, cultura, etc. Por otro lado, una universidad podría crear ediciones anuales o semenstrales para agrupar contenido y luego ocultar aquel que ya no sea útil a sus alumnos y docentes.

Creación de una edición
-----------------------

**Usuario:** Administrador

**Acceso:** Estructura>Ediciones
  
Para crear una edición, haga clic en *Nueva edición* y a continuación complete:
- **Nombre:** por ejemplo *Diario - 20 de febrero de 2015*.
- **Fecha:** día al que corresponde.
- **Es visible:** tilde para hacer efectiva la publicación.
- **Suplemento:** seleccione de la lista el suplemento al cual corresponde la edición.
- **Atributos extra**

Al finalizar, haga clic en *Crear edición*. Posteriormente, deberá *Marcar como activa la edición*, para comenzar un nuevo ciclo de publicación.

Activación y visibilización de ediciones
----------------------------------------

Al marcar como activa una edición se iniciará un nuevo ciclo de publicación, por lo cual los artículos que se creen se asociarán a ella. De esta manera, los administradores del sitio podrán agrupar los contenidos de manera temporal, escogiendo si desean tener ediciones diarias, semanales, mensuales, bimestrales, anuales, etc.

Además es posible gestionar la visibilidad de las ediciones y, por ende, de los artículos que estén asociados a ellas. De esta manera se puede mantener un archivo de artículos visibles al público o invisibilizarlo, en caso de que la información ya no sea de utilidad.

Desde el *listado de ediciones* podrá ver los detalles de cada una, activarlas, modificarlas, borrarlas y ver los artículos que se encuentran asociados a cada edición.

Para invisibilizar una edición, haga clic en la acción *modificar* y destilde el campo *¿Es visible?*. Posteriormente, haga clic en *Actualizar edición*. 

Suplementos
===========

Los *suplementos* son subsitios que agrupan ediciones y secciones con sus respectivas portadas y artículos.

Creación de suplementos
-----------------------

**Usuario:** Administrador

**Acceso:** Estructura>Suplementos

Para crear un suplemento, haga clic en *Nuevo suplemento* y complete:
- **Nombre:** para identificar el elemento
- **Imagen de tapa:** imagen para el banner que encabezará el subsitio.

Secciones
=========




Aplicaciones al cliente
=======================

Componentes
===========

Servidores del frontend
=======================

Tareas programadas
==================

Configuraciones del sistema
===========================

Atributos extra personalizados
==============================

Usuarios
========

**Usuario:** Administrador

**Acceso:** Estructura>Usuarios

Los usuarios son las cuentas de las personas físicas que tienen acceso al administrador de contenidos. Para crear un nuevo usuario, debe hacer clic en *Nuevo usuario* y completar:

- **Nombre de usuario**
- **Mail**
- **Contraseña**
- **Roles:** seleccione uno de los roles, según sea periodista, diseñador, administrador, etc.
- **Espacios de trabajo:** se trata de dos campos que definen las entidades en las cuales un usuario tiene permisos para trabajar. Puede habilitar una o todas las aplicaciones cliente; y restringir la edición de determinadas secciones, o bien, habilitar la edición de todas ellas.

Al finalizar, haga clic en *Crear usuario*.

Desde el listado de usuarios podrá ver todos los usuarios, modificar sus permisos y cambiar o reestablecer sus contraseñas. 

Roles de usuarios
=================

**Usuario:** Administrador

**Acceso:** Estructura>Roles de usuarios

Los roles de usuarios son figuras que agrupan una serie de permisos y luego son adjudicadas a usuarios reales. Por defecto, Yavu reconoce 3 tipos de roles: periodistas, diseñadores y administradores. Cada uno de ellos tiene adjudicado una serie de permisos que le permiten realizar sus tareas dentro del administrador de contenidos, tal como se especifica al inicio de este manual.

Para crear un nuevo rol de usuario, haga clic en *Nuevo rol*, complete el nombre que lo identificará y tilde todos aquellos permisos que desea otorgarle. Al finalizar, haga clic en Crear rol de usuario.

Desde el listado de usuarios, también podrá modificar (agregar o quitar) los permisos de roles ya existentes.
