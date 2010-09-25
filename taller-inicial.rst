
.. sectnum::

==================================
Taller Inicial Open Journal System
==================================

.. contents:: Tabla de contenido

Introducción a OJS
==================

Sobre Open Journal System
-------------------------
Open Journal Systems (OJS) es una solución de código abierto para la gestión
y publicación de revistas académicas en línea. Se trata de un sistema de
gestión y publicación muy flexible y operado por los mismos editores que se
puede descargar de forma gratuita y se instala en un servidor web local. 

Ha sido diseñado para reducir el tiempo y la energía dedicada a las tareas
administrativas y de gestión asociadas con la edición de una revista, al 
tiempo que mejora la eficiencia de registros y de los procesos editoriales.

Su objetivo es mejorar la calidad académica y pública de la difusión de 
revistas a través de una serie de innovaciones, desde la elaboración de
políticas de revista más transparentes hasta mejorar la indexación de los
contenidos.

Características de OJS
----------------------
OJS incluye las siguientes características:

1. Es instalado y controlado en forma local
#. Los editores configuran los requerimientos, secciones, proceso de
   revisión, etc.
#. Envío de artículos, revisión por pares y gestión de todo el
   contenido on-line.
#. Módulo de suscripción con opciones de acceso libre/no libre
#. Indexación exahustiva de contenido 
#. Herramientas de lectura basadas en preferencias del editor
#. Posibilidad de enviar notificaciones y comentarios vía email para los
   lectores
#. Ayuda completa on-line sensible al conexto
#. Módulo de Pagos para aceptar remuneraciones, donaciones, etc.

Preliminares
============
Navegando por OJS
-----------------
Open Journal System ha sido diseñado como un sistema multi-revista el cual
permite mantener cualquier cantidad de revistas en una sola instalación.
Desde la página inicial los visitantes tienen acceso a páginas globales 
del sitio y pueden navegar por cualquiera de las páginas que pertenezcan
a una revista específica albergada en el sitio.

(imagen de sitio multi-revista)

El sistema también puede configurarse para redireccionar a los visitantes
a una revista específica, lo cual es útil si el sitio alberga una sola
revista.

(imagen de sitio una revista)

Elementos comunes en la interfaz
................................
Encontrará algunos elementos de interfaz comunes a nivel de Sitio y nivel de
Revista en cualquier instalación por defecto del sistema OJS.

  * Barra de Navegación Superior

    La barra de navegación que se encuentra más arriba en la página incluye
    enlaces al Inicio, Acerca de..., Login, Registro y Buscar. Si ya ha iniciado
    sesión los enlaces Login y Registro son reemplazados por el enlace Área Personal.

    (imagenes de barra de navegación, ambas)

    (explicar brevemente cada uno de los enlaces)

  * Traza de navegación

    Directamente bajo la barra de navegación superior encontrará una traza de
    la navegación actual con una serie de enlaces, uno por la página inicial
    del sitio, y uno por cada sub-página a la que haya navegado, terminando en
    la página en la que se encuentra (cuyo enlace se encuentra resaltado en
    negrita). Cada enlace lo llevará de vuelta a esa sub-página específica.

    (imagen breadcrumb)

  * Barra Lateral
    
    La barra lateral que encontramos a la derecha en realidad consiste en
    "bloques", los cuales se describen a continuación.

    (imagen barra lateral)

    * El bloque "Desarrollado por" en la parte superior provee un enlace al
      sitio web de Public Knowledge Project.
    * El bloque "Ayuda de la Revista" provee un enlace a la ayuda sensible al
      contexto del sistema. No importa donde se encuentre en el sistema, puede
      dar click en este enlace para acceder a ayuda específica de la sección
      actual.
    * El bloque de "Usuario" provee informaciones y opciones útiles específicas
      para el usuario. Si no ha iniciado sesión, pued ingresar su nombre de
      usuario y contraseña para ingresar al sistema. Si ya ha iniciado sesión,
      el bloque despliega su nombre de usuario y provee enlaces a las revistas
      en que se ha registrado, un enlace a su perfil y otro más para cerrar su
      sesión.
    * El bloque de "Idioma" sólo aparece si más de un idioma ha sido instalado
      en el sistema para la revista en particular en la que está navegando.
      Puede intercambiar de idioma eligiendo el idioma de su agrado de la lista
      de selección.
    * El bloque "Contenido de la revista" le permite buscar contenidos en la
      revista. Puede buscar en todos los campos o puede elegir uno en
      particular (por ejemplo el campo autor). Si está navegando a nivel de
      sitio puede buscar en todas las revistas que alberga el mismo, y si está
      navegando una revista específica sólo podrá buscar dentro de ella.
    * El bloque "Tamaño de fuente" le permite aumentar o disminuir el tamaño
      de la fuente en todo el sitio web.

