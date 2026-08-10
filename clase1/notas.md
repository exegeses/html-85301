# Notas clase 1
## Curso: desarrollo web con HTML
En este curso vamos a aprender a crear página web y sitio web.
Esto es el fundamento de las aplicaciones en la nube.
En este curso vamos a aprender inicialmente dos lenguajes.

1. HTML
2. CSS

## 1. HTML
HTML es un lenguaje para crear páginas web. 
HTML (HyperText Markup Language - Lenguaje de Marcado de hipertexto)
Fue creado en 1993 y es un lenguaje que tiene contenedores.
La palabra marcado indica que cada uno de los elementos es una marca
Cada marca o elemento tiene una funcionalidad, un uso específico
Podemos decir que hay un elemento para:

    Insertar una imagen
    Insertar una enlace
    Insertar un párrafo
    Insertar un video
    Insertar un texto en negrita

Combinando estos elementos vamos a generar la estructura de nuestras páginas web.

## 2. CSS
CSS (Cascading Style Sheets)
CSS es el lenguaje encargado de generar la estética de un sitio, fue creado en 1994.
Si bien con HTML se puede generar un mínimo de estética, no se recomienda hacerlo en HTML. Así que el lenguaje CSS se va encargar de toda la presentación y el diseño.
Estamos hablando de colores, tamaños, posiciones, tipografía y todo lo que tenga que ver con la presentación visual de los elementos.

### Elementos
HTML todos los elementos son contenedores
Tienen una sintaxis específica
Si encierran entre <>

Sintaxis básica de HTML: 

```html
    <elemento>contenido</elemento>
```

### Anidamiento
En algún momento, vamos a querer combinar elementos.
Para poder combinar estos elementos lo que vamos hacer es insertar uno dentro de otro
Esta es la base de la estructura de una página web    

```html
    <elemento>
        <elemento>
            contenido
        </elemento>
    </elemento>
```

## Atributos
Los atributos son modificadores de un elemento

```html
    <elemento atributo="valor"> contenido </elemento>  
    <elemento atributo="valor" atributo2="valor2"> contenido </elemento>  
```