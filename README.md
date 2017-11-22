# Lyft

Éste reto de código consistió en replicar el sitio **Lyft**
![Lyft - Footer](docs/footer.gif)
 Para lo cual empleé html y css.
***


## Consideraciones

* Use los archivos "index.html" y "main.css"
para esctructurar mi código.

* Encontré todo el material (imagenes y archivos html y css) que necesitaba en las carpetas que clone del repositorio que Laboratoria me proporcionó.

* En dicho repositorio también se indicaba las tipografías, colores y videos que debía usar. También  el sitio donde obtener los iconos que necesité [Icomoon].


## Flujo de trabajo

1. Primero hice la estructura del sitio en mi documento index.html.

2. Enlace mi hoja de estilos al head de mi estructra básica de html con una etiqueta link.

  2.1 También enlace mi carpeta fonts donde guarde el archivo de la fuente de iconos Icommon.

  2.3 Enlace mi tipografía con el link de google fonts.

3. En el body de mi estructura usé etiquetas de html semántico para dividir las partes de mi sitio (header, section,footer).

4. En el **header** coloqué la imagen de fondo usando las propiedades background-image y backgrouns-size: cover; para que ocupara el fondo de mi sección a la cual le dije que ocupara el 100% de ancura. Dentro de la  barra de navecgación **nav** puse dos contenedores, uno con el logo de lyft y otro con la lista del menú.

  4.1 fuera de nav pero aún dentro de header puse el contenedor con la información, input y los dos botones.

5.  En la primer sección coloqué dos contenedores que ocupan el 50% del anchi, dentro del primero puse 3 contenedores más, uno para cada parrafo. y en el segundo puse la imagen del telefono.

6. En la segunda sección puse tres contenedores y dentro de cada uno de ellos coloque dos más, uno donde coloque el texto a un 33% de ancho y el segundo para el video con 67% de ancho. Ambos los flote a la izquierda y para que no se empalmara con el siquiente contenenedor los limpie con la propiedad clear.

  6.1 Los videos de ésta sección los coloque con la etiqueta iframe y el enlace que youtube te da. El enlace viene con un ancho y alto predeterminado el cual cambie para que se adecuara a mi página.

7. El **footer** lo dividí con dos contenedores al 100% de ancho y dentro del primero puse 4 contenedores mas al 25% de ancho, dentro de los primeros 3 hice listas  para escribir los datos requeridos y les di hover. En la última coloque los logos de las tiendas en linea los que coloque en contenedores con un ancho y alto específico.

  7.1 En el segundo contenedor del Footer puse los iconos de las redes sociales isando las claves de Icomoon, y para finalizar usé un hr para dividirlo del copyrigth.
