# Tarea 2 — Detección de personas mirando su celular

En este proyecto entreno YOLO para detectar personas que miran directamente la pantalla de su propio celular. No considero llamadas ni personas mirando el teléfono de alguien más.

El dataset se preparó con imágenes aportadas por estudiantes de la Pontificia Universidad Católica de Chile para la tarea de Visión por Computadora. Revisé las etiquetas y separé 2741 imágenes en entrenamiento (1919), validación (411) y prueba (411).

Los archivos del dataset están en la sección **Releases**. Se dividen en dos ZIP por el límite de tamaño de GitHub: uno contiene train y `data.yaml`; el otro contiene val y test. Al descomprimirlos en el mismo directorio queda la estructura que usa YOLO.