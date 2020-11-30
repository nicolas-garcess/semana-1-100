# RETO 1 CICLO 3 DEL GRUPO 100 MISIONTIC 2022 - APLICANDO HTML Y CSS PARA CONFIGURAR EL INICIO DE UN SITIO WEB

Este proyecto corresponde al reto 1 del ciclo 3 de la MisiónTIC 2022, en el cual nos encomendaron realizar la vista de la página de inicio para un sitio web, aplicando HTML y CSS.

## Descripción del reto

Desarrollar un sitio web que conste de 5 secciones, cada sección deberá ser realizada por un estudiante. Los diferentes elementos del sitio web contarán con estilos personalizados creados por los estudiantes y deberán estar condensados en una sola hoja de estilos.

Para iniciar con el desarrollo del sitio web, los estudiantes deberán definir previamente aspectos como ancho del sitio (mínimo 1200px), la información a presentar en el sitio web, diseñar un mockup, borrador o bosquejo, también descargar, diseñar o crear los recursos a utilizar como imágenes, iconos, logos, entre otros y finalmente asignar responsable a cada sección.

El proyecto, deberá manejarse versionado en un repositorio remoto en github, en el que los diferentes miembros del equipo deben tener acceso, no se permite el push directo a las ramas Dev o Master.

### Secciones

- Sección superior, cabecera o header: esta sección deberá contar con el menú de navegación a tres páginas internas del sitio web y su respectivo enlace al inicio. Debe contar con una imagen que ocupe el ancho del sitio.
  El menú debe de estar en un tag `<nav></nav>`.
- Sección de servicios: aquí los estudiantes deberán dividir en ancho del sitio en 3 partes y en cada parte se deberá incluir un servicio. Cada servicio debe contar con una breve descripción, un logo, ícono o imagen que lo identifique y un enlace al detalle de los servicios. El elemento donde están los servicios debe de tener un `id=”services”`
- Sección de noticias: El estudiante encargado de la sección de noticias, deberá dividir el ancho del sitio web en 2 filas y dos columnas para presentar 4 noticias. Cada noticia debe contar con un resumen, una imagen y un enlace a leer la noticia completa.
  El elemento donde están los servicios debe de tener un `id=”news”`

- Sección de equipo: El estudiante deberá dividir el ancho del sitio entre el número de participantes del equipo e incluir junto con cada uno una foto o imagen, el nombre y algún dato como la institución educativa, edad, pasatiempo, entre otros.
  El elemento donde están los servicios debe de tener un `id=”team”`

- Sección Footer o pie del sitio: el estudiante deberá crear el pie del sitio web en donde se incluye información de contacto, deberá estar dividido en dos partes, en una se tendrá la información del sitio web como el motivante del desarrollo y el enlace al repositorio de github, y en la otra los contacto de los miembros del equipo con sus nombres y roles. La sección debe de estar en un tag `<footer></footer>`

## Instrucciones para realializar el reto

### Header

1. Se genera la seccion "Header". al igual que sus secciones internas, para el caso propio, son 3 secciones, una que contenga el logo que queremos de la empresa, otra con el nombre y una última con el menú.
  - Dentro de body, colocar header.
  - Dentro de header colocar 2 secciones section.
  - Dentro del primer section se crea dos etiquetas div y una nav.
  - Dentro de la primera etiqueta div se encontrará la imágen del logo, lo cual se hace por medio de la etiqueta img.
  - En la segunda etiqueta div se encontrará la etiqueta h1 donde pondremos el título principal de la página.
  - En la etiqueta nav se pone la etiqueta ul y allí por dentro 4 etiquetas li las cuales tendrán los 4 enlaces necesarios de la barra superior: inicio, servicios, noticias y miembros.
  - En el segundo section se coloca la imágen de la sección con la etiqueta img.

2. Para cada una de las secciones o divisiones creadas, se genera su "Class".
  - Una vez se crean las secciones, divisiones y etiquetas del punto anterior, en cada una de ellas se crea su "Clase", asingnando un nombre para cada uno de la siguiente manera P.Ej: section class="barra-superior" " Aqui van las demás cosas que se ponen en la sección.

3. En la hoja Styles se colocan los nombres de cada clase y posteriormente se procede a asignarle su propio estilo, colocando un display flex en la barra superior que nos muestra el logo y nombre de la empresa y, el menú. Colocando también background color a toda la sección header y cambiando el tipo de letra a "Cursive".
  - Accedemos al archivo Styles.
  - Añadimos todas las clases creadas previamente al archivo P.Ej: .barra-superior{}.
  - Dentro de cada clase colocamos los estilos pertinentes a aplicar en cada uno, con la ayuda de la herramienta FlexBox.

### Main

#### Servicios

