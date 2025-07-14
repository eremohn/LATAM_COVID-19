# 🧪 Carpeta `etl/` – Limpieza y Transformación de Datos

Esta carpeta contiene el notebook principal de procesamiento de datos crudos sobre COVID-19 en América Latina.

---

## 📌 Propósito

El objetivo de este notebook es realizar la limpieza, transformación y consolidación de los datos crudos en un único archivo estructurado y apto para análisis.

---

## 📄 Contenido

- `etl.ipynb`: procesa los datos originales y genera un archivo limpio llamado `data_latinoamerica_clean.csv`, que se almacena en la carpeta `data/processed/`.

Este archivo limpio es el que se utiliza posteriormente en el análisis exploratorio (`eda/eda.ipynb`).

---

## ⚙️ Principales tareas realizadas

- Carga y revisión del dataset crudo
- Conversión de tipos de datos
- Normalización de nombres y valores
- Detección y tratamiento de valores nulos y atípicos
- Creación de métricas derivadas relevantes para el análisis
- Exportación del dataset consolidado como `data_latinoamerica_clean.csv`

---

## 📥 Requisitos

- El archivo crudo debe estar ubicado en `data/raw/` (ver instrucciones en el `README.md` general).
- Librerías utilizadas:
  - `pandas`, `numpy`, `os`

---

## 🧠 Recomendaciones

- No realizar análisis exploratorio aquí: este notebook debe enfocarse exclusivamente en preparar los datos.
- Documentar bien cada celda para asegurar reproducibilidad y claridad en futuras actualizaciones.

---
