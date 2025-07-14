# 🦠 LATAM_COVID-19

Análisis exploratorio de datos sobre la pandemia de COVID-19 en América Latina, enfocado en la evolución de casos, muertes, políticas sanitarias y vacunación entre países de la región.

---
## 📚 Tabla de contenidos

- [📌 Objetivo](#-objetivo)
- [🌎 Alcance Geográfico](#-alcance-geográfico)
- [📊 Datos Utilizados](#-datos-utilizados)
- [🧰 Herramientas y Tecnologías](#-herramientas-y-tecnologías)
- [📁 Estructura del Repositorio](#-estructura-del-repositorio)
- [📈 Visualizaciones Destacadas](#-visualizaciones-destacadas)
- [🚀 Cómo ejecutar el proyecto](#-cómo-ejecutar-el-proyecto)
- [📊 Visualización del Informe en Power BI](#-visualizacion-del-informe-en-power-bi)
- [🧠 Posibles mejoras](#-posibles-mejoras)
- [📥 Fuente de datos](#-fuente-de-datos)
- [📜 Licencia](#-licencia)
- [✒ Autor](#-autor)

---

## 📌 Objetivo

Este proyecto tiene como propósito visualizar y entender el impacto del COVID-19 en los países latinoamericanos a través de gráficos y análisis comparativos. Se busca identificar patrones, diferencias regionales y relaciones entre indicadores clave.

---



## 🌎 Alcance Geográfico

Se analizan principalmente los siguientes países de América Latina:

- Argentina
- Brasil
- Chile
- Colombia
- México
- Perú
- Uruguay  

---

## 📊 Datos Utilizados

Los datos provienen de fuentes públicas y confiables, incluyendo:

- [Our World in Data](https://ourworldindata.org/)
- [Johns Hopkins CSSE](https://github.com/CSSEGISandData/COVID-19)
- [Ministerios de Salud locales]

Los datasets se encuentran en la carpeta [`/data`](./data/), divididos entre datos crudos y datos procesados.

---

## 🧰 Herramientas y Tecnologías

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook
- Plotly (opcional)
- Streamlit (opcional, para visualización interactiva)

---

## 📁 Estructura del Repositorio

```
LATAM_COVID-19/
├── etl/
│   └── etl.ipynb
├── eda/
│   └── eda.ipynb
├── data/
│   └── processed/
├── informe/
│   ├── README.md 
│   ├── Imagenes/
│   └── Graficos/
├── powerbi/
│   └── informe_covid_latam.pbix
└── README.md

```
powerbi

---

## 📈 Visualizaciones Destacadas

Algunas de las visualizaciones generadas incluyen:

- Evolución diaria de casos confirmados y muertes
- Tasas de vacunación por país
- Comparación regional del crecimiento de contagios
- Mapas de calor y tendencias acumuladas

> 🖼 Pronto se incluirán imágenes en esta sección

---

## 🚀 Cómo ejecutar el proyecto

Este proyecto se ejecuta en notebooks de Jupyter, por lo que es recomendable contar con un entorno Python configurado con las siguientes librerías:

- pandas
- numpy
- matplotlib
- seaborn
- scipy

### 1. Clonar el repositorio

```bash
git clone https://github.com/eremohn/LATAM_COVID-19.git
cd LATAM_COVID-19
```
---

## 📊 Visualización del Informe en Power BI

Además del informe detallado disponible en formato Markdown dentro de la carpeta [`informe/`](./informe), existe una visualización interactiva en Power BI que permitirá explorar de forma dinámica los principales indicadores relacionados con el impacto del COVID-19 en Latinoamérica.

🔹 Esta visualización permitirá:
- Filtrar por país y año.
- Comparar tasas de mortalidad, vacunación, y casos confirmados.
- Visualizar relaciones entre variables socioeconómicas, sanitarias y demográficas.

📁 El archivo `.pbix` estara disponible en la carpeta [`powerbi/`](./powerbi), o será publicado a través de Power BI Service con un enlace directo aquí.


---
## 🧠 Posibles mejoras
- Implementar una app interactiva con Streamlit o Dash

- Incorporar modelos predictivos (SIR, ARIMA, Prophet)

- Automatizar limpieza de datos con notebooks reutilizables

- Agregar visualizaciones geográficas

---

## 📥 Fuente de datos

Debido al tamaño del archivo crudo (2.4 GB), no se encuentra almacenado directamente en el repositorio.

Puedes acceder y descargar el dataset desde el siguiente enlace:

- [📊 Dataset de COVID-19 (Google Drive)](https://drive.google.com/file/d/1asTXNEx_IGFDheRIDqPteII12Iz7Ghj2/view?usp=drive_link)

Una vez descargado, colocá el archivo dentro del directorio `data/raw/`.

---

## 📜 Licencia

Este proyecto se publica bajo la licencia [MIT](LICENSE).

---

## ✒ Autor

Felipe Varela – [GitHub](https://github.com/eremohn)  
Estudiante de Ingeniería Aeroespacial | Analista de Datos | Teaching Assistant

---


