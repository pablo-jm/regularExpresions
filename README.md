¿Qué son las expresiones regulares?
Son patrones de texto utilizados para buscar, analizar y manipular cadenas de caracteres.

¿Qué problema resuelven?
   - Comprobar si un string tiene un formato indicado
      Validar correos electrónicos, números de teléfono, contraseñas seguras, fechas, etc.

   - Encontrar coincidencias (matches) dentro de un string
      Extraer datos relevantes, buscar palabras clave, variaciones del texto, detectar patrones repetidos, etc.

¿Por qué es importante conocerlas?
Porque permiten manejar y manipular texto de manera eficiente, lo cual es una habilidad clave en muchas áreas de desarrollo y análisis de datos.

Ejercicio 1:
Escribe las expresiones regulares correctas para validar:
un email → /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/
un número de teléfono (español) → /^(\+34\s?)?(\d{9}|\d{3}\s\d{3}\s\d{3})$/
un DNI → /^\d{8}[A-Z]$/
