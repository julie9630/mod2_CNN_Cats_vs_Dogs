# 🐶🐱 Clasificador Perros vs Gatos — Proyecto Completo (V1, V2, V3)
By Julieta Itzel Pichardo Meza (A01369630)

Este repositorio contiene **todo el pipeline del proyecto de visión computacional para clasificar imágenes de perros y gatos**, incluyendo:

- Reporte final en PDF  
- Notebooks de entrenamiento (versiones V1, V2, V3)  
- Notebook para cargar modelos entrenados y hacer predicciones (Recomendado en Google Colab)
- Modelos guardados en formato `.pth`  
- Archivo `environment.yml` para reproducir el ambiente  
- Dataset Cats-vs-Dogs de Kaggle

---

## 📁 Contenido del Repositorio

### 📄 **Cats_vs_Dogs_REPORTE_A01369630.pdf**  
Reporte final del proyecto.  
Incluye: introducción, metodología, arquitectura de los modelos, transformaciones, métricas, análisis de resultados y conclusiones.

---

### 📓 **Python (perros-gatos) V1.ipynb**  
Entrenamiento del **Modelo Versión 1 (V1)**.  
- CNN simple construida desde cero  
- Transformaciones básicas  
- Entrenamiento inicial y primeras métricas  
- Ideal para mostrar el funcionamiento básico de una CNN sin técnicas avanzadas
- Incluye matriz de confusión y gráficas de loss/accuracy  


---

### 📓 **Python (perros-gatos) V2.ipynb**  
Entrenamiento del **Modelo Versión 2 (V2)**.  
- Arquitectura más profunda  
- Capas adicionales, dropout y regularización  
- Mejoras significativas en accuracy  
- Incluye matriz de confusión y gráficas de loss/accuracy  

---

### 📓 **Python (perros-gatos) V3.ipynb**  
Entrenamiento del **Modelo Versión 3 (V3)** – *la versión más avanzada*.  
- Uso de **Transfer Learning** (como ResNet18)  
- Aumento de datos más sofisticado  
- Hiperparámetros optimizados  
- También incluye matriz de confusión y gráficas de loss/accuracy  
- Mejor desempeño entre las tres versiones  

---

### 📓 **Python (perros-gatos) cargar modelo colab.ipynb**  
Notebook para **cargar y ejecutar predicciones** usando el modelo V3 ya entrenado en Google Colab.  
Permite probar imágenes nuevas sin necesidad de reentrenar.

---

### 📓 **Python (perros-gatos) cargar modelo local.ipynb**  
Notebook para **cargar y ejecutar predicciones** con el modelo V3 de manera local.  
Permite probar imágenes nuevas sin necesidad de reentrenar.

---

### 🧠 **clasificador_perros_gatos_v1.pth**  
Archivo del **modelo entrenado V1** listo para cargar en PyTorch.

### 🧠 **clasificador_perros_gatos_v2.pth**  
Archivo del **modelo entrenado V2**.

### 🧠 **clasificador_perros_gatos_v3.pth**  
Archivo del **modelo entrenado V3** (modelo final recomendado).

---

### ⚙️ **enviorment.yml**  
Archivo para crear el **ambiente virtual con Conda** utilizado en los notebooks.  
Contiene todas las dependencias necesarias para ejecutar y entrenar los modelos.

---

### 💾 **Dogs-vs-Cats.zip**  
Dataset que contiene las imágenes que se usan para entrenar el modelo en formato comprimido. Este, al rebasar el tamaño máximo de un archivo en un repositorio de Github, se encuentra en el siguiente link: https://www.kaggle.com/c/dogs-vs-cats/data 

---


# 🚀 Cómo Usar Este Repositorio

## 🌐 Ejecución en Google Colab para hacer predicciones (RECOMENDADO)
Abrir y ejecutar las instrucciones del archivo Python (perros-gatos) cargar modelo colab.ipynb

## 💻 Ejecución Local para hacer predicciones
Abrir y ejecutar las instrucciones del archivo Python (perros-gatos) cargar modelo local.ipynb