# Metro CDMX: Estaciones y Coordenadas

Hola !

Este repositorio contiene información sobre las estaciones del Metro de la Ciudad de México, incluyendo sus nombres y coordenadas geográficas (algunas aún faltan). El objetivo es facilitar el acceso a estos datos para cualquier persona interesada, así como permitir la actualización del estado de las estaciones según su disponibilidad.

## Archivos principales

- `Estaciones/estaciones.json`: Lista de estaciones del Metro CDMX. Cada estación tiene un nombre y un campo `available` que indica si está en funcionamiento (`true`) o en mantenimiento/cerrada (`false`). Puedes modificar este campo según la situación actual de cada estación.

- `Coordenadas/metro_coordenadas.json`: Archivo GeoJSON con las coordenadas de muchas estaciones del Metro. Incluye el nombre, las líneas que pasan por cada estación y su ubicación geográfica. Algunas estaciones aún no tienen coordenadas.

## ¿Cómo usar estos datos?

- Puedes consultar el archivo de estaciones para saber cuáles están disponibles en una fecha determinada.
- Si alguna estación entra en mantenimiento, puedes cambiar su campo `available` a `false` en el JSON.
- El archivo de coordenadas puede ser usado en aplicaciones de mapas, visualizaciones o para ubicar estaciones en el espacio geográfico.


## Contribuciones

Este proyecto es abierto y cualquier persona puede contribuir:
- Corrigiendo o agregando coordenadas faltantes.
- Actualizando el estado de las estaciones.
- Mejorando la estructura o documentación de los datos.

Siéntete libre de hacer un fork, abrir un issue o enviar un pull request. ¡La idea es que esta información sea útil para todos!

---

**Hecho para contribuir algo a la comunidad .** 
**Contáctame:**
📧 abrahammartinezhdez629@gmail.com

![Mapa de Líneas del Metro CDMX](https://metro.cdmx.gob.mx/storage/app/media/lared/MAPA_MI_3V.png)
