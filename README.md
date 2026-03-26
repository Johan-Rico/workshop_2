# Workshop 2 – Machine Learning & Deep Learning Aplicado

**Universidad EAFIT**
**Curso:** Introducción a la Inteligencia Artificial

---

## 👥 Equipo de Trabajo

  * Kadiha Muhamad
  * Laura Restrepo
  * Johan Rico

---

## 📌 Introducción

Este repositorio contiene el desarrollo del **Workshop 2**, el cual aborda dos problemas supervisados en el área de la Inteligencia Artificial:

* Un problema de **clasificación**, enfocado en la detección de fatiga muscular a partir de señales EMG.
* Un problema de **regresión**, orientado a la estimación de la edad a partir de imágenes faciales.

El proyecto seguirá el flujo general de Machine Learning y Deep Learning, incluyendo análisis de datos, preprocesamiento, entrenamiento y evaluación de modelos.

---

## 🧠 Estructura del Proyecto

```
workshop_2/
├── README.md
├── clasificacion/
│   └── clasificacion.ipynb
├── regresion/
│   └── regresion.ipynb
```
## Instrucciones de ejecución

### Problema 2 – Regresión (Estimación de Edad)

El dataset de regresión proviene de Kaggle y debe configurarse manualmente
antes de ejecutar el notebook. Sigue estos pasos:

1. Descarga el dataset desde:
   https://www.kaggle.com/datasets/arashnic/faces-age-detection-dataset

2. En tu Google Drive, crea la siguiente estructura de carpetas:
```
   Mi unidad/
   └── workshop_2/
       └── regresion/
           └── data/
               └── faces-age-detection-dataset.zip
```

3. Sube el archivo `faces-age-detection-dataset.zip` **sin descomprimir**
   a la carpeta `data/`.

4. Abre `regresion/regresion.ipynb` en Google Colab, ejecuta las celdas
   en orden y acepta la solicitud de acceso a Google Drive cuando aparezca.

> El notebook descomprime el dataset automáticamente en la primera ejecución.
> Las siguientes ejecuciones detectan que ya está descomprimido y omiten ese paso.

### Problema 1 – Clasificación (Fatiga Muscular)

El dataset se carga automáticamente desde HuggingFace al ejecutar el notebook.
No requiere configuración adicional.
