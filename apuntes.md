<!--# Titulos
## Subtitulos-->
<!--Estos se usan para demarcar los titulos como en html pero con numeral de acuerdo a cuantos se les coloque-->
<!--para escribir en italica colocar "" 
lo mismo para negrita pero con ** **-->
<!--para colocar una lista desordenada ul colocar un * y luego la palabra
para listas ordenadas colocar un numero y un punto 1. y luego un espacio-->
<!--Para colocar enlace primero se ingresa el texto entre [] luego ingresar el url entre ()-->
<!--Para colocar una citacion se debe colocar un > -->
<!--Tambien se pueden genrar lineas de separacion o de etiqueta con tres guiones seguidos --- -->
<!--Para poder citar una linea de codigo solo se debe coloar dos tildes y entre las tildes colocar el codigo `` y para colocar multiples lineas de codigo se debe colocar tres tildes al inicio y al final ```..... ``` para colocarles color segun el lenguaje que esta utilizando esa linea solo hay que escrbir el nombre del lenguaje despues de las tres tildes ej 
```css
.contenido-hero {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0, .7);
    background-color: rgb(0 0 0 /70%);
``` al ciralo de esta manera quedara en un recuadro y resatado con los colores-->
<!--Se pueden generar tablas colocando 
|texto|texto|texto| barras y dandole forma entre cada barra para columnas y filas darles espacion con tab -->
<!--Para cargar un aimagen es lo mismo que con los enlaces nada mas que lo que se debe poner el principio antes de los corchetes es un signo de exclamacion ej. ![texto](enlace)-->


#Apuntes de Proyecto Frontend Store

##Apuntes BEM

<p> BEM es un tecnologia para crear codigo reutilizable y ordenado en tus proyectos de css. Para esto hay que seguir las convenciones de BEM.
Para evitar la colision de nombres.
### Reglas de BEM
####Bloques <p>Son un Contenedor si una seccion por si sola es significativa y no requiere de otras secciones para su apariencia (css) debera ir en un bloque.
```html
<div class= "cliente">...</div>
```
```css
.cliente {...}
```
####Elementos<p>Parte de un bloque, depende del bloque y no es por si solo significativo; tienen la caracteristica de que utilizan el nombre del bloque y despues doble guion bajo _
```html
<p class= "cliente__nombre">...</p>
```
```css
.cliente__nombre{...}
```
####Modificadores <p>¿Un bloque o un elemento tendra una variante? Entonces se utiliza un modificaor que es una "bandera" que avisa que ese elemento tendra un diseño diferente.
```html
<p class= "cliente__nombre--ceo">...</p>
```
´´´css
.cliente__nombre--ceo{...}
´´´
