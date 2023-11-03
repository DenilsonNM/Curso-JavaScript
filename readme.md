# JavaScript
[Curso de JAVASCRIPT desde CERO (Completo) - Nivel JUNIOR por Soy Dalto](https://youtu.be/z95mZVUcJ-E?si=CQWAuznxkiIQ2JwP)
# ¿Que es?
- ECMASCRIPT (tecnologia en la que se basó JavaScript)
- Lenguaje de programación (instrucciónes a una maquina)
- Lenguaje Interpretado (Todo el codigo no pasa por compilador, se ejecuta en tiempo real y por el interprete)
- Orientado a objeto (su estructura abajarca los conceptos: clases, herencia, polomorfismo, etc)
- Lenguaje imperativo (Las instrucciones van de linea en linea ejecutandose)
- Lenguaje "case sensitive" (sencible a mayusculas y minusculas)
- Basado en protipos/ instancias/ Clases (basados en otros onjetos previamente construidos por el equipo desarrollador del lenguaje)
- Tipado débil (el valor de las variables pueden cambiar o sobreescribirse de tipos de datos distintos)
- Lenguaje Dinamico (el dato se ajusta a la variable)

# ¿Para que se usa?
- Dinamismo en sitios web (mas comun, y del lado del cliente)
- Servidor en NodeJS
- Tecnologias Frontend (Angular, React, Vue.js, etc)
## Otros usos
- IA (raro)
- Placas electronicas (Jhonny Five)
- Mobile Apps
- Desktop Apps

# Enlazar JavaScript a otra tecnologia
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
`recipiente` es la variable, `"papel"` es un tipo de texto String que esta dentro, usando la funcion `alert()` mostramos en forma de alerta que es lo que esta dentro de `recipiente`
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
### Boleano
```
bol = true || bol = 1
bol = false || bol = 0
```
