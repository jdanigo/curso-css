# Curso de CSS

CSS es un lenguaje de hojas de estilo en cascada, usado mayormente para dar estilos a documentos HTML, CSS se basa en reglas de estilos para cambiar visualmente la apariencia de los antes nombrados documentos HTML, esto incluye diseño, colores, animaciones, fuentes y entre otros elementos visuales.

Como bien sabemos que CSS se basa en reglas de estilos, tenemos una serie de propiedades que permiten cambiar el comportamiento visual.

## Propiedades mas usadas en CSS

- background-color: Establece el color de fondo de un elemento.
- color: Establece el color del texto de un elemento.
- font-size: Establece el tamaño de fuente del texto de un elemento.
- font-family: Establece la fuente de un elemento.
- padding: Establece el espacio entre el contenido de un elemento y su borde.
- margin: Establece el espacio entre los bordes de un elemento y los elementos circundantes.
- border: Establece el estilo, ancho y color del borde de un elemento.
- text-align: Establece la alineación horizontal del texto dentro de un elemento.
- display: Establece el tipo de pantalla de un elemento.
- width: Establece el ancho de un elemento.
- height: Establece la altura de un elemento.
- position: Establece la posición de un elemento.
- top, right, bottom, left: Establecen la posición de un elemento en relación a su contenedor.
- float: Establece el flujo del contenido de un elemento.
- clear: Establece el comportamiento de un elemento cuando se encuentra en una línea con otros elementos flotantes.
- opacity: Establece la opacidad de un elemento.
- transition: Establece la duración, el tiempo de espera y la función de transición de una animación.
- text-decoration: Establece la decoración del texto, como subrayado, tachado, etc.
- text-transform: Establece la transformación del texto, como mayúsculas o minúsculas.
- text-shadow: Establece una sombra alrededor del texto.
- box-shadow: Establece una sombra alrededor de un elemento.
- border-radius: Establece la curvatura de las esquinas de un elemento.
- outline: Establece una línea de contorno alrededor de un elemento.
- background-image: Establece una imagen de fondo de un elemento.
- background-size: Establece el tamaño de la imagen de fondo de un elemento.
- background-position: Establece la posición de la imagen de fondo de un elemento.
- background-repeat: Establece la repetición de la imagen de fondo de un elemento.
- transform: Establece transformaciones en un elemento, como rotación, escala, etc.
- transition: Establece una transición animada en un elemento.
- cursor: Establece el tipo de cursor que aparece al pasar el ratón por encima de un elemento.
- box-sizing: Establece el modelo de caja de un elemento, como content-box o border-box.
- overflow: Establece el comportamiento de un elemento cuando su contenido desborda su espacio.
- z-index: Establece el orden de apilamiento de los elementos en una página.
- line-height: Establece la altura de línea de texto dentro de un elemento.
- letter-spacing: Establece la distancia entre caracteres dentro del texto.
- word-spacing: Establece la distancia entre palabras dentro del texto.
- text-indent: Establece la sangría del primer renglón de un párrafo.
- text-overflow: Establece el comportamiento de un texto cuando sobrepasa los límites de su contenedor.
- white-space: Establece cómo el espacio en blanco debe ser manejado dentro de un elemento.
- vertical-align: Establece la alineación vertical de un elemento en relación con su contenedor.
- position: Establece el tipo de posicionamiento de un elemento.
- visibility: Establece la visibilidad de un elemento.
- opacity: Establece la transparencia de un elemento.
- flex: Establece el diseño flexible para un conjunto de elementos.
- grid: Establece el diseño en cuadrícula para un conjunto de elementos.
- justify-content: Establece la alineación horizontal de los elementos dentro de un contenedor.
- align-items: Establece la alineación vertical de los elementos dentro de un contenedor.
- align-self: Establece la alineación vertical de un elemento dentro de un contenedor.
- gap: Establece el espacio entre filas y columnas en un diseño en cuadrícula.
- animation: Establece una animación para un elemento.


## ¿Que son los selectores ?

Los selectores son patrones que se utilizan para seleccionar uno o más elementos en una página web y aplicarles estilos en CSS. Los selectores pueden ser de tipo, de clase, de ID, de descendencia, de hermano adyacente, de hermano general, etc. Ejemplo: h1 selecciona todos los encabezados de nivel 1 en la página.

## ¿Que son los pseudoselectores ?

Los pseudoselectores son palabras clave que se utilizan para aplicar estilos a partes específicas de un elemento, como la primera letra (::first-letter) o la primera línea (::first-line) de un párrafo. Los pseudoselectores se agregan después del selector y se escriben con dos puntos dobles ::. Ejemplo: p::first-letter selecciona la primera letra de todos los párrafos en la página.

