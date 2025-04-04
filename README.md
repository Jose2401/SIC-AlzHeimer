# <> SIC-AlzHeimer  
**Detección temprana del Alzheimer con Machine Learning y Deep Learning**  
Proyecto presentado en el **Samsung Innovation Campus 2024** – *Equipo 6*

---

## Descripción del Proyecto

**SIC-AlzHeimer** es una solución basada en inteligencia artificial que busca asistir en el diagnóstico temprano del Alzheimer mediante el análisis de datos médicos, clínicos y neuroimágenes (resonancias magnéticas cerebrales).

El proyecto incluye **dos modelos de clasificación**:

1. **Modelo Tradicional de Machine Learning:**  
   Utiliza técnicas como Random Forest, SVM, KNN y árboles de decisión sobre datos clínicos estructurados.

2. **Modelo con Redes Neuronales Convolucionales (CNN):**  
   Entrenado con imágenes cerebrales para detectar patrones asociados a diferentes etapas del Alzheimer.

---

## Requisitos

- Python >= 3.10 (probado en Python 3.12)
- Entorno con soporte para **Jupyter Notebook**
- Librerías necesarias:
  - `tensorflow`
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`
  - `opencv-python`
  - `seaborn`
  - `notebook`

Puedes instalar todas las dependencias ejecutando:

```bash
pip install -r requirements.txt
```

---

## Guía de Uso

1. **Clona este repositorio**:

   ```bash
   git clone https://github.com/tuusuario/SIC-AlzHeimer.git
   cd SIC-AlzHeimer
   ```

2. **Instala las dependencias**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Abre uno de los modelos en Jupyter Notebook**:

   - Para datos clínicos: `alzheimer_ml.ipynb`
   - Para imágenes neuronales: `alzheimer_cnn.ipynb`

   Puedes iniciar el entorno con:

   ```bash
   jupyter notebook
   ```

4. **Ejecuta las celdas del notebook** para entrenar y evaluar los modelos o simplemente revisa los resultados previamente generados.

---

## Resultados

Ambos modelos muestran una alta precisión en la clasificación entre sujetos sanos, con deterioro cognitivo leve y con Alzheimer.  
*Se obtuvieron mejores resultados con el modelo CNN usando resonancias cerebrales preprocesadas.*

> **Precisión del modelo CNN:** No C%  
> **Precisión del modelo ML:** ~95%

---

## Créditos

**Equipo 6 – Samsung Innovation Campus 2024**  
Desarrollado por estudiantes de Inteligencia Artificial del IPN – ESCOM.
* Rivas Ortega Montserrat
* Rodas Bautista Saul
* Espinosa Martínez José Carlos

---

## Licencia

Este proyecto está bajo licencia de código abierto y uso libre :D, siéntete libre de utilizarlo en tus proyectos.
