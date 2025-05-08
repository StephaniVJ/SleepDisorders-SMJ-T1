
# 💤 Análisis  de Trastornos del Sueño

Este proyecto aplica técnicas de Ciencia de Datos y Aprendizaje Automático para analizar y predecir trastornos del sueño a partir de variables relacionadas con el estilo de vida y la salud. Utiliza un dataset obtenido de Kaggle que incluye información sobre salud mental, nivel de estrés, consumo de sustancias, actividad física, entre otros factores.

---
# 📚Estructura del repositorio

1.Carpeta principal [Sleep-Diorders](https://github.com/StephaniVJ/SleepDisorders-SMJ-T1/tree/main)
  - [Notebooks](Sleep-Disorders/Notebooks)
     - sleep-disorder--->Código Original
     - Trastorno-del-sueño--->Código optimizado
  - [PDF-Report](Sleep-Disorders/PDF)
  - Readme.md
---
## 📊 Objetivo del Proyecto

- Analizar la relación entre variables de salud y estilo de vida con los trastornos del sueño.
- Aplicar modelos de Machine Learning para predecir el tipo de trastorno presente en cada paciente.
- Comparar el rendimiento de distintos modelos de clasificación.
- Visualizar resultados e interpretar hallazgos relevantes.
---
## 🤖 Modelos Utilizado

- Regresión Logística

- Árbol de Decisión

- Random Forest

- K-Nearest Neighbors (KNN)


Comparación con visualizaciones (matriz de confusión, curva ROC)

---
## 📈 Resultados
Los modelos  XGBoost y Gradient Boosting optimizados obtuvieron el mejor rendimiento con una accuracy de 0.96%. Los resultados la edad, el campo laboral, la frecuencia cardica, el género y el nivel de actividad física; son variables altamente correlacionadas con trastornos como el insomnio y la apnea.

---
## 📑 Informe
Consulta el informe completo en formato PDF dentro del repositorio:
📎 report.pdf

Incluye:

* Descripción del problema médico

* Análisis exploratorio

* Explicación de modelos

* Conclusiones
  
---
## ⚙️ Requisitos
Instala las dependencias con:

```bash
pip install -r requirements.txt

# Puedes ejecutar el proyecto clonando este repositorio y abriendo los notebooks del código base y del código optimizado:
git clone (https://github.com/StephaniVJ/SleepDisorders-SMJ-T1)
cd Sleep-Disorders/Notebooks
jupyter notebook Trastorno-del-sueño(1).ipynb  # Código optimizado
jupyter notebook sleep-disorders.ipynb # Código base
```

Licencia
Este proyecto se distribuye bajo la licencia MIT. Puedes modificarlo y reutilizarlo libremente para fines educativos o personales.
