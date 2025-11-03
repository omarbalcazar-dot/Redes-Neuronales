# Redes-Neuronales

OBJETIVO

Entrenar un modelo de clasificación de dígitos (0–9) con MNIST, evaluarlo en prueba, y comprobar su desempeño en un conjunto propio de 50 imágenes (5 por clase). Documentar 3 mejoras aplicadas al preprocesamiento/inferencia y mostrar una demo en vivo opcional.

EVALUACIÓN

- Se cargó MNIST y se verificaron shape y distribución.
- Datos normalizados y canal agregado si aplica.
- Modelo definido, compilado y entrenado con validación y EarlyStopping.
- test_accuracy reportada y comparada con val_accuracy.
- Gráficas de accuracy y loss (train/val).
- Función de preprocesamiento externo robusta.
- Predicción de 1 imagen con visualización de pasos.
- 50 imágenes evaluadas con accuracy y matriz de confusión.
- 3 mejoras descritas con propósito y evidencia.
- Video en bandeja

MEJORAS

En esta entrega implementé tres mejoras: centrado por centro de masa, que endereza el dígito y lo coloca al centro para que la geometría se parezca a MNIST. Un preprocesamiento v2 que extrae un ROI con margen, usa el trazo (no relleno) con ligera dilatación y normaliza a 28×28. Una demo en vivo con ROI central, que recorta la zona relevante antes de inferir, reduce ruido de fondo y muestra en tiempo real la predicción y confianza con una miniatura del 28×28 procesado. En conjunto, estas mejoras aumentan la robustez, estabilizan las predicciones y facilitan su uso práctico.

El trabajo va de 2 documentos

[reporte html](IA3_2_652911.html)

[reporte ipynb](IA3_2_652911.ipynb)

