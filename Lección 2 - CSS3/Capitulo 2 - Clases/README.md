# Capitulo 2 - Clases

A medida que vamos avanzando en el diseño web, muchas veces notamos que tenemos ciertos grupos de etiquetas distintas, pero que queremos que compartan el mismo tipo de diseño que otras. Si tuvieramos que ir etiqueta por etiqueta generando el diseño, se volvería muy tedioso y molesto. Para tal motivo, existen las clases que se declaran como atributo en cada etiqueta.

La forma de declarar una clase es en el documento html en las etiquetas que queramos diseñar. Se hace a través del atributo de clase de la siguiente manera: `class="nombre-que-le-demos-a-la-clase"`.

# Hagamos una prueba

Supongamos que queramos que algunas etiquetas h2 y algunos parrafos sean de color rojo, haríamos lo siguiente en el html:

```
<h2>Este título lo dejamos normal</h2>
<p>Este parrafo también lo dejamos normal</p>
<h2 class="rojo">Este título será en rojo</h2>
<p class="rojo">Y le acompaña este parrafo en color rojo</p>
<h2>Dejamos este título normal</h2>
<p class="rojo">Pero este parrafo lo haremos con color rojo</p>
```

Ahora bien, si solamente declaramos las clases en el html, pero no hacemos nada en el archivo css, será lo mismo que nada.

La declaración de una clase en css se hace con un punto y seguido con el nombre de la clase que creamos en el documento html.

En el archivo donde estemos trabajando nuestro css, escribiremos lo siguiente para que funcione los cambios que queremos:

```
.rojo {
    color: red;
}
```

Noten el punto seguido inmediatamente y sin espacio el nombre de la clase rojo. Si abrimos nuestro documento web, notaramos como nuestras etiquetas con las clases señaladas están con el diseño que nosotros queremos.

# Aclaremos

Si bien hasta el momento los ejemplos han sido haciendo el cambio de color de las etiquetas y de las clases, hay mucho más camino por recorrer, pero el motivo de este tutorial se está enfocando en las bases del desarrollo web. Para abarcar más en detalle lo que se puede hacer en CSS, realizaré otro tutorial y más extendido de como utilizar propiedades más avanzadas de css.

# Continuemos

En la siguiente lección nos enfocaremos cuando necesitamos diseño específico para una sola etiqueta dentro del documento.