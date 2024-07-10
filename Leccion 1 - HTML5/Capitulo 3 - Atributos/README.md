# Capitulo 3 - Atributos

**¿Qué son los atributos en las etiquetas?**

Los atributos de una etiqueta son las características con las cuales se pueden personalizar dicha etiqueta. Los atributos en común en la mayoría de las etiquetas más utilizadas son _id_ y _class_, los cuales se utilizan generalmente para poder identificarlos dentro del documento HTML y luego trabajar con ellos desde CSS y JavaScript, lo cual veremos en las lecciones siguientes.

# ¿Cómo se declaran los atributos en una etiqueta?

Los atributos se declaran dentro de la etiqueta de apertura. Por ejemplo, si yo quiero darle un _id_ a una etiqueta de parrafo, lo haría de la siguiente manera:

- `<p id="mi-parrafo-especial">Este es mi parrafo especial con su id declarado</p>`

Ahora bien, existen muchos atributos que son específicos para ciertos grupos de etiquetas y no son compatibles con otros. En la siguiente sección comentaremos algunos.

# ¿Cuáles son algunos atributos específicos?

Podemos dar como ejemplo la etiqueta de enlaces que nos llevan a otra página dentro del sitio o fuera del mismo. La etiqueta para enlaces es `<a>` y para llevarnos a otra dirección se hace con el atributo _href_. Ejemplo:

- `<a href="https://www.algunsitio.web">Vamos a algún sitio .web</a>`

Ahora, podemos hacer que este enlace se abra en otra pestaña y podemos añadir a la misma etiqueda el atributo _target="\_blank"_:

- `<a href="https://www.algunsitio.web" target="_blank">Vamos a algún sitio .web</a>`

Otro ejemplo que podemos mencionar es en el caso de cuándo queremos mostrar una imagen y utilizamos la etiqueta `<img>` y el atributo para dar la ruta donde se encuentra la imagen es _src_. Ejemplo de como lo escribimos:

- `<img src="nombre-imagen.jpg">`

Cabe señalar que si estamos dando una dirección de la imagen dentro de nuestro proyecto, el mismo debe darse bien la ruta en dónde está guardado, sino se mostrará con error. Esta aclaración aplica también para otras páginas dentro de nuestro propio sitio web o archivos que queramos permitir que se descarguen o compartan.

Puedo extenderme más en el tema de atributos, pero no es el propósito de este tutorial, ya que solo deseo abarcar los fundamentos básicos de la programación web para que comiencen a enteder como funciona.
