# Kit de supervivencia HTML5 CSS3
Durante una de mis clases de lenguaje de marcas, generamos un documento HTML con CSS con las opciones básicas para poder visualizar una página decentemente con HTML5 y CSS3.
## HTML5 CSS3 básico
No se trata de un ejemplo de uso extensivo de las (muchas) posibilidades de maquetación con HTML y CSS, si no una pequeña introducción, tal vez un recordatorio, de cómo me introduzco, en ocasiones, a generar la vista de una aplicación.
# Flex y Grid
Para los que llevamos mucho tiempo maquetando HTML, la llegada de flex y grid supuso un gran cambio en cuanto a la comodidad y rapidez en la maquetación, por eso, me gusta comenzar con la maquetación tal y como hacíamos antes y cómo se hace con flex o grid.
```
    .miClase {
        display: flex;
        flex-wrap: wrap;
    }
```
Me gusta comenzar asignando flex a una clase y ver cómo se comportan los elementos de bloque anidados.
```
    .miClase div {
        width: 150px;
    }
```
Con estas 2 sencillas sentencias crearemos una vista de bloques de 150px que, cuando no caben en el ancho de pantalla actual, pasan automáticamente a la línea siguiente (al estar flex-wrap: wrap, y en su modo por defecto -no-warp- todos los elementos de bloques serán mostrados en una única línea).

# BasicHTML5.html
Este documento tiene todo lo básico, tanto en lo referente a etiquetas semánticas HTML5 como las clases CSS3 (nótese cómo el significado de *aside* se visualiza gracias a estar incluido como elemento de bloque con tamaño dentro de un div con display:grid) 
## Responsive
Nos introducimos en HTML5/CSS3 al mismo tiempo que en la creación de código HTML responsive, que se adapte a los dispositivos donde se visualiza gracias a las *media Querys* (nótese que, este ejemplo, se cambia una propiedad flex que hace que se inviertan la posición de las columnas)
```
@media (max-width:1000px) {
    main {
        flex-direction: row-reverse;
    }
}
```
# Mi-primer-documento-css.html
Por último, y para recopilar todo lo *básico* aprendido en lo relativo a `HTML5 & CSS3` generaremos el documento Mi-primer-documento-css.html en el que utilizaremos imágenes externas y fuentes de Google así como parámetros básicos para generar una vista de manera rápida. 

---
`título:` Kit de Supervivencia HTML5-CSS3 \
`autor:` David G. Bonacho &nbsp;&nbsp;  [www.tizedit.com](https://www.tizedit.com)