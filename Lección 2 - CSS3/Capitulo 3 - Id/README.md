# Capitulo 3 - Id

Llegamos a un punto del diseño web cuando una etiqueta comparte diseño con otras, pero nosotros necesitamos que tenga algún o algunas características distintas a las que veníamos usando en las clases. En esos casos, utilizamos el el atributo id y le damos un nombre específico que no puede volver a repetirse en el documento y no debe haber sido aplicado en alguna otra clase o id, ya que esto generaría inconsistencias y errores en la experiencia visual deseada.

# ¿Cómo declaramos un id?

Tal como lo explicamos con las clases, la declaración de id ocurre dentro del documento HTML en la etiqueta que deseamos dar el diseño específico. El mismo se declara de la siguiente manera: `id=nombre-específico-que-le-demos`.

# Vamos por el ejemplo

Usaremos como base el documento de la lección anterior, pero tendremos la particularidad que al último parrafo le daremos un id, porque queremos hacer que solo ese último parrafo quede en cursiva y lo haremos de la siguiente manera:

En el HTML:

```
<h2>Este título lo dejamos normal</h2>
    <p>Este parrafo también lo dejamos normal</p>
    <h2 class="rojo">Este título será en rojo</h2>
    <p class="rojo">Y le acompaña este parrafo en color rojo</p>
    <h2>Dejamos este título normal</h2>
    <p class="rojo" id="cursiva">Pero este parrafo lo haremos con color rojo y en cursiva</p>
```