## ¿Que son las pseudoclases ?

Las pseudoclases son palabras clave que se utilizan para aplicar estilos a elementos que están en un estado específico, como cuando el usuario mueve el cursor sobre un enlace (:hover) o cuando un elemento está activo (:active). Las pseudoclases se agregan después del selector y se escriben con dos puntos :. Ejemplo: a:hover selecciona todos los enlaces cuando el usuario mueve el cursor sobre ellos.

## ¿Que son las clases ?

Las clases son atributos que se agregan a los elementos HTML para identificarlos y darles estilo en CSS. Las clases se escriben con un punto . seguido del nombre de la clase. Ejemplo: .texto-rojo selecciona todos los elementos con la clase texto-rojo


## Tipos de selectores

### Selectores comunes

- Selector universal (*): selecciona todos los elementos de la página.
- Selector de tipo (elemento): selecciona todos los elementos del tipo especificado, por ejemplo p para párrafos.
- Selector de clase (.clase): selecciona todos los elementos que tienen la clase especificada.
- Selector de ID (#id): selecciona el elemento con el ID especificado.
- Selector de descendiente (espacio): selecciona elementos que son descendientes de otro elemento, por ejemplo div p selecciona todos los párrafos dentro de un div.
- Selector de hijo (>): selecciona elementos que son hijos directos de otro elemento, por ejemplo div > p selecciona todos los párrafos que son hijos directos de un div.
- Selector de hermano adyacente (+): selecciona el primer elemento que sigue inmediatamente al otro elemento, por ejemplo h1 + p selecciona el primer párrafo que sigue inmediatamente a un encabezado de nivel 1.
- Selector de hermano general (~): selecciona todos los elementos que siguen al otro elemento, por ejemplo h1 ~ p selecciona todos los párrafos que siguen a un encabezado de nivel 1.

### Selectores mas complejos

- Selector de atributo : 
selecciona elementos que tienen un atributo específico
Ej: [atributo]

Un atributo específico con un valor específico 
Ej: [atributo=valor]

Que comienza
Ej: [atributo^=valor]

Que termina
Ej: [atributo$=valor]

Que contiene un valor específico
Ej: [atributo*=valor]


Ejemplo: 

Usamos el tipo de selector atributo
```
input[name="apellidos"] {
  margin-bottom: 1rem;
  border: red;
}

input[type="text"] {
  ...
}

input[class="micss"] {
  ...
}

[name="nombres"] {
    border: 3px solid red;
}
```

El siguiente ejemplo es un poco mas complejo, selecciona todos los enlaces que no tienen el atributo href

```
a:not([href]) { color: purple; }
```

El siguiente ejemplo, muestra de color azul todos los links que apunten a determinada url

```
a[href="https://google.com"] { color: blue; }
```



- Selectores de pseudo-elementos (::before, ::after, ::first-line, ::first-letter, ::selection): selecciona elementos y partes específicas de elementos que no existen en el árbol DOM, como el contenido antes o después de un elemento, la primera línea o la primera letra de un elemento, o el texto seleccionado por el usuario.

A continuación un ejemplo de como utilizar before, after, selection

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Ejemplo Pseudo-elementos y Pseudo-clases</title>
    <style>
      /* Pseudo-elemento ::before */
      h1::before {
        content: "Antes de: ";
        color: blue;
      }

      /* Pseudo-elemento ::after */
      h1::after {
        content: "Después de.";
        color: red;
      }

      /* Pseudo-clase ::selection */
      p::selection {
        background-color: yellow;
      }
    </style>
  </head>
  <body>
    <h1>Título principal</h1>
    <p>Este es un párrafo de ejemplo que muestra el uso de los pseudo-elementos y pseudo-clases en CSS.</p>
  </body>
</html>

```




- Selectores de pseudo-clases (:hover, :active, :focus, :visited, :nth-child(), :nth-of-type(), :not(), :empty, :checked, :disabled, :enabled, :target, :lang()): selecciona elementos en función de su estado o posición en la página, como cuando el usuario mueve el cursor sobre un elemento (:hover), cuando un enlace ha sido visitado (:visited), o cuando un elemento es el tercer hijo de su padre (:nth-child(3)).


Ejemplo: 

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Ejemplo de Pseudo-clases en CSS</title>
    <style>
      /* Pseudo-clase :hover */
      a:hover {
        color: red;
      }

      /* Pseudo-clase :active */
      button:active {
        background-color: blue;
      }

      /* Pseudo-clase :focus */
      input:focus {
        border: 2px solid green;
      }

      /* Pseudo-clase :visited */
      a:visited {
        color: gray;
      }

      /* Pseudo-clase :not */
      p:not(.importante) {
        color: gray;
      }

      /* Pseudo-clase :checked */
      input[type="checkbox"]:checked + label {
        text-decoration: line-through;
      }

      /* Pseudo-clase :disabled */
      input[type="text"]:disabled {
        background-color: gray;
      }

      /* Pseudo-clase :enabled */
      input[type="text"]:enabled {
        background-color: white;
      }

      /* Pseudo-clase :target */
      #seccion1:target {
        background-color: yellow;
      }
    </style>
  </head>
  <body>
    <a href="#">Enlace</a>
    <button>Botón</button>
    <br>
    <input type="text" disabled>
    <input type="text" enabled>
    <br>
    <input type="checkbox" id="check1"><label for="check1">Opción 1</label>
    <input type="checkbox" id="check2"><label for="check2">Opción 2</label>
    <br>
    <p>Este párrafo no es importante.</p>
    <p class="importante">Este párrafo es importante.</p>
    <br>
    <section id="seccion1">
      <h2>Sección 1</h2>
      <p>Esta es la sección 1.</p>
    </section>
    <section id="seccion2">
      <h2>Sección 2</h2>
      <p>Esta es la sección 2.</p>
    </section>
  </body>
</html>
```


## Tipos de posiciones

- Posicionamiento relativo : El posicionamiento relativo permite desplazar un elemento de su posición original sin afectar la posición de los demás elementos en la página.

Ejemplo: 

```
div {
  position: relative;
  top: 20px;
  left: 30px;
}
```

En este ejemplo, position: relative establece el posicionamiento relativo del elemento, y top y left desplazan el elemento 20 píxeles hacia abajo y 30 píxeles hacia la derecha, respectivamente.


- Posicionamiento absoluto
El posicionamiento absoluto permite fijar un elemento en una posición específica de la página, independientemente de la posición de otros elementos.

Ejemplo: 

```
div {
  position: absolute;
  top: 50px;
  left: 50px;
}
```

En este ejemplo, position: absolute establece el posicionamiento absoluto del elemento, y top y left lo fijan a 50 píxeles desde la parte superior y la izquierda de la página, respectivamente.

- Posicionamiento fijo
El posicionamiento fijo permite fijar un elemento en una posición específica de la ventana del navegador, incluso cuando se desplaza la página.

```
div {
  position: fixed;
  top: 0;
  left: 0;
}
```

En este ejemplo, position: fixed establece el posicionamiento fijo del elemento, y top y left lo fijan en la esquina superior izquierda de la ventana del navegador.

- Posicionamiento pegajoso
El posicionamiento pegajoso permite fijar un elemento en una posición específica hasta que alcanza una cierta posición de desplazamiento, momento en el cual se convierte en posicionamiento relativo.

```
div {
  position: sticky;
  top: 50px;
}
```

En este ejemplo, position: sticky establece el posicionamiento pegajoso del elemento, y top lo fija a 50 píxeles desde la parte superior de la ventana del navegador hasta que se alcanza un punto de desplazamiento específico.

**NOTA:**

la propiedad position funciona en conjunto con otras propiedades CSS como top, bottom, left, y right para determinar la posición exacta del elemento en la página.


## Tipos de display

- block

La propiedad `display: block;` se utiliza para crear un elemento que ocupa todo el ancho disponible y se muestra en una línea separada.

```css
div {
  display: block;
}
```

En este ejemplo, `div` se muestra como un bloque, ocupando todo el ancho disponible y colocándose en una línea separada.

- inline

La propiedad `display: inline;` se utiliza para crear un elemento que no ocupa todo el ancho disponible y se muestra en la misma línea que el texto.

```css
span {
  display: inline;
}
```

En este ejemplo, `span` se muestra en línea con el texto y no ocupa todo el ancho disponible.

- inline-block

La propiedad `display: inline-block;` se utiliza para crear un elemento que se muestra en línea, pero también puede tener un ancho y un alto definidos.

```css
button {
  display: inline-block;
  width: 100px;
  height: 50px;
}
```

En este ejemplo, `button` se muestra en línea con el texto, pero también tiene un ancho y un alto definidos.

- flex

La propiedad `display: flex;` se utiliza para crear un contenedor flexible para elementos secundarios.

```css
.container {
  display: flex;
  justify-content: space-between;
}
```

En este ejemplo, `container` se define como un contenedor flexible y se establece la distribución del espacio entre los elementos secundarios con la propiedad `justify-content: space-between;`.

**NOTA:**
La propiedad `display` es muy versátil y puede utilizarse para controlar el tipo de caja que se utiliza para presentar un elemento, como bloques, líneas en línea o contenedores de diseño.