# Visión por Computadora I - Trabajo Práctico 1

Este repositorio contiene la resolución del primer trabajo práctico de la materia Visión por Computadora I (CEIA - FIUBA).

Integrantes:
- Lucia T. Capon Paul
- Leandro Britez

---

## Contenidos del Proyecto
El trabajo se divide en dos secciones principales, implementadas en el notebook 

white_patch.ipynb
:

### 1. Balance de Blancos: Algoritmo White Patch

Implementación: Se desarrolla el algoritmo White Patch para la corrección de iluminación utilizando normalización por máximos y por percentiles.

### 2. Análisis de Histogramas

Visualización: Comparativa de histogramas en escala de grises para imágenes sintéticas y naturales.
Conclusiones: Análisis sobre la pérdida de información espacial en los histogramas y una discusión técnica sobre su viabilidad como descriptores de características (features) en modelos de clasificación y detección de objetos.

## Requisitos

Para ejecutar el notebook, se requieren las siguientes librerías de Python:


- numpy
- opencv-python (cv2)
- matplotlib

## Estructura de Archivos

white_patch.ipynb
: Notebook principal con código y análisis.
white_patch/: Carpeta con imágenes de prueba para el algoritmo de balance de blancos.

img1_tp.png | img2_tp.png
: Imágenes utilizadas para la comparativa de histogramas.
