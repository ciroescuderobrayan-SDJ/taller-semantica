Taller de Investigación: Fundamentos de HTML
Nombre del Estudiante: [Brayan Esneider Ciro Escudero]

1. Anatomía de una Etiqueta HTML
Etiqueta de Apertura y Cierre
¿Qué es una etiqueta de apertura?

Respuesta:
Etiqueta de apertura → indica dónde empieza el elemento.

¿Qué es una etiqueta de cierre?

Respuesta:
Etiqueta de cierre → indica dónde termina el elemento.

Atributos
¿Qué es un atributo y para qué sirve? Da un ejemplo.

Respuesta: 
Un atributo es información adicional que se le agrega a una etiqueta de apertura en HTML para:
* Modificar su comportamiento.
* Darle características extra.
* Hacerla más específica.

<a href="https://www.apple.com">Ir al sitio de Apple</a>

a> y explicando qué hace el atributo href.

Respuesta: 
* El atributo href significa Hypertext REFerence (referencia de hipertexto).

* Su función es indicar la dirección o recurso al que apunta un enlace <a>.

* Gracias a href, un texto, imagen o botón se convierte en un hipervínculo clickeable.

Escribe tu respuesta aquí, incluyendo un ejemplo de código como < href="https://google.com">Ir a Google</

2. El Poder de la Semántica
HTML Semántico
¿Qué es el HTML Semántico y por qué es tan importante?

Escribe tu respuesta aquí, mencionando aspectos como accesibilidad (lectores de pantalla) y SEO (cómo los buscadores entienden tu página).

Respuesta:
El HTML semántico es la forma de escribir páginas web utilizando etiquetas que tienen un significado claro sobre el contenido que encierran. A diferencia de etiquetas genéricas como <div> o <span>, las etiquetas semánticas como <header>, <nav>, <main>, <article> o <footer> indican qué tipo de información contienen y cuál es su función dentro de la página.

Esto es importante por varias razones:

* Accesibilidad.

Los lectores de pantalla (usados por personas con discapacidad visual) pueden interpretar mejor la estructura de la página.

Por ejemplo, un lector de pantalla reconoce que <nav> es un menú de navegación y permite saltar directamente a esa sección.

* SEO (Posicionamiento en buscadores).

Los buscadores como Google leen el HTML semántico para entender el contenido y jerarquía de la página.

Esto ayuda a que el sitio aparezca en mejores posiciones porque el buscador sabe qué partes son títulos, menús, artículos, etc.

* Claridad y mantenimiento del código.

El HTML semántico hace que el código sea más fácil de leer y mantener.

Otros desarrolladores entienden rápidamente la estructura sin necesidad de muchos comentarios.

1: <header>
Sirve para definir el encabezado de una página o de una sección. Normalmente contiene el logo, el título principal o menús introductorios.

2: <nav>
Indica la barra o menú de navegación que contiene enlaces a otras secciones de la misma página o a otras páginas.

3: <main>
Se utiliza para encerrar el contenido principal de la página, es decir, lo más importante que diferencia esa página del resto. Solo debe haber un <main> por documento.

4: <section>
Define una sección temática dentro de la página. Sirve para agrupar contenido relacionado, como “Noticias”, “Cursos”, “Testimonios”.

5: <article>
Representa un contenido independiente y autónomo, que podría existir por sí mismo: un post de blog, una noticia, un comentario de foro, etc.

6: <aside>
Se usa para contenido complementario o secundario al principal, como barras laterales, anuncios, enlaces recomendados o widgets.

7: <footer>
Indica el pie de página de un documento o sección. Suele contener información de contacto, derechos de autor, enlaces legales o redes sociales.

