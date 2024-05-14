# Organizador de Archivos

Este script está diseñado para organizar archivos dentro de una estructura de directorios en función de ciertos criterios. Mueve archivos a carpetas de destino específicas dependiendo de sus nombres y atributos.

## Funcionalidad

El script realiza las siguientes tareas:

- Categoriza archivos en dos grupos principales: archivos que coinciden con un cierto patrón y archivos que no.
- Los archivos que coinciden con el patrón se mueven a una carpeta de destino, mientras que los archivos que no coinciden se mueven a otra.
- Si un archivo con el mismo nombre ya existe en la carpeta de destino, el script renombra el archivo para evitar duplicaciones.
- El script puede ejecutarse de manera recursiva para procesar subdirectorios dentro de la carpeta de origen especificada.

## Uso

Para usar el script, sigue estos pasos:

1. Coloca el script (`script.py`) en el directorio que contiene los archivos que deseas organizar.
2. Ejecuta el script escribiendo `python script.py`.
3. El script organizará los archivos según los criterios especificados.

## Posibles Mejoras

Aquí hay algunas mejoras potenciales que podrían realizarse para mejorar la funcionalidad del script:

- Implementar soporte para criterios adicionales de organización de archivos.
- Agregar manejo de errores y registro para proporcionar una mejor retroalimentación al usuario.
- Refactorizar el código para mejorar la legibilidad y mantenibilidad.
- Proporcionar opciones de configuración mediante argumentos de línea de comandos o un archivo de configuración.

¡Siéntete libre de contribuir al proyecto enviando solicitudes de extracción o sugiriendo nuevas funciones!
