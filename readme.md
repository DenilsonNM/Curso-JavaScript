# JavaScript
[Curso de JAVASCRIPT desde CERO (Completo) - Nivel JUNIOR por Soy Dalto](https://youtu.be/z95mZVUcJ-E?si=CQWAuznxkiIQ2JwP)
# ¿Que es?
- ECMAScript (tecnología en la que se basó JavaScript)
- Lenguaje de programación (instrucciones a una maquina)
- Lenguaje Interpretado (Todo el código no pasa por compilador, se ejecuta en tiempo real y por el interprete)
- Orientado a objeto (su estructura abarca los conceptos: clases, herencia, polimorfismo, etc)
- Lenguaje imperativo (Las instrucciones van de linea en linea ejecutándose)
- Lenguaje "case sensitive" (sensible a mayúsculas y minúsculas)
- Basado en prototipos/ instancias/ Clases (basados en otros objetos previamente construidos por el equipo desarrollador del lenguaje)
- Tipado débil (el valor de las variables pueden cambiar o sobrescribirse de tipos de datos distintos)
- Lenguaje Dinámico (el dato se ajusta a la variable)

# ¿Para que se usa?
- Dinamismo en sitios web (mas común, y del lado del cliente)
- Servidor en NodeJS
- Tecnologías Frontend (Angular, React, Vue.js, etc)
## Otros usos
- IA (raro)
- Placas electrónicas (Jhonny Five)
- Mobile Apps
- Desktop Apps

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
strg = "hola soy una cadena de texto"
strg = 'hola soy una cadena de texto'
strg = `hola soy una cadena de texto`
```
### Número
```
num = 1
num = 20
num = 3.5
num = 40000
...
```
### Booleano
```
bol = true
bol = 1
bol = false
bol = 0
```
### Especiales
donde la variable no esta definida o hay un error
- undefined
- null
- nan

## Formas de declarar variables

### var
Para variables publicas/globales
```
```
### let
Para variables dentro de un bloque
```
let numero;
numero = 31
alert(numero)
```
muestra el numero en forma de alerta
```
let numero = 31;
alert(numero)
```
otra forma de declaración y también muestra el numero en forma de alerta
```
let numero = 31;
numero = 10
alert(numero)
```
se modifica `numero` y muestra el nuevo valor
```
let numero;
alert(numero)
```
muestra el tipo de dato `undefined` porque `numero` no esta declarada/no tiene un valor
### const
Para variables que permanecen con su valor definido/no cambian
```
const saludo = "hola"
alert(saludo)
```
nos muestra una alerta con el valor la constante
```
const saludo = "hola"
saludo = "adios"
alert(saludo)
```
nos muestra un error, porque las variables que son declaradas como `const` no deben ni pueden cambiarse después de declararse