Elementos específicos de la interfaz de revistas
................................................
Encontrará algunos elementos de interfaz que sólo se ven cuando se navega
a nivel revista.

  * Barra de Navegación Superior Específica de Revista
   
    Al navegar a nivel de revista, la barra de navegación que se encuentra
    más arriba incluye dos enlaces extra por defecto:

    (imagen top navigation bar journal level)

    * El enlace "Actual" lo lleva a la tabla de contenidos de la edición
      actual. Si la revista no tiene actualmente algún material publicado,
      verá una página que le indicará esto.
    * El enlace "Archivos" lo lleva a un listado de todas las ediciones
      publicadas, incluída la publicación más reciente. También podrá
      visitar la tabla de contenido de cada edición mediante un click
      en el título de la misma.

  * Elmentos Específicos de Revista en la Barra Lateral
    
    Notará algunos bloques nuevos al navegar a nivel revista:

    (imagen journal's sidebar)

    * El bloque de "Notificaciones" que le permite manipular y ver las 
      notificaciones específicas de la revista.
    * El bloque de "Suscripción", que sólo aparecerá en las revistas que
      permitan suscripciones, y mostrará información relativa a la cuenta
      del usuario.
    * El bloque "Navegar" permite examinar los contenidos de la revista
      por listas. Puede navegar por Edición, por Autor y por Título.
      Adicionalmente, si se hace click en el enlace  "Otras revistas"
      será dirigido a la lista de revistas a nivel de sitio.
    * El bloque de "Información" despliega los enlaces "Para lectoras/es",
      "Para Autoras/es" y "Para bibliotecarias/os". El contenido de estas
      páginas se agrega al configurar una revista. Si el contenido es
      eliminado, estos enlaces desaparecerán automáticamente.



Usuarios y Roles
----------------

Acerca de los Roles de Usuario
..............................
OJS utiliza un sistema de roles global para dividir el trabajo entre los
usuarios, asignar los flujos de trabajo y limitar el acceso a diferentes partes
del sistema. Como una instalación de OJS puede albergar múltiples revistas, 
los usuarios pueden estar inscritos en diferentes roles en más de una revista.

Cuando un usuario inicia sesión en el sistema, será dirigido a su página de
Área Personal. Desde allí podrá ver una lista de los roles en los que está
inscrito para cada revista en el sistema (además de ver enlaces específicos de
usuario para editar su perfil, cambiar su contraseña, etc.). En el ejemplo de 
abajo, el usuario está inscrito como Adminstrador del Sitio, tiene roles
de Gestión de Revista, Gestión de Subscripciones y Editor en la revista
*Canadian Journal of Scholarlly Publishing*; además tiene roles de Gestión de 
Revista, Editor y Autor para la revista *Demo Journal*. Un usuario podría ser un
Editor en una revista (con todos los permisos que corresponda), pero puede que
sólo tenga rol de Autor en otra revista (por lo tanto estará limitado a
realizar tareas de Autor para esa revista).

(imagen user home)

Roles disponibles en OJS
........................
* Administrador del Sitio

  El Administrador del Sitio es el responsable general de la instalación de
  OJS, debe asegurarse de que las configuraciones del servidor son correctas,
  agrega archivos de idiomas y crea las revistas nuevas en la instalación. La
  cuenta del Administrador del sitio es creada durante el proceso de
  instalación. A diferencia de los demás roles en OJS, puede haber sólo un
  Administrador de Sitio.

  Para más detalles puede ver la sección Administrador del Sitio.

* Gestión de Revista

  El rol de Gestión de Revista es responsable de configurar el sitio web de la
  revista, configurar las opciones del sistema y gestionar las cuentas de
  usuarios. Esto no requiere ninguna habilidad técnica en especial, pero
  implica llenar formularios web y subir archivos al servidor. El o La Gestor/a
  de la Revista también inscribe a las/los Editoras/es, Editoras/es de Sección,
  Correctoras/es, Editoras/es de Maquetación, Correctoras/es de Pruebas, 
  Autoras/es y Revisoras/es. Alternativamente, si los nombres respectivas
  direcciones de correo electrónico de usuarios potenciales ya existen en otra
  base de datos (por ejemplo, una planilla de cálculo electrónica), pueden ser
  importados en el sistema. El o La Gestor/a de Revista también tiene acceso
  a otras características de la revista, y puede crear nuevas Secciones para
  la revista, configurar Formularios de Revisión, editar correos
  electrónicos por defecto, gestionar Herramientas de Lectura, ver
  Estadísticas y Reportes y más.

  Para más detalles puede ver la sección Gestor/a de Revista

* Lectoras/es

  El rol de Lectoras/es es el rol más simple en OJS y el que menos capacidades
  tiene en el sistema. Las/os Lectoras/es incluyen a los subscriptores
  tanto para revistas basadas en subscripciones y lectoras/es que se registran
  a revistas de acceso libre (ya sea de acceso libre inmediato o luego de un
  periodo de tiempo). Las/os Lectoras/es registrados reciben notificaciones vía
  correo electrónico con la publicación de cada edición, la cual incluye la 
  Tabla de Contenidos para esa edición particular.

  Para más detalles puede ver la sección `Lectoras/es`_

* Autoras/es

  Las/os Autoras/es son capaces de enviar manuscritos o artículos a la revista 
  directamente a través de la página web de la revista. Se le solicita que 
  suba un archivo de envío y que provea metadatos o información para 
  indexación. (Los metadatos mejoran la capacidad de búsqueda on line de la
  revista). El o La Autor/a puede subir archivos suplementarios, en forma de
  conjunto de datos, instrumentos de investigación, o fuentes textuales que 
  enriquezcan el artículo, de manera a contribuír a una investigación 
  académica más abierta y robusta. Al iniciar sesión en la página web de la 
  revista, el o la Autor/a es capáz de hacer el seguimiento de su envío a 
  través del proceso de revisión y editorial - además de participar como 
  corrector y corrector de prueba en los envíos aceptados para publicación.

  Para más detalles puede ver la sección `Autoras/es`_.

* Editoras/es

  Las/os Editoras/es vigila el proceso completo de revisión, edición y
  publicación. Trabajando en conjunto con el o la Administrador/a de Revista,
  por lo general establece las políticas y procedimientos para la revista. En
  el proceso de edición, las/os editoras/es asignan los envíos a las/os
  Editoras/es de Sección para que pasen por la Revisión de Envíos y la Edición
  de Envíos. Las/os Editoras/es prestan atención al progreso del envío y asiste
  con cualquier dificultad que surja. Una vez que la revisión se completó, el o
  la editor/a por lo general sigue el envío a través del proceso de edición
  (incluída la corrección, la maquetación y la corrección de pruebas) 
  aunque en algunas revistas ésta sigue siendo la responsabilidad de
  las/os editoras/es de sección a cargo del proceso de revisión del envío.
  El o La Editor/a también crea las ediciones de una revista, agenda los envíos
  para su publicación, organiza la Tabla de Contenidos y publica la edición
  como parte del Proceso de Publicación. El o La Editor/a puede restaurar al
  estado activo un envío archivado en las listas En Revisión o En Edición.

  Para más detalles puede ver la sección `Editoras/es`_.

* Editoras/es de Sección

  Las/os Editoras/es de Sección gestionan la revisión y edición de los envíos
  que les fueron asignados. En algunos casos el o la Editor/a de Sección que 
  fue asignado a seguir envíos a través del Proceso de Revisión también será
  responsable de seguir aquellos envíos que fueron aceptados a través del 
  Proceso de Edición (esto es, a través del la corrección, la maquetación y
  corrección de pruebas). A menudo, sin embargo, las/os Editoras/es de Sección
  sólo trabajan con el Proceso de Revisión, y un/a Editor/a, actuando con el
  rol de Editor/a de Sección, sigue los envíos a través del Proceso de Edición.
  La revista tendrá una política que definirá cómo estarán divididas estas
  tareas.

  Para más detalles puede ver la sección `Editoras/es de Sección`_.

* Revisoras/es

  Un/a Revisor/a es seleccionado/a por un/a Editor/a de Sección para revisar
  un envío. A las/os Revisoras/es se les solicita que envíen sus revisiones al
  sitio web de la revista (aunque algunas revistas optan por una política de
  revisión vía correo electrónico) y tienen permitido subir adjuntos para el
  uso de las/os Editoras/es y Autoras/es. Las/os Revisoras/es tienen la
  posibilidad de ser valorados por las/os Editoras/es de Sección, dependiendo
  de las políticas de la revista.

  Para más detalles puede ver la sección `Revisoras/es`_.

* Adminsitradoras/es de Subscripción

  El o La Adminstrador/a de Subscripción gestiona las subscripciones y los
  tipos de subscripción de una revista, y también puede configurar cuándo y
  cómo los pagos son manejados dentro del sistema.

  Para más detalles puede ver las secciones correspondientes a Subscripciones
  y Pagos.

* Correctoras/es

  Las/os Correctores/as editan los envíos para mejorar la gramática y la
  claridad, trabaja con las/os Autoras/es para asegurarse de que todo está
  correcto, asegura la adherencia estricta a los estilos bibliográficos y 
  textuales de la revista, y produce una copia en limpio y editada para
  el o la Editor/a de Maquetación para transformarlo en la galera que será
  publicada en el formato de la revista. Algunas revistas tienen a Editores/as
  o Editoras/es de Sección que se encargan de este rol.

  Para más detalles puede ver la sección `Correctoras/es`_.

* Editoras/es de Maquetación

  El o la Editor/a de Maquetación transforma las versiones corregidas de un
  envío en galeras en formatos HTML, PDF, PS, etc. - tipos de archivos que la
  revista eligió para usar en la publicación electrónica. Este sistema no 
  provee un módulo para convertir los documentos recibidos formatos de galera,
  por lo que el o la Editor/a de Maquetación debería tener acceso y ser capáz
  de utilizar aplicaciones externas para crear las galeras en estos formatos 
  y presentar los artículos en pantalla en una disposición correctamente 
  formateada y legible, a la manera de una revista académica y prestando 
  atención a este nuevo medio de publicación (para darse una idea puede 
  consultar con la disposición que utilizan otras revistas en línea, por
  ejemplo `Highwire Press <http://highwire.stanford.edu/>`_)
  
  Para más detalles puede ver la sección `Editoras/es de Maquetación`_.

* Correctoras/es de Prueba

  Las/os Correctoras/es de Prueba leen cuidadosamente sobre la galera en los
  formatos en los que la revista publica (así también lo hace el o la
  autor/a). El o La Corrector/a de Prueba (y el o la Autor/a) anota cualquier
  error tipográfico y de formato para que el o la Editor/a de Maquetación lo
  corrija. En el caso de algunas revistas un/a Editor/a o Editor/a de Sección
  también será un Corrector/a de Prueba.

  Para más detalles puede ver la sección `Correctoras/es de Pruebas`_.

Registrarse en una Revista
..........................

Los visitantes de la revista que no estén registrados normalmente pueden
registrarse a sí mismos como Lectores/as, Autoras/es y/o Revisoras/es. Las/os 
Administradoras/es de Revista pueden remover esta opción de registro (en tal
caso, aparecerá una notificación estableciendo que el registro se encuentra 
cerrado), pero siempre pueden registrar usuarios desde la página principal de
Gestión de la Revista en cualquier momento para cualquier rol.

Para registrarse en una revista, haga click en el enlace **Registro** en la
barra superior de navegación, si se le solicita, elija la revista a la cual 
quiere registrarse, y proceda a llenar el formulario en pantalla. No será capáz
de registrarse con un rol de Editorial (Editoras/es, Editoras/es de Sección,
Correctoras/es, Editoras/es de Maquetación, Correctoras/es de Prueba, 
Administradoras/es de Subscripción o Administradas/es de Revista). Si necesita
ser registrado con este nivel de roles, solicítelo al Editor/a de la Revista o
al Administrador/a del Sitio.

Todos los campos con un asterisco al lado (Usuario, Contraseña, Repetir
Contraseña, Nombre, Apellido, Correo Electrónico) son obligatorios. Si la 
revista es multilingüe, necesitará elegir su idioma preferido.

(imagen filling out registration form)

Su nombre de usuario y correo electrónico deben ser únicos, además, a pesar de
poder cambiar luego su dirección de correo electrónico, no será posible cambiar
su nombre de usuario.

Puede registrarse como Lector/a, Autor/a y/o Revisor/a, dependiendo de cómo ha
sido configurada la revista. Todo lo que debe hacer es marcar la casilla de
selección de los roles que estén habilitados. Si se registra como Revisor/a
también podrá proveer los intereses que tiene en cuanto a revisiones.

(imagen selecting roles)

En algunos casos, la revista en la que esté intentando registrarse tal vez no
permita realizar registros, si ese fuera el caso verá una nota indicando esto.

Si quiere registrarse con otro rol en la misma revista (por ejemplo, si ya es
un/a Lector/a, pero también quiere ser un/a Autor/a) puede iniciar sesión, ir
a **Editar Mi Perfil** (en Mi Cuenta en su página de Área Personal) y elegir 
las casillas de selección de los roles, hacia la parte inferior de la página.

Si quiere revocar su registro completamente de la revista, todo lo que debe 
hacer es visitar su perfil y desmarcar todas las casillas de selección de los
roles. Si está registrado con un rol de nivel editorial, tendrá que solicitarlo
al Administrador/a de la Revista.

Ver y Cambiar su Perfil
.......................

Para ver y editar su perfil, inicie sesión y haga click en el enlace **Editar Mi
Perfil** de la página de Área Personal. Alternativamente, una vez que haya
iniciado sessión, también puede hacer click en el enlace **Mi Perfil** del
bloque de Navegación de Usuario en la barra lateral si estuviera disponible. En
esta página puede actualizar su dirección de correo electrónico, su información
personal o cambiar su contraseña.

Cambiar su Contraseña
........................

El proceso de cambio de contraseña es simple si la recuerda y sólo desea
cambiarla por otra nueva: inicie sesión, y desde su página de Área Personal
haga click en el enlace **Cambiar Contraseña**. Necesitará ingresar su
contraseña actual y luego la nueva contraseña dos veces.

Si ha olvidado su contraseña, el cambio también es un proceso simple, pero
lleva unos cuantos pasos más:

1. Haga click en el enlace **Login** en la barra de navegación superior.
#. Haga click en el enlace **Olvidó su contraseña?**.
#. Ingrese su dirección de correo en el cuadro de texto mostrado y haga click
   en el enlace **Cambiar Contraseña**. Esto hará que se envíe un correo 
   electrónico de confirmación a su dirección de correo electrónico (si no ve
   un correo electrónico en su Bandeja de Entrada, revise su carpeta de correo
   basura).
#. El correo electrónico incluirá un enlace para cambiar su contraseña: haga
   click en él y debería retornar al sitio web de la revista.
#. Al retornar al sitio web de la revista, debería ser notificado que otro
   correo electrónico que contiene una nueva contraseña ha sido enviado a su
   dirección de correo electrónico. Revise este segundo correo y utilice las
   credenciales para iniciar sesión en el sitio.
#. Luego de un inicio de sesión exitoso, se le solicitará inmediatamente que
   cambie la contraseña. Ingrese primero la contraseña recibida por correo (que
   en este momento es su contraseña actual), y luego ingrese una nueva 
   contraseña secreta dos veces (Nueva Contraseña, Repita Nueva Contraseña).

(imagen cambiar contraseña)

Configuraciones y Gestión de Revista
====================================
Resumen
-------

Como parte de la `Instalación`_, habrá creado una cuenta de Administrador del
Sitio. Cuando inicia sesión en OJS con esa cuenta, tendrá acceso a las
configuraciones de Administración del Sitio en su página de Área Personal.
Podrá crear nuevas revistas, gestionar el soporte de idiomas en el sistema y
llevar a cabo otras tareas administrativas.

Para acceder a las páginas de Administración del Sitio, inicie sesión como
Administrador del Sitio y desde su página de Área Personal haga click en el
enlace **Administrador/a**.

.. figure:: images/sec03-area-personal-admin.png
   :align: center

   Área Personal del/la Administrador/a
..

Gestión de Sitio
----------------
Configuraciones del Sitio
.........................
Revistas Albergadas
...................
Configuraciones de Idiomas
..........................
Funciones Administrativas
.........................
Gestión de Revista
------------------
El Proceso de Configuración de 5 Pasos
......................................
Anuncios
........
El Explorador de Documentos
...........................
Secciones de una Revista
........................
Formularios de Revisión
.......................
Idiomas
.......
Equipo de Trabajo
.................
Plantillas de correo electrónico
................................
Herramientas de Lectura
.......................
Reportes y Estadísticas
.......................
Suscripciones
.............

Gestión de Usuarios
-------------------
Enviar correo electrónico a usuarios
....................................
Inscribir Usuarios Existentes
.............................
Mostrar Usuarios sin Rol
........................
Crear Usuarios
..............
Unir Usuarios
.............

Proceso de Edición y Publicación
================================
Autoras/es
----------
Editoras/es
-----------
Editoras/es de Sección
----------------------
Revisoras/es
------------
Correctoras/es
--------------
Editoras/es de Maquetación
--------------------------
Correctoras/es de Pruebas
-------------------------
Las/os Correctoras/es de Pruebas recibirán un correo electrónico del Editor/a
de Código solicitando que el o la Corrector/a de Pruebas complete una o varias
rondas de corrección de prueba. Es ese momento es cuando un/a corrector/a de
prueba decide aceptar o rechazar la responsabilidad. Si acepta la tarea, el o
la corrector/a de prueba puede iniciar sesión e iniciar el proceso de
corrección de prueba desde su **Área Personal**.




Lectoras/es
-----------
Las/los Lectoras/es son aquelos subscriptos a una revista basada en
subscripciones, junto con aquellos lectores que eligieron registrarse en
revistas de acceso libre (ya sea de acceso libre inmediato o luego de un
perido de tiempo luego de la publicación inicial del contenido de la revista).

Las/los Lectoras/os registrados reciben una notificación de la publicación de
cada edición, la cual incluye la Tabla de Contenidos de la Revista.

* Acceder al contenido

  Para revistas de acceso libre que utilizan OJS, el acceder al contenido es
  tan simple como hacer click sobre el enlace **Actual** para ver la última
  edición, o también puede acceder al enclace **Archivo** para ver ediciones
  previas.

  (imagen current issue)

* Suscribirse
  
  Si se requiere una subscripción para acceder al contenido de la revista,
  primero necesitará registarse como Lector/a en la revista OJS. Para más
  detalles puede ver la sección Pagos y Subscripciones.

* Inscripción a Notificaciones
  Si le gustaría recibir un correo electrónico automático que lo alerte sobre
  nuevo contenido de una revista OJS, a menudo puede registarse en una cuenta
  con rol de Lector/a y marcar la casilla de selección:

  (imagen reader notification)

* Herramientas de Lectura
  
  Las Herramientas de Lectura están hechas para asistir tanto a lectoras/es
  expertas/os o novatas/os de la revista. Esta asistencia se utiliza de manera
  a construir un contexto para interpretar, evaluar y utilizar la investigación
  que están leyendo.

  Las Herramientas de Lectura han sido desarrolladas para un amplio rango de
  disciplinas académicas, de las cuales el Administrador de la Revista puede
  seleccionar, así como actualizarlas y editarlas, de manera a dar soporte al
  entorno de lectura para la revista. Las Herramientas de Lectura también
  permiten a las/os lectoras/es a unirse a foros de discusión relevantes, así
  como también permiten contactar con el autor o compartir el artículo con 
  otro/a lector/a, entre muchas cosas más.

  (imagen reading tool)
  
Administración del Sistema
==========================
Las siguientes instrucciones demostrarán cómo instalar OJS, cómo hacer
copias de respaldo del sistema y cómo restaurarlas. Los requerimientos del
sistema que se listan a continuación deben cumplirse antes de iniciar el
proceso de instalación.

Instalación
-----------
Requisitos mínimos y deseables
..............................
* Requerimientos mínimos para el sistema:

  * PHP >= 4.2.x (incluyendo PHP 5.x); Microsoft IIS requiere PHP 5.
  * MySQL >= 3.23.23 (incluyendo MySQL 4.x y 5.x) o PostgreSQL >= 7.1
    (incluyendo PostgreSQL 8.x)
  * Apache >= 1.3.2x o >= 2.0.4x o Microsoft IIS 6
  * Sistema Operativo: Cualquier sistema operativo que soporte el software
    mencionado arriba, incluyendo Linux, BSD, Solaris, Mac OS X, Windows.

* Configuración recomendada del servidor

  * PHP 5.x con soporte para iconv, mbstring, libgd y libfreetype
  * MySQL 5.x con conexión y almacenamiento de datos utilizando UTF8
  * Sistema Operativo del tipo \*NIX (Linux, BSD, Mac OS X)
  * Servidor Web Apache configurado con PHP via FastCGI 

También se recomienda tener acceso `SSH <http://en.wikipedia.org/wiki/Secure_Shell>`_ al servidor, pues
verá que esto será necesario para realizar tareas de nivel avanzado,
además de ser útil en general.

Componentes de una Instalación
..............................
* Ruta de instalación que contiene el OJS (típicamente 10-20Mb)
* El tamaño de la ruta de los archivos (configurado en ``config.inc.php`` 
  utilizando la directiva ``files_dir``, varía dependiendo de los documentos
  que están siendo gestionados (por ejemplo: el formato de los archivos,
  la complejidad del diseño, cantidad de rondas de revisión, etc.)
* El tamaño de la base de datos MySQL (configurado en ``config.inc.php`` en
  la sección ``[database]``, varía de unas decenas de megabytes para
  pequeñas revistas a cientos de megabytes para grandes revistas o 
  colecciones.
* OJS contiene librerías open source de terceros, entre ellas:

  * `ADODB <http://adodb.sourceforge.net/>`_, librería de abstracción de datos para PHP
  * `Smarty <http://smarty.net/>`_, para plantillas e interfaz general
  * `TinyMCE <http://www.moxiecode.com/>`_, editor sencillo incrustado

El Proceso de Instalación
.........................
Existe varios pasos a llevar a cabo para una instalación exitosa de OJS:
descargar y descomprimir los archivos de OJS en un directorio accesible vía
web en su servidor, crear un directorio separado ``files/`` que no sea 
accesible vía web y lo más probable creación de la base de datos con algún
usuario para acceder a la misma.

* Descargar y descomprimir el paquete de instalación del sitio oficial

  Puede elegir la versión que más le conviene según sus necesidades
  (versiones estables o versiones de prueba) desde aquí http://pkp.sfu.ca/ojs_download.
  El proceso de instalación es el mismo para cualquier versión.

  Descomprima el `archivo tar <http://en.wikipedia.org/wiki/Tar_%28file_format%29>`_ que
  descargó y mueva todo el contenido que descomprimió a un directorio que
  sea accesible vía web en el servidor web que quiera instalar OJS. Un ejemplo
  común es el directorio ``/var/www/html/``, el cual utilizaremos para este
  ejemplo.

  Si no pudo descargar directamente el *archivo tar* en su servidor web, puede 
  descomprimirlo en su computadora personal y luego transferir el contenido
  vía FTP.

  Digamos que el contenido se descomprime en un directorio llamado ``ojs``,
  entonces puede mover el mismo dentro de  ``/var/www/html/``, en este punto, ya
  podrá acceder al contenido del directorio vía web en su servidor (es decir
  que con el navegador puede ir a http://ejemplo.com/ojs/ y podrá ver la
  pantalla de instalación.

.. figure:: images/instalacion-01.png
   :align: center

   Pantalla de Instalación de OJS

* Preparar el entorno para la instalación

  Necesitará crear un directorio ``files/`` en donde OJS almacenarán los
  archivos enviados. Este directorio no debería ser accesible vía web ya que
  sería posible acceder en línea a archivos privados. Para evitar esto, debe
  crear el directorio fuera de ``/var/www/``.

  Luego necesitará otorgar los permisos necesarios al directorio ``files/``, a
  los subdirectorios ``public/`` y ``cache/`` de la ruta de instalación de OJS
  y al archivo de configuración ``config.inc.php`` para que el servidor web 
  pueda administrar/guardar correctamente los datos que vaya recibiendo.

  En la página de instalación recibirá una advertencia si los permisos no están
  debidamente configurados.

.. figure:: images/instalacion-permisos-pre-instalacion.png
   :align: center

   Instalación de OJS: Permisos insuficientes

* Configurar la base de datos

  Necesitará crear una base de datos para que el sistema la utilice, además de
  asegurarse de que exista un usuario de la base que tenga los permisos
  necesarios para operarla debidamente.

  Por ejemplo, para MySQL, se puede crear una base de datos y un usuario con
  phpMyAdmin o vía línea de comandos, como se muestra a continuación::


   $ mysql -u root -p
   Enter password: 
   
   Welcome to the MySQL monitor.  Commands end with ; or \g.
   Your MySQL connection id is 95
   Server version: 5.1.38 MySQL Community Server (GPL)
   
   Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.
   
   mysql> CREATE DATABASE ojs DEFAULT CHARACTER SET utf8;
   Query OK, 1 row affected (0.13 sec)
   
   mysql> GRANT ALL ON ojs.* TO pkpuser@localhost IDENTIFIED BY 'password';
   Query OK, 0 rows affected (0.15 sec)
   
   mysql> exit;
   Bye

  En este ejemplo, la base de datos se llama ``ojs``, el usuario de la base se
  llama ``pkpuser`` y la contraseña es ``password``. Se necesitarán estas tres
  piezas de información mas adelante.

* Completar la instalación vía web  

  Con el navegador de internet, diríjase al directorio de instalación de OJS en
  su servidor. Verá una página de instalación: llene todos los campos del 
  formulario (incluyendo la información de conexión a la base de datos que 
  estableció previamente, y en Configuraciones de Archivo llene con la ruta al
  directorio ``files`` que creó en pasos anteriores) y haga click sobre el 
  botón **Instalar** en la parte de abajo de la página.

  Debe configurar la configuración de localización: aparte de la localización
  del idioma, deberá elegir el juego de caracteres que se utilizará. Si fuera
  posible, debe elegir "Unicode (UTF-8)", lo cual asegurará un mejor soporte
  multilingüe en el sitio.

.. figure:: images/instalacion-configuracion-locales.png
   :align: center

   Instalación de OJS: Configuración de locales
..

  Luego debe especificar la ubicación del directorio ``files/`` que creó 
  previamente:

.. figure:: images/instalacion-configuracion-files.png
   :align: center

   Instalación de OJS: Configuración de ficheros
..

  Seguidamente, elija las configuraciones de seguridad. Esta configuración
  especifica cómo son almacenadas las contraseñas del sistema. SHA1 es más
  segura que MD5, por lo tanto, si su versión de PHP es 4.3.0 o superior, elija
  la opción SHA1.

.. figure:: images/instalacion-configuracion-seguridad.png
   :align: center

   Instalación de OJS: Configuración de seguridad
..

  Debe especificar un nombre de usuario, contraseña y correo electrónico para 
  la Cuenta del Administrador. Luego de una instalación exitosa, utilizará esta
  cuenta para iniciar sesión y configurar inicialmente nuevas revistas, pero
  normalmente esta cuenta no será utilizada para el trabajo diario con una 
  revista.  

.. figure:: images/instalacion-configuracion-cuenta-admin.png
   :align: center

   Instalación de OJS: Configuración de administrador/a
..

  El paso siguiente es referente a la configuración de la base de datos. Debe
  completar la configuración apropiadamente: elija el controlador correcto
  que utilizará con el sistema, especifique correctamente el host (normalmente
  será ``localhost``, pero esto depende de la configuración del servidor),
  complete el nombre de usuario y la contraseña para la base de datos y el
  nombre de la base de datos a la que el sistema se conectará. Si todavía no ha
  creado la base de datos, entonces asegúrese de que la casilla de selección
  "Crear nueva base de datos" se encuentre seleccionada; aunque esta opción no
  funcionará si el usuario de la base de datos no tiene los permisos necesarios
  para crear bases de datos. Si este fuese el caso, deberá crear la base de
  datos de antemano.

.. figure:: images/instalacion-configuracion-bd.png
   :align: center

   Instalación de OJS: Configuración de la base de datos
..

  Por último, elija un identificador apropiado para el repositorio OAI (el
  nombre por defecto podría ser adecuado) y haga click en **Instalar Open
  Journal Systems** si el usuario de la base de datos tiene permisos de
  escritura en la base de datos, o bien haga click en **Instalación Manual** si
  necesita cargar la base de datos manualmente.

.. figure:: images/instalacion-configuracion-adicional.png
   :align: center

   Instalación de OJS: Configuración adicional
..

  Si todo va bien, entonces verá una pantalla de instalación exitosa.

.. figure:: images/instalacion-exitosa.png
   :align: center

   Instalación de OJS: Instalación exitosa
..

  Si el servidor no pudo escribir en el archivo ``config.inc.php``, se le
  solicitará que copie el contenido de un cuadro de texto y lo pegue en su
  archivo de configuración ``config.inc.php`` por defecto del servidor.

.. figure:: images/instalacion-copiar-configuracion-manualmente.png
   :align: center

   Instalación de OJS: Copiar archivo de configuración config.ini.php
..

  Si elijió realizar una instalación manual, se le solicitará que copie una
  serie de sentencias SQL que deberán ser ejecutadas en su servidor de base de
  datos.

.. figure:: images/instalacion-bd-manual.png
   :align: center

   Instalación de OJS: Instalación manual
..

Copias de Respaldo y Restauración
---------------------------------
Una copia de respaldo completa de una instalación OJS debería incluír tres
componentes: los archivos de sistema de OJS, el directorio ``files/`` que creó
durante la instalación y la base de datos. Hay muchas maneras de hacer copias
de respaldo para estos tres componentes. Dependiendo de las herramientas a su
disposición podría ser capaz de realizar las copias de respaldo completamente
vía web mediante alguna interfaz administrativa como CPanel, o tal vez tenga
que realizar las copias de respaldo vía linea de comandos. La siguiente
sección demuestra una de las maneras de realizar la copia de respaldo vía línea
de comandos.

Realizar Copias de Respaldo del Sistema
.......................................

* Copia de Respaldo de los archivos de sistema de OJS

  Para encontrar los archivos del sistema debe buscar su archivo de 
  configuración ``config.inc.php``, éste estará en el directorio donde 
  originalmente se instaló OJS. Copie todos los archivos de este directorio y
  todos sus sub-directorios. Suponiendo que OJS está isntalado en 
  ``/var/www/html/ojs`` y la copia de respaldo debe ser almacenada en
  ``/root``, el siguente ejemplo comprimirá los archivos de sistema de OJS en
  un archivo llamado ``ojs-install.tar.gz`` y los almacenará en ``/root``::

    $ cd /var/www/html/ojs
    $ tar czf /root/ojs-install.tar.gz *
  
* Copia de Respaldo de la base de datos

  Aquí necesita saber el nombre de la base de datos, el usuario y la contraseña
  de la misma. Esta información la puede obtener fijándose en la sección 
  ``[database]`` en su archivo de configuración ``config.inc.php``::

    [database]

    driver = mysql
    host = localhost
    username = pkpuser
    password = password
    name = ojs

  Puede realizar la copia de respaldo utilizando la herramienta mysqldump. Por
  ejemplo, si la copia de respaldo debe almacenarse en ``/root``::

    $ mysqldump -u pkpuser -p password | gzip -9 > /root/ojs-database.sql.gz

  Como es de suponerse, phpMyAdmin u otras herramientas podrían ser utilizadas
  para realizar la copia de respaldo de la base de datos.

* Copia de Respaldo del directorio ``files/``

  Para saber dónde está el directorio ``files/``, fíjese en el parámetro 
  ``files_dir`` en el archivo de configuración ``config.inc.php``::

    [files]

    ; Complete path to directory to store uploaded files
    ; (This directory should not be directly web-accessible)
    ; Windows users should use forward slashes
    files_dir = /usr/local/ojs-files

  Copie este directorio y todo su contenido, por ejemplo, si la copia de
  respaldo se almacenara en ``/root``::

    $ cd /usr/local/ojs-files/
    $ tar czf /root/ojs-files.tar.gz

  Cuando estos pasos se hayan completado, habrá creado tres archivos de copia
  de respaldo que se encuentran en ``/root``. Todos ellos son necesarios para
  restaurar una copia de la instalación de OJS.

Restaurar Datos de una Copia de Respaldo
........................................
Esta sección muestra un breve resumen de cómo un sistema OJS puede ser
restaurado de copias de respaldo realizadas en la sección anterior. Esta es 
sólo una manera de restaurar el sistema, existen muchas otras maneras 
dependiendo de las herramientas que tenga a su disposición como así también 
depende de la manera en que haya realizado las copias de respaldo.

* Restaurar los archivos

  Para restaurar de una copia de respaldo, descomprima en el lugar apropiado 
  los archivos correspondientes al directorio ``files/`` y al directorio que
  contiene los archivos del sistema de la siguiente manera::

    $ cd /var/www/html
    $ mkdir ojs
    $ cd ojs
    $ tar xzf /root/ojs-install.tar.gz
    $ cd /usr/local
    $ mkdir ojs-files
    $ cd ojs-files
    $ tar xzf /root/ojs-files.tar.gz

* Restaurar la base de datos

  Para crear de vuelta la base de datos MySQL (eliminándola primero si fuera
  necesario)::

    $ mysql -u root -p
    Enter password:

    Welcome to the MySQL monitor.  Commands end with ; or \g.
    Your MySQL connection id is 103
    Server version: 5.1.38 MySQL Community Server (GPL)

    Type 'help;' or '\h' for help. Type '\c' to clear the current input statement.

    mysql> DROP DATABASE ojs;
    Query OK, 0 rows affected (0.23 sec)

    mysql> CREATE DATABASE ojs DEFAULT CHARACTER SET utf8;
    Query OK, 1 row affected (0.00 sec)

    mysql> GRANT ALL ON ojs.* TO pkpuser@localhost IDENTIFIED BY 'password';
    Query OK, 0 rows affected (0.01 sec)

    mysql> 
  
  Y luego cargue en la nueva base de datos el contenido de la copia de
  respaldo::

    $ zcat /root/ojs-database.sql.gz | mysql -u pkpuser -p password


