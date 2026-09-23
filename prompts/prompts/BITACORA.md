# Bitacora de prompts
 
Laboratorio 06: Fundamentos de Ingenieria de Prompts.
 
Herramienta de IA usada: (escribe aqui cual usaste)
 
## Ejercicio 2: Tokens y ventana de contexto
 
## Ejercicio 3: Temperatura

## Ejercicio 4: Prompt vago vs estructurado
 
## Ejercicio 5: Anatomia de un prompt
 
## Ejercicio 6: Del prompt basico al profesional

| Texto | Caracteres | Tokens |
|-------|------------|--------|
| Los estudiantes programan en Java. |7|35|
| The students program in Java. |6|29|
| desafortunadamente |4|18|

La IA no reconocio mi pregunta cuándo inicie una nueva conversación.
Lo que significa que no guarda inormación o no la registre.

## Ejercicio 7: Temperatura y %

| Temperatura | % de BiblioTec | Nombres en los 5 intentos |
|-------------|----------------|---------------------------|
| 0 |100%|BiblioTec|
| 0.5 |65.3%|BiblioTec, BiblioTec, BiblioTec, LibroYa, BiblioTec|
| 1 |44.5%|LibroYa, BiblioTec, LibroYa, BiblioTec, BiblioTec|
| 1.8 |32.2%|BiblioTec, BiblioTec, PrestaLibro, NubeDeTinta, BiblioTec|

Al aumentar la temperatura, los nombres se vuelven más variados y menos repetitivos porque el modelo explora opciones con menor probabilidad.

## Ejercicio 8: Criterios 

| Criterio | Prompt vago | Prompt estructurado |
|----------|-------------|---------------------|
| Menciona el objetivo del sistema |Si|Si|
| Menciona a los usuarios principales |Si|Si|
| Tiene exactamente 3 funcionalidades |No|Si|
| Esta en 3 parrafos |No|Si|
| Lo usaria en un informe real |No|Si|
## Ejercicio 9: Texto de mi prompt
| Componente | Texto de mi prompt |
|------------|--------------------|
| Rol |Actua como desarrollador Java.|
| Instruccion |Crea un programa en Java para gestionar los productos de una tienda usando una clase Producto con los atributos codigo, nombre, precio y stock.|
| Contexto |(No especificado explícitamente en el prompt original)|
| Ejemplo |(No especificado explícitamente en el prompt original)|
| Formato |Explica primero la estructura de la clase y luego presenta el codigo Java.|

```text
(pega aqui tu prompt profesional y la mejora que enviaste)
```
