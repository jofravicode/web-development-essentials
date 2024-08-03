# Capitulo 1 - ¿Que es CSS3?

Utilizando el glosario que se encuentra en Mozilla Developers, cito la descripción sobre este tema:

`"CSS, de las siglas en inglés Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje declarativo que controla el aspecto de las páginas web en el navegador. El navegador aplica declaraciones de estilo CSS a los elementos seleccionados para exhibirlos correctamente. Una declaración de estilos contiene las propiedades y sus respectivos valores, los cuales determinan cómo se verá una página web."` (https://developer.mozilla.org/es/docs/Glossary/CSS)

Cabe señalar que, al igual que HTML, CSS no es un lenguaje de programación. CSS simplemente es el lenguaje con el cual se da diseño a una página web.

# ¿Cómo funciona?

Al final de la lección de HTML mencioné acerca de las etiquetas y sus atributos. Pues, la forma de dar diseño a un documento HTML es a través de las referencias de las etiquetas y de los atributos id y class cuando queremos abarcas algunas más específicas.

Existen dos formas de generar mencionar el CSS dentro del documento html. La primera que veremos, será la que va en el mismo documento con la etiqueta `<style>`, la cual va dentro de la etiqueta `<head>`.

# Ejemplo 1 dentro de la etiqueta style

Vamos con el siguiente ejemplo: si yo quisiera que todos los títulos h2 sean de color azul, lo declataría de la siguiente manera en el css

```
<head>
<title>Primer ejemplo de CSS</title>
<style>
h2 {
    color: blue;
}
</style>
</head>
```

Entonces, cada vez que se abra el documento y reconozca los títulos h2, el navegador le dará el color azul.

# Ejemplo 2 - Referencia al documento css

La segunda opción, y la que vamos a estar usando en la gran mayoría de los casos, es hacer referencia al archivo que contenga el estilo y tiene la terminación de tipo de archivo .css

Se realiza de la siguiente manera: para este ejemplo, hemos creado el achivo estilos.css y dentro del archivo copiamos lo que estaba en el primer ejemplo de la referencia a la etiqueta h2 para que sea de color azul, y quedó de la siguiente manera:

```
h2 {
    color: blue;
}
```

Ahora, en nuestro head hacemos la referencia al archivo estilos.css a través de la etiqueda link con su atributo rel en stylesheet y hace la referencia a la dirección del archivo en href con su nombre para ser utilizado en el documento. Aquí va:

```
<head>
    <title>Segundo ejemplo CSS</title>
    <link rel="stylesheet" href="estilos.css">
</head>
```

Como notarán, ocurre lo mismo que en el primer ejemplo que los títulos h2 están de color azul.

En la siguiente lección continuaremos trabajando bajo el archivo estilos.css, ya que es la práctica más recomendada en diseño web para la reutilización de código y diseño unificado dentro del mismo sitio web.