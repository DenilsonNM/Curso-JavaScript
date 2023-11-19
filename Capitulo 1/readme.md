# JavaScript
[Curso de JAVASCRIPT desde CERO (Completo) - Nivel JUNIOR por Soy Dalto](https://youtu.be/z95mZVUcJ-E?si=CQWAuznxkiIQ2JwP)

# Capitulo

# Enlazar JavaScript a otra tecnología
## En linea HTML
```
<!DOCTYPE html>
...
<h1 onclick="alert('Esta es una alerta de JS en linea HTML')">haz click sobre este texto</h1>
...
```
## En etiqueta <Script>
```
<!DOCTYPE html>
...
<script type="text/javascript">
  alert('esta es una alerta usando etiqueta Script')
</script>
...
```

## En un archivo aparte codigo.js
index.html
```
<!DOCTYPE html>
...
<script src="codigo.js"></script>
...
```
codigo.js
```
alert('esta es una alerta usando etiqueta Script y un archivo JS')
```
## En un Require
```
```
---
# Variables
espacios que guardamos en memoria y que contienen un dato que puede cambiar
## Ejemplo
`recipiente` es la variable, `"agua"` es un tipo de dato de texto que esta adentro. Usando la función `alert()` mostramos en forma de alerta, lo que esta dentro de `recipiente`
```
recipiente = "agua";
alert(recipiente)
```

## Tipos de datos

### Cadena de texto
```
"hola soy una cadena de texto"
'hola soy una cadena de texto'
`hola soy una cadena de texto`
```
### Número
```
1
20
3.5
40000
...
```
### Booleano
```
true
1
false
0
```
### Especiales
donde la variable no esta definida o hay un error
- Undefined
- Null
- NaN

## Formas de declarar variables y su scope (ámbito o alcance)

### - var
Para variables **publicas/globales**
```
var numero;
numero = 31;
alert(numero);
```
muestra el numero en forma de alerta
```
var numero = 31;
alert(numero);
```
otra forma de declaración y también muestra el numero en forma de alerta
```
var numero = 31;
numero = 10;
alert(numero);
```
se modifica `numero` y muestra el nuevo valor
```
var numero;
alert(numero);
```
muestra el tipo de dato `undefined` porque `numero` no esta declarada/no tiene un valor

### - let
Para variables dentro de un **bloque**; fuera de este, la variable no existe
```
let numero;
numero = 31;
alert(numero);
```
muestra el numero en forma de alerta
```
let numero = 31;
alert(numero);
```
otra forma de declaración y también muestra el numero en forma de alerta
```
let numero = 31;
numero = 10;
alert(numero);
```
se modifica `numero` y muestra el nuevo valor
```
let numero;
alert(numero);
```
muestra el tipo de dato `undefined` porque `numero` no esta declarada/no tiene un valor

### - const
Para variables que permanecen con su valor **definido/no cambian**
```
const saludo = "hola";
alert(saludo);
```
nos muestra una alerta con el valor la constante
```
const saludo = "hola";
saludo = "adios"
alert(saludo);
```
nos muestra un error en consola, porque las variables que son declaradas como `const` no deben ni pueden cambiarse después de declararse
```
const saludo;
saludo = "adios";
alert(saludo);
```
nos muestra un error en consola, porque las variables que son declaradas como `const` solo se pueden inicializar cuando se declaran y NO después como en `let`

### Multiples variables en una linea
```
let numero, numero2, numero3;

numero = 1;
numero2 = 2;
numero3 = 3;

alert(numero);
alert(numero2);
alert(numero3);
```
nos muestra los valores de cada variable en forma de alerta, uno después de otro
```
let numero = 1, numero2 = 2, numero3 = 3;

alert(numero);
alert(numero2);
alert(numero3);
```
otra forma de declarar y nos muestra los valores de cada variable en forma de alerta, uno después de otro

### - Null
variable nula, se declara para indicar que no es `undefined` y que tendrá el valor de **nulo**
```
let numero = null;

```
### - NaN

## Hoisting
formas de ejecución y de escritura del código donde se pueden ejecutar antes o después de una declaración


