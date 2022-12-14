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

## Maquetando la sección de redes sociales
  El espacio donde contendra la información de las diversas redes sociales que se pueda contar para que las personas conozcan más de nosotros.

## ¿Qué debo saber de CSS?
  CSS es utilizado para diseñar y dar estilo a las páginas web, por ejemplo, alterando la fuente, color, tamaño y espaciado del contenido, dividirlo en múltiples columnas o agregar animaciones y otras características decorativas. Este módulo proporciona un suave comienzo hacia el dominio de CSS con los conceptos básicos acerca de su funcionamiento, la sintaxis y la manera en que puedes comenzar a utilizarlo para agregar estilos al HTML.

  ![Imgur](https://i.imgur.com/mppve6a.png)

  Tipos de selectores que pueden ser fáciles o tan complejos como tú quieras.
  - Etiqueta
  - ID
  - Clase
  - Atributo

  ![Imgur](https://i.imgur.com/FlCOZpg.png)

  Y estos selectores se pueden combinar que pueden ser tan fáciles o tan complejos como se quiera.

  ![Imgur](https://i.imgur.com/06Yb78i.png)

## Cómo hacer deploy a internet
  Deploy es la forma con la que se le dice poner una página web en internet. Básicamente es liberar tu sitio web al mundo para que cualquier persona pueda accederlo o támbien "llevarlo a producción".

  Para que la página web pueda ser mostrada en tu la computadora, alguien tiene que entregártela primero. Ese alguienb es llamdo **servidor** porque es quien te sirve la página web que estás buscando.

## Deploy en [Netlify](https://www.netlify.com/)
  Te registras a la página de Netlify para poder hacer el deploy o támbien se puede hacer directamente desde **GitHub**.
  - Escogemos Deploy Manualmente

  ![Imgur](https://i.imgur.com/8UYPlIv.png)

  - Arrastramos toda la carpeta donde se encuentra nuestro proyecto.

  ![Imgur](https://i.imgur.com/pa4tqFv.png)

  - Listo tenemos nuestra página web desplegada, le hacemos click en la dirección.

  ![Imgur](https://i.imgur.com/6Ye3BAX.png)

## Compra el dominio de tu página web
  Un dominio es nuestra dirección en internet una dirección IP, es el que le permite al navegador poder encontrar la página web.

  Donde podemos adquirir nuestro dominio atraves de esta página [NameCheap](https://www.namecheap.com/) donde te pide estar registrado y añadir un método de pago.

  No es el unico lugar donde se puede comprar, puedes usar [Nominalia](https://www.nominalia.com/)

  Buscamos el nombre del dominio que deseamos tener donde nos dara una lista de toda las opciones que podamos tener con difrentes extensiones que existan, lo mas recomendable siempre intentar adquirir el que termina en **.com**.

  ![Imgur](https://i.imgur.com/jFacmna.png)

  Despues de comprar el dominio nos movemos a la página donde fue desplegado nuestro sitio web en este caso usamos Netlify, donde añadiremos el dominio.

  ![Imgur](https://i.imgur.com/Oj0TLeO.png)

## Cómo comprar un hosting para mi página web
  Muchas veces  necesitamos tener mayoy control sobre lo que hacemos y necesitamos hacer más cosas "como a empezar a manejar backend" entonces debemos empezar a pensar en un hosting. Tenemos de varios tipos:

  - Hosting compartido es un servidor que se encarga de alojar varias paginas web.
  - VPS Virtual Private Server son maquinas virtuales que corren dentro de una computadora para ser usada como hosting.
  - Servidor dedicado una computadora completa para uso exclusivamente para tu sitio web.

  Ventajas del hosting compartido:
  - Muchas veces el hosting compartido se suele vender por paquetes que te incluyen almacenamiento, dominio, SSL, bases de datos  y cuentas de correo personalizados.

  Recomendaciones de hosting:
    - [HostGator](https://www.hostgator.com/)
    - BanaHosting
    - Kinsta Hosting
    - WP Engine
    - Hostinger
    - DigitalOcean
    - Siteground
    - HostPapa

## Qué es no-code
  Construir un sitio web **No-Code** nos ayuda a terner un ***MVP*** en poco tiempo y sin gastar mucho dinero, nos permite resolver rápido el problema que necesitamos resolver.

  Ventajas:
  - Velocidad
  - Agilidad
  - Bajo costo
  - Fácil de mantener
  - Seguridad

  Desventajas:
  - Poca escalabilidad
  - Personalización limitada
  - Poco control de las herramientas
  - Dependes de otros desarrolladores

  Las herramientas No Code permiten crear software sin usar lenguajes de programación, solo a través de interfaz visual.

  La misma palabra No Code (ningún código) es recurrente entre herramientas muy conocidas: Airtable, Zapier, Stripe, Notion, Landbot, Shopify, Wix, Webflow, Substack, Typeform, WordPress y otras.

  [Por qué aprender No Code: ventajas de las herramientas](https://www.torresburriel.com/weblog/2021/11/25/porque-aprender-no-code-ventajas-de-las-herramientas/)

  ¿Qué es WordPress?
  Es un sistema manejador de contenidos que nos permite crear sitios web de una forma muy rápida y sin necesidad de código. Basado en PHP.

  Wordpress con Docker, tener instalado previamente docker en su computadora podemos usar contenedores donde tendremos corriendo una base de datos y wordpress para poder practicar, teniendo estas configuraciones:

  - Nuestro archivo de **docker-compose.yml**:
  ```yml
  version: '3.1'

  services:

    wordpress:
      image: wordpress
      restart: always
      ports:
        - 8080:80
      environment:
        WORDPRESS_DB_HOST: db
        WORDPRESS_DB_USER: exampleuser
        WORDPRESS_DB_PASSWORD: examplepass
        WORDPRESS_DB_NAME: exampledb
      volumes:
        - ./wordpress:/var/www/html
    
    db:
      image: mysql:5.7
      restart: always
      environment:
        MYSQL_DATABASE: exampledb
        MYSQL_USER: exampleuser
        MYSQL_PASSWORD: examplepass
        MYSQL_RANDOM_ROOT_PASSWORD: '1'
      volumes:
        - ./db:/var/lib/mysql
  ```
  - Ejecutamos estos comandos para levantar nuestros contenedores:
  ```bash
  docker-compose up -d wordpress
  docker-compose up -d db
  ```

  - Nos movemos al navegador a la siguiente dirección http://localhost:8080 donde podras instalar wordpress paso a paso simplemente existiendo dentro de un contenedor.

  ![Imgur](https://i.imgur.com/bJJxAlZ.png)

## Instalación y configuración de Elementor
  Instalaremos el plugin llamado **Elementor** nos servira para construir páginas web añadiendo elementos sin la necesidad de usar código.

  ![Imgur](https://i.imgur.com/gzcl282.png)

  Dentro de Elementor

  ![Imgur](https://i.imgur.com/uM4Azv0.png)

  Simple Page

  ![Imgur](https://i.imgur.com/CmoE8Sk.png)

## Mi primera página web con Elementor
  Dentro de Elementor encontramos los diferentes elementos que nos ayudaran a construir nuestra página web de manera muy sencilla.

  ![Imgur](https://i.imgur.com/fP3LhfC.png)