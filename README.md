# ConnectaTel – Análisis de Comportamiento de Clientes

Este repositorio contiene el análisis exploratorio realizado sobre los datos de ConnectaTel, empresa de telecomunicaciones en Latinoamérica.

El proyecto trabaja con tres datasets que registran información de planes, clientes y uso real de servicios hasta el año 2024, diseñados para simular condiciones reales de datos en la industria: valores faltantes, sentinels, outliers e inconsistencias de formato.

---

## 📂 Contenido del repositorio

- `notebooks/connectatel_analysis.ipynb`
  → Notebook principal con carga, limpieza, EDA, segmentación de clientes e insights ejecutivos.

---

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/imjesusgarcia/Project-ConnectaTel-Student/blob/main/Estudiante_Project_ConnectaTel.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

---

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/connectatel_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga los datasets desde `/datasets/` — asegúrate de tener disponibles:
   - `plans.csv`
   - `users_latam.csv`
   - `usage.csv`

---

## 🧠 Objetivo del análisis

- Detectar y corregir problemas de calidad de datos (sentinels, fechas inválidas, nulos)
- Construir métricas de uso por usuario a partir de datos de llamadas y mensajes
- Analizar distribuciones e identificar outliers mediante el método IQR
- Segmentar clientes por nivel de uso y grupo de edad
- Generar recomendaciones accionables para el equipo comercial de ConnectaTel

---

## 🛠️ Stack

`Python` · `pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Jupyter Notebook`
