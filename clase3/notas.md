# Notas clase 3
## Enunciados o encabezados
Los enunciados se crearon para establecer el tema de una página
desde h1 hasta h6
El h1 es el tema principal y los demás van a ir disminuyendo en importancia
```html
<h1>Tema principal</h1>
<h2>Subtema</h2>
<h3>...</h3>
```
Google da suma importancia al contenido del h1.
Al h2 le da poca importancia y el h3 tiene casi nula importancia.

> Recomendación: en cada página debo tener 1 únco h1.  
> Esto hará que google indexa mejor (más arriba) el contenido de mi página.


## Elementos de maquetado semántico

Maquetar significa pasar a código HTML y CSS el contenido de nuestro prototipo/diseño

En HTML tenemos ciertos elementos que fueron creados para poder dar estructura a nuestras páginas. Fueron creados para maquetar
Algunos de estos elementos son:
```html
<header>
    <nav>
<main>
    <section>
        <article>
<footer>
```

## Hoja de estilos
Una hoja de estilos es un archivo con extensión .css
En este archivo vamos a insertar todo y código de la parte estética
Para que funcione tendremos que enlazarlo desde el HTML con el elemento
```html
<link rel="stylesheet" href="hoja-de-estilos.css">
```
En el CSS tenemos selectores. 
La sintaxis es:
```css
selector{
    atributo: valor;
    atributo2: valor;
}
```

## Tipografías
### Tipografías seguras:

Las tipografías seguras son aquellas que ya vienen pre instaladas en todos los dispositivos. Sin importar si es un dispositivo móvil, un tablet o equipo de escritorio o laptop

<https://chatgpt.com/share/68bb2a6b-33c8-8013-a990-639d82a2d331>   

### Tipografías en la nube
Existen varios servicios de tipografías que podemos enlazar directamente desde la web de un proveedor
Esto quiere decir que puedo usar tipo grafías sin necesidad de instalarlas
Y lo mejor de todo es que cuando un cliente entre a nuestro sitio tampoco necesita descargarlas o instalarlas porque estas tipografía se encuentran Online

> <https://fonts.google.com/>

> <https://fonts.bunny.net/>

Respuesta a una pregunta sobre el tamaño de la tipografía.

    Base font-size
    De manera predeterminada, en un equipo de escritorio, el tamaño es 16 pixeles
    Luego las hs serán multiplicadas por un factor

    Si no configuramos el tamaño de tipografía para body este es 16 pixeles

    base -> 16px
    h1   -> base * 2
    h2   -> base * 1.5
