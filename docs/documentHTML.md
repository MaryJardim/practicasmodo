HTML https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/HTML_basics
El Lenguaje de Marcado de Hipertexto (HTML) es el código que se utiliza para estructurar y desplegar una página web y sus contenidos. Por ejemplo, sus contenidos podrían ser párrafos, una lista con viñetas, o imágenes y tablas de datos. Como lo sugiere el título, este artículo te dará una comprensión básica de HTML y cúal es su función.


 Las partes principales del elemento son:

La etiqueta de apertura: consiste en el nombre del elemento (en este caso, p), encerrado por paréntesis angulares (< >) de apertura y cierre. Establece dónde comienza o empieza a tener efecto el elemento —en este caso, dónde es el comienzo del párrafo—.
La etiqueta de cierre: es igual que la etiqueta de apertura, excepto que incluye una barra de cierre (/) antes del nombre de la etiqueta. Establece dónde termina el elemento —en este caso dónde termina el párrafo—.
El contenido: este es el contenido del elemento, que en este caso es sólo texto.
El elemento: la etiqueta de apertura, más la etiqueta de cierre, más el contenido equivale al elemento.


Los elementos suelen venir acompañados de un atributo que permita identifificar(ya que contiene) información adicional acerca del elemento, la cual no quieres que aparezca en el contenido real del elemento. 
Un atributo debe tener siempre:

Un espacio entre este y el nombre del elemento (o del atributo previo, si el elemento ya posee uno o más atributos).
El nombre del atributo, seguido por un signo de igual (=).
Comillas de apertura y de cierre, encerrando el valor del atributo.



Elementos vacíos
Algunos elementos no poseen contenido, y son llamados elementos vacíos. Toma, por ejemplo, el elemento <img> de nuestro HTML:
Ejemplo:

<img src="images/firefox-icon.png" alt="Mi imagen de prueba" /> 

Posee dos atributos, pero no hay etiqueta de cierre </img> ni contenido encerrado. Esto es porque un elemento de imagen no encierra contenido al cual afectar. Su propósito es desplegar una imagen en la página HTML, en el lugar en que aparece.



Etiquetas de estructura que ayudan en la semantica del archivo.