# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline1
----------

Underline 2
-----------
-----------

# Formatos de enfasis
- Formato *itálica* de la primera forma.
- Formato _itálica_ de la segunda forma.
- Formato **negrita** de la primera forma.
- Formato __negrita__ de la segunda forma.
- Formato ~~subrayado~~, formato normal.
- Combinado de *__todo__*

# Listas
## Ordernada
1. Esto es un objeto.
2. Esto es un objeto.
3. Esto es un objeto.

## Desordenadas
- Esto es un objeto.
- Esto es un objeto.
- Esto es un objeto.

# Links
- [Esto es un link en Makdown](http://www.google.es)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://www.webbyline.com/site/wp-content/plugins/screets-lc/assets/img/night-bird-logo-200px.png)

# Code Snippets
- Jighlightjs es la libreria que vamos a utilizar.
- Resaltar código en JSON.
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
- Resaltar código en JSON.
```JAVASCRIPT
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

# Tabla
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Raul | Jiménez | 273687983W |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es una cita que no se relaciona con la cita anterior con dos enter por medio.
> Esto es otra cita.

# Lineas divisoras
Esto es un texto que será dividido por guiones, se debe de separar por dos enter.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.

___


