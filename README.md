# Identificación de actividades cotidianas basado en visión por computador y cámara con montaje en la cabeza

Este repositorio contiene la implementación completa de un Trabajo de Fin de Grado (TFG) centrado en el Reconocimiento de Acciones Humanas (HAR) desde una perspectiva en primera persona (egocéntrica). El proyecto utiliza una arquitectura de Red Neuronal Convolucional 3D (3D CNN) para clasificar acciones a partir de vídeos grabados con una cámara en la cabeza.

El código incluye un pipeline completo que abarca:

    Procesamiento de datos: Scripts para leer anotaciones, extraer segmentos de vídeo y balancear clases.

    Aumento de datos: Técnicas de aumento espacial y temporal para mejorar la generalización.

    Modelo: La definición de la arquitectura 3D CNN personalizada en Keras.

    Entrenamiento y Evaluación: El bucle principal de entrenamiento, con callbacks para monitorización y guardado del mejor modelo.