1. Se genera la etiqueta "Main". 
  - En este caso, por dentro se crea una etiqueta section "Servicios". 
  - Ahora, se crean 3 divisiones div, las cuales contendrán cada una, una imagen por medio de la etiqueta img. 
  - Dentro de cada etiqueta div, estará otra etiqueta div en la cual se colocará el texto correspondiente a cada imagen.
  - Cada imagen tendrá su respectivo titulo.

2. Cada sección y división creada tendrá su respectiva "Clase" asignada para qué, de esta manera, se pueda modificar el estilo por medio del archivo CSS.

3. En el archivo Stylo.css se dará estilo a cada clase según corresponda, alineando textos, modificando color de letra y background, tipo de letra, entre otros.

##### Noticias

1. Dentro de la etiqueta main se agrega una etiqueta section que contendrá dos div. 

2. En el primer div se ingresan otros dos div donde cada uno corresponte a una noticia. Con la etiqueta img src="ruta-imagen" se agrega la imagen a cada noticia, con p se agrega el texto de la noticia y con a href="link-noticia" Noticia se agrega el link a la noticia completa.

3. El segundo div contiene las mismas etiquetas del paso anterior.

4. En el archivo css se le da orden a las bloques que forman la sección noticia. Para esto se utiliza la función display: flex en la sección.

##### Miembros

1. Con base en la carpeta del workshop se trabaja sobre el código en VS Code, iniciando con la seccion "Header". Al igual que sus secciones internas, para el caso propio, son 3 secciones, una que contenga el logo que queremos de la empresa, otra con el nombre y una última con el menú.
  - Dentro de body, colocar header
  - Dentro de header colocar 2 secciones section
  - Dentro del primer section se crea la etiqueta div
  - Dentro de la primera etiqueta div se encontrará la foto de cada integrante del equipo lo cual se hace por medio de la etiqueta img, se le da el nombre respectivo a cada integrante por medio la etiqueta h2, seguido de una descripción de la carrera profesional, edad y pasatiempo por medio de la etiqueta p.  

2. Para cada una de las secciones o divisiones creadas, se genera su "Class".
  - Una vez se crean en la hoja Stylo las divisiones, colores de fondo, color de letra y etiquetas del punto anterior, en cada una de ellas se crea su "Clase", asingnando un nombre para la section id=“team” de la siguiente manera:  class =”miembros” y class=”miembros_contenedor".

3. Teniendo en cuenta la descripción anterior se replica 4 veces el div para completar le número de integrantes del equipo. 

4. En la hoja Stylo se trabaja en el body con un Font-family: cursive, whith; 1200px; y margin right y left auto  y posteriormente se procede a crear la section .miembros con los ambientes background-color y asignarle display: flex para dividir los cuadros y justify-content: space-evenly, con text-align: center que nos permite tener el texto centrado y margin-bottom: de 40px.
En el ambiente .miembros_contenedor se le da un width del 25%.

5. Accedemos al archivo Stylo mediante el href=”css/styles.css.

### Footer

1. En el archivo html se escribe el tag footer y dentro de este se colocan dos tags div que serán parte izquierda y derecha del pie de página. 

2. Al footer con css se le modifica el color, la fuente, ancho, alto, margen centrado y un display flex para que ambos bloques queden uno al lado del otro. 

3. Al lado de la izquierda con css se le dan dimesiones de ancho y alto, luego en html se le colocan otros dos div, uno para la zona izquierda (motivación) con lo solicitado en el reto (motivación del desarrollo y link del repositorio) y otro para la zona derecha baja para links de interés (políticas.

4. En el div motivación con css se hace un display flex y flex direction para que queden en columna ambos párrafos; a cada párrafo se le modifica las propiedades de color de letra, alineamiento justificado y se le dan márgenes para que quede en el lugar deseado; en el html se utiliza el tag a href="link-repositorio" para agregar el link del respositorio. 

5. Al div políticas con css se le hace un display flex y flex end para que quede ubicado hacia la derecha y a los links se le dan colores para que resalten si han sido oprimidos o no, esto se hace con las subclase en css a:visited; en html se utiliza la etiqueta a href="#" para agregar un link vacío.

6. Ahora, en el div derecho del footer con css se modifica el ancho y alto deseado, se hace un display flex con dirección columna. Éste se divide en dos div, uno para el título contáctenos y el segundo div contiene los datos de los integrantes del grupo. Con css se modifica el color de la letra del título y se le dan márgenes al párrafo. 

7. Al div de los integrantes con css se le hace un display flex, un flex-flow row wrap para que los alinee en línea y saltos de fila si se se supera el ancho del div principal, un justify-content sapace-round para que los separe espaciados y se alinean en el centro con align-items. Para cada párrafo, que corresponde a un integrante, se le modifica el color de la letra y se alinea el texto centrado.

## Colaboradores

### Juan Sebastián Prado
### Julián García
### Nicolás Garcés
### Raúl Amaya
### Jorge Quintero