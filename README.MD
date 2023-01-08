# Versión del curso
Versión actual: v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========
# Formatos de enfasis
- formato *itálica* de la primer forma

- formato _itálica_ de la segunda forma

- formato **bold o strong** de la primer forma
- formato __bold o strong__ de la primer forma

- formato ~~tachado~~, formato normal
- aquí podemos usar *formato itálico* pero también **bold** y ~~tachado~~

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
- <a href="http://google.com">Esto es un link en html</a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png){ width=50% }

# Code Snippets
Código en Javascript
```Javascript
// program that checks if the number is positive, negative or zero
// input from the user
const number = parseInt(prompt("Enter a number: "));

// check if number is greater than 0
if (number > 0) {
    console.log("The number is positive");
}

// check if number is 0
else if (number == 0) {
  console.log("The number is zero");
}

// if number is less than 0
else {
     console.log("The number is negative");
}
```

Código JSON

```JSON
{"menu": {
  "id": "file",
  "value": "File",
  "popup": {
    "menuitem": [
      {"value": "New", "onclick": "CreateNewDoc()"},
      {"value": "Open", "onclick": "OpenDoc()"},
      {"value": "Close", "onclick": "CloseDoc()"}
    ]
  }
}}

```
# Tablas
| Nombre | Apellido | Documento |
|--------| -------- | --------- |
| Maxi   | Burgos   | 35475969  |
| Tomas  | Tompson  | 34895985  |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior
> Esto es otra cita

# Lineas divisoras
Esto es un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos

***
Esto es otro texto dividido por guiones bajos

___

# Saltos de linea
Esto es nuestro primer párrafo.

Esto es nuestro segundo párrafo.

Esto es nuestro tercer párrafo.
- Lista