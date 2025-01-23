# Log Visualizer

***Log Visualizer*** es una aplicación web pensada para facilitar
las tareas de desarrollo, permitiendo mostrar los logs generados
por un programa de una forma más amigable para el usuario y filtrarlos
según su tipo.

## Formato

Para que **Log Visualizer** funcione correctamente, es necesario que los logs
estén almacenados en *ficheros de texto plano* y tengan el siguiente formato:
```
    [marca de tiempo UTC]:[tipo]:[identificador]:[mensaje]
```
Actualmente, **Log Visualizer** permite los siguientes *tipos de registro*:
 - Error
 - Warning
 - Fatal
 - Debug
 - Trace
 - Info

El *identificador* puede tomar el valor `null`.

## CHANGELOG

 - [v0.0.4](CHANGELOG.md#004-2025-01-23)
 - [v0.0.3](CHANGELOG.md#003-2025-01-18)
 - [v0.0.2](CHANGELOG.md#002-2025-01-17)
 - [v0.0.1](CHANGELOG.md#001-2024-11-24)