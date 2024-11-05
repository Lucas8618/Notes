Lenguaje MarkDown:
Objetivo: proporcionar una herramienta para documentar cogigo, o aspectos tecnicos para compartirlos o tenerlos de referencias en mi Git u otra plataforma.

MarkDown es un lenguaje de mercado ligero creado en 2004 por Jhon Gruber, trata de conseguir la maxima legibilidad y facilidad de publicación tanto en la forma de entrada como de salida, inspirandose en muchas convenciones existentes para marcar mensajes de correo electronico como texto plano.

El objetivo de su creador fue hacer que la gente pudiera escribir usando un formato de texto plano facil de leer, fail de escribir y con posibilidad de convertir su documento en un HTML valido.

Contener sintaxis MarkDown  [Parrafo 1...]

Parrafo 1...
Lorem Ipsum es simplemmente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estandar de las industrias desde el año 1500.

_Cursiva_

**Negrita**

**_Cursiva y negrita_**

_~Cursiva y tachado~_

**~Negrita y tachado~**

**_~Cursiva negrita y tachado~_**


Encabezado

# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3

Divisiones

Un bloque de contenido
---
Este es otro bloque de contenido

Listas
Podemos usar tanto listas ordenadas como listas desordenadas.

1. HTML
1. css
1. javascrip
1. ajax
1. json

- HTML
- css
- javascript
- ajax
- json

citas
Podemos dar formato de una cita a un texto anteponiendo a la linea de texto un caracter de mayor que (>)

> La IA en el futuro remplazara muchas profeciones

> ChatGPT debe potenciar mi aprendizaje, no suprimir mi estado autodidactico

Enlaces

[Youtube][https://youtube.com]
[Google][https://google.com]

Imagenes

[texto alternativo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwall.alphacoders.com%2Fbig.php%3Fi%3D967401&psig=AOvVaw3cjkswFTGodwtS-6-87hrX&ust=1730922682898000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCIjeitT7xYkDFQAAAAAdAAAAABAE)

Tablas

| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
|A          |1          |A1         |
|B 	        |2          |B2         |


Codigo
Podemos dar formato de codigo a un texto, para ello se usa el ascento grave ("`")

Este es un Cogido en linea.

En javascrpit una variable se define asi
`let saludo="Hola Mundo"`

```js
let estudiante="Juan Pérez";
let edad="19 años";
let isEstudiante="true";
let calificacion=92.3;

console.log("Estudiante: "+estudiante);
console.log("Edad: "+edad);
console.log("Estudia: "+isEstudiante);
console.log(typeof calificacion);
console.log(`El promedio global del estudiante es ${calificacion}`);
```