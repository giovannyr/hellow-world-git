# cabecera h1
## cabecera h2
### cabecera h3
#### cabecera h4
##### cabecera h5
###### cabecera h6

Underline 1
-----------

Underline2
==========

# Formatos de enfasis
- formato *italica* primera forma
- formato _italica_ segunda forma
- formato **bold o strong** primera forma
- formato __bold o strong__ segunda forma
- formato ~~tachado~~
- aqui podemos usar *italica*, **bold** y ~~tachado~~ en una misma linea.

# Listas
### Lista ordenada
1. item
2. item
3. item

### Lista desordenada
- item
- item
- item

# Links
- <a href="http://www.google.com">Esto es un link en HTML</a>
- [Esto es un link en MARDOWN](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GitHub](https://live.mrf.io/statics/i/ps/www.muylinux.com/wp-content/uploads/2017/06/github.png?width=1200&enable=upscale)

# Code Snipets
[*ver [highlight js](https://highlightjs.org/) | [highlight js - demo](https://highlightjs.org/static/demo/)*]

Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Codigo en Javascript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Poder |
| - | - | -
| Bruce | Wayne | N/A |
|Tony|Stark|N/A

# Citas
Esto es un texto referente a una cita de Linus Torvalds

> “La inteligencia es la habilidad de evitar hacer el trabajo, consiguiendo el trabajo hecho.”

con doble salto de linea se termina la cita.
> esto es otra cita

# Lineas divisoras
texto que sera dividido

---
otro texto dividido
 
*** 
otra forma de dividir

___

# Saltos de linea
Primer parrafo.

Segundo parrafo.

Tercer parrafo.
- item 1
