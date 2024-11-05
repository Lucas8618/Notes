```js
```

<!-- Esto es para crear comentarios -->
<!-- Para la creacion e impresion de lineas se usa el comando console.log(" ") -->
```js
console.log("Bienvenido al mundo de la programación FrontEnd con JavaScript");

console.log("Esta es otra linea" + "Y se conectan con el simbolo +");
```

<!-- Ahora vamos a trabajar con declaraciones de variables -->
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

<!-- JavaScript es un lenguaje debilmente tipeado, esto significa que
no es estricto en declararación de tipos de datos. Es decir que no 
fuerza a que inicialmente digas el tipo de dato de la variable. Y
esta puede cambiar en el transcurso de lógica por otro tipo de
datos segun sea la necesidad -->

```js
let num1=50;
let num2=25;
let suma=num1 + num2
let resta=num1-num2;
let mult=num1*num2;
let divicion=num1/num2;

console.log("Suma= "+suma);
console.log("Resta= "+resta);
console.log("Multiplicación= "+mult);
console.log("Divición= "+divicion);

let val1;
let val2;
    val1=prompt("Ingresa el primer numero");
    val2=prompt("Ingresa el segundo numero");

    num1=parseInt(val1);
    num2=parseInt(val2);

    console.log("La suma es "+ (num1 + num2))
```

<!-- Estructuras de control
(if, if else, switch)
Estas estructuras permiten ejecutar bloques de codigo
segun el resultado de una conducta -->
```js
let EdadA=17;

//Estructura de control usando if
if(EdadA >= 18){
    console.log("Eres un adulto y debes registrarte en el SAT")
}

//Estructura de control usando if/else
if(EdadA >= 18){
    console.log("Eres un adulto y debes registrarte en el SAT")
}else{
    console.log("Todabia no pagaras impuestos")
}
```

<!-- Opreadores de control -->

```js
//1.- Operadores aridmeticos
let a=10;
let b=5;
console.log(a + b); //suma
console.log(a - b); //resta
console.log(a * b); //multiplicacion
console.log(a / b); //division
console.log(a % b); //modulo

//operadores de asignacion
let X=10;
X += 5; //X=15
X -= 2; //X=13
X *= 3; //X=39
X /= 3; //X=13
X %= 5; //X=3

//operadores de comparacion
let A=5; let B=`5`;
console.log(A == B); //compara solo el valor
console.log(A === B); //compara el valor y el tipo
console.log(A != B);
console.log(A !== B);
console.log(A > 3);
console.log(A <= 5);

//Estructuras de control if/else anidado.
let Cargo=200;

    if(Cargo >=100 && Cargo <=150){
        alert("Impuesto bajo");
    }else if(Cargo >=151 && Cargo <=200){
        alert("Revisar el tabulador")
    }
```