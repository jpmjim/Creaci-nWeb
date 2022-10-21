# Curso de Creación de Páginas Web
  Frontend abarca toda la parte visual por el usurario desde su estructura inicial dentro de un mockup, lo más básico que se debe dominar en el frontend son nuestros tres lenguajes ***html, css y javascript***.

  - HTML es ese lenguaje con el cual puedes definir la estructura de cualquier página web.
    - Aprender las etiquetas, támbien necesitamos saber sobre la accesibilidad ya que una página web debe poder ser usada por cualquier usuario (pueda contar con alguna descapacidad) con la ayuda de etiquetas que son lectores adaptando nuestro sitio web. 
    - Debemos aprender a escribit **html semántico** es decir que tenga sentido aprnder usar las etiquetas correctas en el lugar correcto es fundamental.

  - CSS es el lenguaje de estilos utilizado para describir la presentación de documentos html.
    - Dentro de css los selectores son importantes al momento de seleccionar los elementos del html.
    - La alineación con CSS al momento de disttribución de los elementos dentro del espacio una de las más comunes encontramos a Flexbox y una de las mejores es CSS Grid el cual nos permite crear diseños inimaginables, más sencillos de sleccionar layouts.
    - Dentro de css podemos crear animaciones esto le da un plus a la página web y la hace más dinámnica para el usuario.
    - El responsive la página web debe adaptarse a cualquier tamaño de pantallasobre todo al trabajar con Mobile First.

  Backend maneja todos los datos que le sirve el Frontend desde datos generales hasta los datos mas sensibles, es donde los usuario no puedan ver tan facilmente, también es todo la infraestructura por parte del servidor.
  - Podemos empezar eligiendo algún lenguaje del lado del servidor como puede ser php, python, java, nodejs, etc.
  - Debemos aprender sus fundamentos, la sintaxis que manejan el lenguaje que estes usando.
  - La persistencia de datos, desde las relacionales y las no relacionales como mysql, mongodb, firebase, postgresSQL. 
  - EL deploy el trasladar tu página web distribuirla por el internet, lo cual usando el sericio de hosting que se encargan de esa tarea, donde podemos subir mediante los servicios microsoft Azure. Google Cloud, Amazon Webservices.
  - Arquitectu utilizadora backend cómo conectamos todos los servicios como la conexión entre base de datos, para lograr construir aplicaciones que pueden ser escalables.

## ¿Qué debo saber de HTML?
  (Hyper Text Markup Languaje) es un lenguaje de marcado de texto, es el código que se utiliza para estructurar el contenido de tu web, y darle sentido y propósito, Hyper Text significa que el texto tiene interactividad, conexión con otros documentos, Markup significa que le pone etiquetas a los elementos, por eso también se le conoce como lenguaje de etiquetas.

  - Anatomía de una página web:
    La anatomía de una página web se refiere al acomodo de información o secciones de la página que dividimos por medio de [etiquetas específicas](https://developer.mozilla.org/es/docs/Web/HTML):
    - CONTAINER→ contenedor principal de la información
    - HEADER → Cabecera de la página
    - MAIN CONTENT → Estructura o contenido principal de la página
    - SIDEBAR → Contenido secundario de una página (anuncios, etc.)
    - FOOTER → Pie de página

      ![](https://root-cuckoo-af5.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fa22f86c3-622e-4aa8-b60c-a145a47a759a%2FUntitled.png?table=block&id=0b925eec-ee3a-416a-9b3e-c47bb25acad2&spaceId=13288771-0d8b-469c-8940-e662d0415c68&width=2000&userId=&cache=v2)

## Mi primera página web con HTML
  Tu primer archivo html siempre tiene que llamarse index.html, index va a ser la página principal que el servidor va a buscar al momento que tenga que abrir un proyecto. Si esta página no existe, nosotros tendríamos que decirle al servidor cuál es la página que tiene que tomar como página de inicio.

  - <! DOCTYPE html> → Informa al navegador qué versión de HTML se usó para escribir el documento, en este caso html. DOCTYPE es una declaración, no una etiqueta.
  - <html lang=”es”> → Es la etiqueta “padre” donde vivirá nuestro proyecto. El atributo lang establece el idioma del sitio web. Debemos usarlo para que el navegador pueda traducir nuestra página.
  - <head> → La cabecera (en inglés head) es la parte del documento HTML, que contiene metadatos sobre ese documento, como el autor, la descripción y los enlaces a los archivos.
  - <body> → El elemento body de HTML representa el contenido de un documento HTML. Solo puede haber un elemento <body> en un documento

  [Referencia de Elementos HTML](https://developer.mozilla.org/es/docs/Web/HTML/Element)

  Anatomía de una etiqueta de HTML:
  ![](https://root-cuckoo-af5.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F801829fb-1816-4ac6-bc01-2727bacde74a%2FUntitled.png?table=block&id=bb0e5eb8-7ccd-43eb-99ab-fbba3cb761e0&spaceId=13288771-0d8b-469c-8940-e662d0415c68&width=2000&userId=&cache=v2)


## Maquetando el hero
  Donde se da a conocer una parte de la información o descripción de la persona, con una imagen de fondo para darle mas estilo a una fotografía, a una pequeña descripción a lo que haces.
