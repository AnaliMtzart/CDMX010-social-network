# MXCHILAZO

## 1. Resumen del proyecto

MXCHILAZO en una Red Social dirigida a los turistas y por supuesto para nosotros los chilangos, 
quienes en un fin de semana quizás y luego de una semana agotadora buscamos pasear, 
pero siempre surge el ¿A dónde vamos?. 
Bueno pues MXCHILAZO ofrece la solución a esa problemática pero...sin ir muy lejos. 
Ofreciendo lugares dentro de las distintas delegaciones acompañadas de información y 
reseñas que le serán útiles al usuario para tomar una decisión. 

La app permite a cualquier usuario crear una cuenta de acceso y loguearse con ella 
o con otras cuentas como lo son Facebook y Google; crear, editar, borrar y _"likear"_ publicacciones.

## Demo
Puedes ingresar al MVP de [MXCHILAZO](https://mxchilazo-by-anali.netlify.app/)<br>

La aplicación esta diseñada para el uso en dispositivos móviles, por lo que te sugerimos visualizarla en modo de 360x640 <br>

Es necesario ingresar con un usuario y una contraseña, por lo que puedes crear una o acceder con:<br>
Correo: anali@gmail.com <br>
Contraseña: anali1

## Diseño de la Interfaz de Usuario (prototipo de baja fidelidad)

Se identificaron y aterrizaron los elementos básicos que debería de llevar la app para posteriormente integrarlos en un prototipo de alta fidelidad.

<img src='https://firebasestorage.googleapis.com/v0/b/analimtzart.appspot.com/o/analiprot1.jpg?alt=media&token=6d3ab776-962f-4d06-a42f-85aaf86acf83' width='400' >

## Prototipo

Se desarrolló un espacio donde el flujo para el usuario sea sencilla
y clara durante su recorrido por el sitio, siempre con el objetivo de que obtenga 
la información necesaria para tomar una decisión.
Para la paleta de color se eligieron tonalidades moradas y rosadas resaltando elementos del sitio. 
Al desarrollar el diseño buscamos que fuera intuitivo, simple y amigable para el usuario.

[Figma](https://www.figma.com/file/W5eXYNQpbfOT1KKUdvIlHK/MXCHILAZO?node-id=0%3A1)

## Prototipo final

<img align='center' width="100%" src="https://firebasestorage.googleapis.com/v0/b/analimtzart.appspot.com/o/MXCHILAZO.gif?alt=media&token=b5b599e8-e35b-4f9a-8eb2-1d53b5085525"/>

## 3. Objetivos de aprendizaje

El objetivo principal de aprendizaje de este proyecto es construir una
[Single-page Application (SPA)](https://es.wikipedia.org/wiki/Single-page_application)
[_responsive_](../../topics/css/02-responsive) (con más de una vista / página)
en la que podamos **leer y escribir datos.**

### HTML y CSS

* [ ] [Uso de HTML semántico.](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#Semantics_in_HTML)
* [ ] Uso de selectores de CSS.
* [ ] Construir tu aplicación respetando el diseño realizado (maquetación).
* [ ] [Uso de flexbox en CSS.](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### DOM y Web APIs

* [ ] Uso de selectores del DOM.
* [ ] Manejo de eventos del DOM.
* [ ] [Manipulación dinámica del DOM.](https://developer.mozilla.org/es/docs/Referencia_DOM_de_Gecko/Introducci%C3%B3n)
(appendChild |createElement | createTextNode| innerHTML | textContent | etc.)
* [ ] [History API.](https://developer.mozilla.org/es/docs/DOM/Manipulando_el_historial_del_navegador)
* [ ] [localStorage.](https://developer.mozilla.org/es/docs/Web/API/Window/localStorage)

### JavaScript

* [ ] Uso de condicionales (if-else | switch | operador ternario)
* [ ] Uso de funciones (parámetros | argumentos | valor de retorno)
* [ ] Manipular arrays (filter | map | sort | reduce)
* [ ] Manipular objects (key | value)
* [ ] Uso ES modules ([`import`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
| [`export`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export))
* [ ] Diferenciar entre expression y statements.
* [ ] Diferenciar entre tipos de datos atómicos y estructurados.
* [ ] [Uso de callbacks.](https://developer.mozilla.org/es/docs/Glossary/Callback_function)
* [ ] [Consumo de Promesas.](https://scotch.io/tutorials/javascript-promises-for-dummies#toc-consuming-promises)

### Testing

* [ ] [Testeo unitario.](https://jestjs.io/docs/es-ES/getting-started)
* [ ] [Testeo asíncrono.](https://jestjs.io/docs/es-ES/asynchronous)
* [ ] [Uso de librerias de Mock.](https://jestjs.io/docs/es-ES/manual-mocks)

### Estructura del código y guía de estilo

* [ ] Organizar y dividir el código en módulos (Modularización)
* [ ] Uso de identificadores descriptivos (Nomenclatura | Semántica)
* [ ] Uso de linter (ESLINT)

### Git y Github

* [ ] Uso de comandos de git (add | commit | pull | status | push)
* [ ] Manejo de repositorios de GitHub (clone | fork | gh-pages)
* [ ] Colaboración en Github (branches | pull requests | |tags)
* [ ] Organización en Github (projects | issues | labels | milestones)

### Firebase

* [ ] [Firestore.](https://firebase.google.com/docs/firestore)
* [ ] [Firebase Auth.](https://firebase.google.com/docs/auth/web/start)
* [ ] [Firebase security rules.](https://firebase.google.com/docs/rules)
* [ ] Observadores. ([onAuthStateChanged](https://firebase.google.com/docs/auth/web/manage-users?hl=es#get_the_currently_signed-in_user)
 | [onSnapshot](https://firebase.google.com/docs/firestore/query-data/listen#listen_to_multiple_documents_in_a_collection))

### UX

* [ ] Diseñar la aplicación pensando y entendiendo al usuario.
* [ ] Crear prototipos para obtener feedback e iterar.
* [ ] Aplicar los principios de diseño visual (contraste, alineación, jerarquía)
* [ ] Planear y ejecutar tests de usabilidad.

### Mobile first

El concepto de [_mobile first_](https://www.mediaclick.es/blog/diseno-web-responsive-design-y-la-importancia-del-mobile-first/)
hace referencia a un proceso de diseño y desarrollo donde partimos de cómo se ve
y cómo funciona la aplicación en un dispositivo móvil primero, y más adelante se
ve como adaptar la aplicación a pantallas progresivamente grandes y
características específicas del entorno desktop. Esto es en contraposición al
modelo tradicional, donde primero se diseñaban los websites (o webapps) para
desktop y después se trataba de _arrugar_ el diseño para que entre en pantallas
más chicas. La clave acá es asegurarse de que desde el principio diseñan usando
la vista _responsive_ de las herramientas de desarrollador (developer tools) del
navegador. De esa forma, partimos de cómo se ve y comporta la aplicación en una
pantalla y entorno móvil.
