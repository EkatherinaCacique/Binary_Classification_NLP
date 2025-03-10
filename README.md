# 🌸📚 Clasificación Binaria NLP en IMDb con Redes Neuronales  

Este proyecto entrena un modelo de clasificación binaria utilizando el conjunto de datos de reseñas de películas de **IMDb**. Se emplea **aprendizaje profundo** con la biblioteca **Keras** para predecir si una reseña tiene una valoración **positiva** o **negativa**.  

## 🚀🌸 Descripción del Proyecto  

El código implementa una **red neuronal densa** con Keras para realizar **clasificación binaria** en un conjunto de datos de **reseñas de películas de IMDb**. Se carga el conjunto de datos, se preprocesa, se entrena un modelo y se visualizan los resultados.  

## 📌🌸 Características Principales  

✔ Carga el conjunto de datos de **IMDb** (10,000 palabras más frecuentes).  
✔ Vectoriza las reseñas mediante **one-hot encoding**.  
✔ Implementa una red neuronal con **dos capas ocultas**.  
✔ Usa **entropía cruzada binaria** como función de pérdida.  
✔ Divide el conjunto de datos en entrenamiento y validación.  
✔ Muestra **gráficas** de la evolución del entrenamiento.  

## 🛠️🌸 Instalación y Configuración  

1. **Clona el repositorio** o copia el código en tu entorno:  
   ```sh
   git clone https://github.com/tu_usuario/tu_repositorio.git
   cd tu_repositorio
   ```  

2. **Instala las dependencias necesarias**:  
   ```sh
   pip install numpy matplotlib tensorflow keras
   ```  

3. **Ejecuta el script principal**:  
   ```sh
   python main.py
   ```  

## 💂🏻‍♂️🌸 Estructura del Proyecto  

```
/proyecto
│── main.py                 # Archivo principal para ejecutar el modelo
│── README.md               # Documentación del proyecto
│── requirements.txt        # Lista de dependencias
│── .gitignore              # Archivos a ignorar en Git
│── /src
│   ├── Binary_Classification_NLP.py            # Código del modelo y entrenamiento
```

## 🧠🌸 Explicación del Modelo  

1. **Carga del dataset**: Se usa `keras.datasets.imdb` para obtener reseñas de películas etiquetadas como positivas o negativas.  
2. **Preprocesamiento**: Se convierten las reseñas en vectores de tamaño fijo mediante **one-hot encoding**.  
3. **Creación del modelo**:  
   - Capa densa con **16 neuronas** y activación `ReLU`.  
   - Otra capa densa con **16 neuronas**.  
   - Capa de salida con **1 neurona** y activación `sigmoid` para clasificar.  
4. **Entrenamiento**: Se divide el dataset en **entrenamiento** y **validación**. Se entrena durante **20 épocas** con `batch_size=512`.  
5. **Evaluación**: Se calcula la precisión final en los datos de prueba.  
6. **Visualización**: Se grafican la **pérdida** y **precisión** durante el entrenamiento.  

## 📊🌸 Resultados Esperados  

Durante el entrenamiento, se mostrarán las gráficas de la evolución del **error** y la **precisión**.  

## 📝🌸 Notas  

- **El conjunto de datos ya está preprocesado** en Keras, por lo que las palabras están representadas como enteros.  
- Se usa **one-hot encoding** para representar las reseñas en un vector de tamaño fijo de 10,000 elementos.  
- El modelo utiliza **sigmoid** para devolver la probabilidad de que la reseña sea positiva.  

---

🌸 Espero que te guste con el toque de emojis rosas 🌸✨💖

