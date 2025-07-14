# 📊 Carpeta `eda/` – Análisis Exploratorio de Datos

Esta carpeta contiene el análisis exploratorio de datos (EDA) sobre el impacto del COVID-19 en los países de Latinoamérica.

---

## 📌 Propósito

Realizar un estudio comparativo regional para entender cómo la pandemia afectó a distintos países de América Latina, utilizando el dataset limpio generado en `etl/`.

---

## 📄 Contenido

- `eda.ipynb`: análisis exploratorio general de múltiples indicadores relacionados al COVID-19, incluyendo salud, demografía, economía, vacunación y comorbilidades.

---

## 📈 Visualizaciones destacadas

El notebook genera gráficos que se incluyen en el informe, tales como:

- Matriz de correlación
- Evolución de casos y muertes
- Vacunación por país
- Comparaciones por temperatura, densidad, PIB, comorbilidades, etc.
- Análisis de personal de salud, población por edad y tasa de mortalidad

---

## 📥 Requisitos

- El archivo `data_latinoamerica_clean.csv` debe estar en `data/processed/`
- Librerías utilizadas:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy.interpolate`

---

## 🧠 Recomendaciones

- Este notebook está pensado para ser ejecutado una vez procesados los datos.
- La interpretación de resultados está acompañada por un informe externo (`Informe/`) con gráficos generados desde aquí.

---
