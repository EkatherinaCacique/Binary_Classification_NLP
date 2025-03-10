# IMDB Sentiment Analysis

Este proyecto entrena una red neuronal para analizar sentimientos en reseñas de películas usando el conjunto de datos IMDB.

## 📌 Requisitos

Antes de ejecutar el código, asegúrate de tener instaladas las siguientes dependencias:

```bash
pip install numpy matplotlib keras tensorflow
```

## 🚀 Ejecución del script

Para entrenar el modelo y visualizar los resultados, simplemente ejecuta el siguiente comando en la terminal:

```bash
python script.py
```

> Asegúrate de que el archivo `script.py` contiene el código del modelo.

## 📖 Descripción del Código

1. **Carga de Datos:** Se utiliza el dataset de IMDB incluido en Keras.
2. **Preprocesamiento:** Se vectorizan las secuencias de palabras en valores numéricos binarios.
3. **Construcción del Modelo:** Se define una red neuronal con capas densas.
4. **Entrenamiento:** Se entrena el modelo con un conjunto de validación.
5. **Evaluación:** Se mide la precisión del modelo sobre el conjunto de prueba.
6. **Visualización:** Se grafican las métricas de entrenamiento y validación.

## 📊 Gráficos Generados

- **Pérdida durante el entrenamiento y validación.**
- **Precisión durante el entrenamiento y validación.**

Estos gráficos ayudan a visualizar el rendimiento del modelo.

## 📜 Resultados

Tras el entrenamiento, el modelo evalúa su desempeño sobre los datos de prueba y muestra la precisión y la pérdida obtenidas.

## ✨ Mejoras Posibles

- Ajustar el número de neuronas en las capas ocultas.
- Modificar el número de épocas para evitar sobreajuste.
- Experimentar con diferentes optimizadores.

¡Siéntete libre de contribuir al proyecto con mejoras o sugerencias! 😊

