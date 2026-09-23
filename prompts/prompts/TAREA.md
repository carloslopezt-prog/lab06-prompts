# Tarea: Mi prompt profesional
 
## Funcionalidad elegida

Formulario de registro de usuarios en Java Swing.

## Version 1: prompt basico

Hazme un formulario de registro de usuarios en Java.
Qué cambió: Creación del prompt inicial sin detalles.

Por qué: Para evaluar la respuesta base que genera la IA con información mínima.

Qué mejoró: Generó un código básico en Java, pero mezcló componentes, usó un diseño genérico y no incluyó validaciones ni estructura clara.

## Version 2

 Actúa como desarrollador Java. Crea un formulario de escritorio para el registro de usuarios utilizando Java Swing. El usuario debe ingresar su Nombre, Correo y Contraseña.

 Qué cambió: Se agregó un ROL (desarrollador Java), la tecnología específica (Java Swing) y los campos requeridos (Nombre, Correo, Contraseña).

Por qué: Para acotar la respuesta y evitar que la IA elija tecnologías al azar o cree campos innecesarios.

Qué mejoró: El código ahora usa Swing y genera los campos solicitados de forma más ordenada. Sin embargo, falta validación de datos y el formato de entrega no está especificado.

## Version 3: prompt final

Actúa como desarrollador Java experto en interfaces de usuario. Crea un formulario de registro de usuarios utilizando Java Swing para una aplicación de escritorio.

Campos requeridos:
- Nombre de usuario
- Correo electrónico
- Contraseña

Restricciones:
- No uses librerías externas (solo componentes nativos de Java Swing y AWT).
- Valida que el correo contenga el símbolo '@'.
- Valida que la contraseña tenga al menos 8 caracteres.
- Muestra las alertas de éxito o error utilizando JOptionPane.

Formato de respuesta:
1. Explica brevemente los componentes principales utilizados.
2. Muestra el código Java completo y organizado en una sola clase ejecutable.

Qué cambió: Se definieron los 5 componentes del prompt (Rol, Instrucción, Contexto, Ejemplo implícito de validación y Formato) además de restricciones explícitas.

Por qué: Para evitar que la IA incluya librerías pesadas y garantizar un código listo para ejecutar con validaciones reales.

Qué mejoró: La IA entregó una explicación clara de la estructura antes del código, incluyó validaciones con JOptionPane y el código funcionó correctamente al compilarse.
 
## Componentes del prompt final

Componente,Texto de mi prompt
Rol,Actúa como desarrollador Java experto en interfaces de usuario.
Instrucción,Crea un formulario de registro de usuarios utilizando Java Swing... Valida que el correo contenga '@' y la contraseña 8 caracteres.
Contexto,"Para una aplicación de escritorio que requiere registrar Nombre, Correo y Contraseña."
Ejemplo,Valida que el correo contenga el símbolo '@' y que la contraseña tenga al menos 8 caracteres (reglas específicas de formato).
Formato,Explica primero los componentes principales y luego muestra el código organizado en una sola clase ejecutable.
 
## Evaluacion del resultado

Aquí tienes las dos tablas con exactamente esa estructura para que las puedas copiar y pegar directamente en tu archivo `TAREA.md`:

### Componentes del prompt final

| Componente | Texto de mi prompt |
| --- | --- |
| Rol | Actúa como desarrollador Java experto en interfaces de usuario. |
| Instruccion | Crea un formulario de registro de usuarios utilizando Java Swing. Valida que el correo contenga '@' y la contraseña tenga al menos 8 caracteres. |
| Contexto | Para una aplicación de escritorio que requiere registrar Nombre de usuario, Correo electrónico y Contraseña. |
| Ejemplo | Muestra alertas con JOptionPane (ejemplo: "Error: El correo debe contener @"). |
| Formato | Explica primero los componentes principales y luego presenta el código completo en una sola clase ejecutable. |

---

### Evaluación del resultado

| Criterio | Cumple (Sí / No) |
| --- | --- |
| ¿Usa Java Swing sin librerías externas? | Sí |
| ¿Contiene los campos Nombre, Correo y Contraseña? | Sí |
| ¿Valida las reglas solicitadas con JOptionPane? | Sí |
| ¿Muestra la explicación antes del código? | Sí |
 
## Errores que evite

Ser demasiado general: Evité pedir simplemente "código para un registro", especificando la tecnología (Java Swing), el entorno (escritorio) y los campos exactos.

No indicar restricciones: Evité que la IA agregara librerías externas o complejas agregando la restricción explícita de usar solo componentes nativos de Java AWT/Swing.