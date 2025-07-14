<p align="center">
  <img src="./Imagenes/Banner_informe.png" alt="Banner del Informe">
</p>

# Informe: Impacto del COVID-19 en América Latina

## Introducción
---

La pandemia de COVID-19 tuvo un impacto profundo y multifacético en todo el mundo, y los países de Latinoamérica no fueron la excepción. Esta región, caracterizada por su diversidad demográfica, socioeconómica y de infraestructura de salud, experimentó una variedad de respuestas y resultados ante la crisis sanitaria. El presente estudio se centra en analizar y comprender cómo el COVID-19 afectó a diferentes países de Latinoamérica, proporcionando una visión integral basada en datos.

## Metodología de trabajo
---

Para analizar el impacto del COVID-19 en los países de Latinoamérica, seguimos una metodología estructurada que incluye las siguientes etapas:

- **Extracción de Datos:** fuentes confiables sobre casos, muertes, vacunación, indicadores socioeconómicos y demográficos.
- **Transformación de Datos:** limpieza, normalización y estandarización.
- **Identificación de Anomalías:** detección y corrección de outliers, validación cruzada.
- **Preparación del Conjunto de Datos:** integración y creación de variables derivadas.
- **Análisis Exploratorio (EDA):** visualizaciones, estadísticas descriptivas, correlaciones.
- **Interpretación y Conclusiones:** insights para mejorar la respuesta ante futuras pandemias.

## Análisis Exploratorio de Datos
---

### Matriz de Correlación de Variables

<p align="center">
  <img src="./Graficos/matriz_de_correlacion.png" alt="Matriz de Correlación">
</p>

Principales hallazgos:

- Mayor mortalidad en hombres.
- Alta relación entre comorbilidades y mortalidad.
- La vacunación reduce contagios.
- Mayor densidad poblacional = más casos.
- PIB per cápita no influye en contagios, pero sí en mortalidad.

> *Las correlaciones no implican causalidad directa.*

---

### Casos Confirmados Acumulados por País

<p align="center">
  <img src="./Graficos/total_casos_confirmados_por_pais.png" alt="Casos Confirmados">
</p>

- Brasil lidera en casos confirmados.
- Factores: tamaño y densidad poblacional, medidas de control, testeo.

---

### Temperatura Promedio vs Casos y Decesos

<p align="center">
  <img src="./Graficos/Diagrama_de_dispersión_de_temperatura_promedio_vs_nuevos_confirmados_por_país.png" alt="Temp vs Casos">
</p>

<p align="center">
  <img src="./Graficos/Diagrama_de_dispersión_de_temperatura_promedio_vs_decesos_por_COVID-19_por_país.png" alt="Temp vs Decesos">
</p>

- Posible correlación en climas cálidos.
- Se necesitan estudios más profundos.

---

### Dosis de Vacunación Administradas

<p align="center">
  <img src="./Graficos/dosis_de_vacunacion_administradas_por_pais.png" alt="Vacunación Total">
</p>

<p align="center">
  <img src="./Graficos/dosis_de_vacunacion_administradas_por_cada_100_personas.png" alt="Vacunación per cápita">
</p>

- Brasil administra más dosis totales, pero Chile, Perú y Argentina destacan en cobertura proporcional.

---

### Evolución de Casos Nuevos Semanales

<p align="center">
  <img src="./Graficos/Evolución_de_Casos_Nuevos_de_COVID-19_en_América_Latina.png" alt="Evolución Casos">
</p>

Fases identificadas:
1. Aumento inicial (2020).
2. Descenso por vacunación (2021).
3. Rebrote tras reaperturas (2022).
4. Nueva baja (2do semestre 2022).

---

### Evolución de Decesos

<p align="center">
  <img src="./Graficos/Evolucion_de_decesoss_de_COVID-19_en_America_Latina.png" alt="Evolución decesos">
</p>

- Patrón similar al de casos nuevos.
- Importancia de sistemas de salud y vacunación.

---

### Población por Grupo Etario

<p align="center">
  <img src="./Graficos/Poblacion_por_Grupo_Etario_y_Pais_en_America_Latina.png" alt="Población Etaria">
</p>

- Mayores de 60: mayor mortalidad.
- Jóvenes: menos letalidad, pero impacto indirecto.

---

### Personal de Salud por País

<p align="center">
  <img src="./Graficos/Personal_de_Salud_por_Pais.png" alt="Personal de salud">
</p>

- Brasil, Chile y Argentina presentan mejor cobertura.
- Perú, México y Colombia: menor disponibilidad por habitante.

---

### Dosis de Vacunas per Cápita

<p align="center">
  <img src="./Graficos/Dosis_per_capita_de_vacunas_administradas_por_Pais.png" alt="Vacunas per cápita">
</p>

- Cobertura proporcional favorece a Chile y Perú.
- Brasil, pese a liderar en dosis totales, muestra cobertura media.

---

### PIB y PIB per Cápita

<p align="center">
  <img src="./Graficos/GDP_y_GDP_per_Capita_por_Pais.png" alt="PIB por País">
</p>

- Relación entre economía y tasa de casos no es directa.
- PIB per cápita influye más en capacidad de respuesta y mortalidad.

---

### Fumadores y Diabetes

<p align="center">
  <img src="./Graficos/Prevalencia_de_fumadores_y_diabetes_por_Pais.png" alt="Fumadores y Diabetes">
</p>

- Fumar y la diabetes aumentan el riesgo de COVID-19 grave.
- Comorbilidades agravan la situación sanitaria regional.

---

### Tasas de Mortalidad por País

<p align="center">
  <img src="./Graficos/Tasas_de_Mortalidad_por_Pais.png" alt="Tasa Mortalidad">
</p>

- Altas tasas en Brasil y Perú.
- México y Argentina presentan tasas más bajas.
- Excepciones como Colombia y Chile invitan a análisis más profundo.

---

## Conclusiones
---

La pandemia de COVID-19 ha impactado de manera desigual a los países de Latinoamérica. Algunas conclusiones clave:

- **Mortalidad:** Hombres y personas mayores con comorbilidades presentan mayor riesgo.
- **Vacunación:** Factor clave en reducción de contagios y muertes.
- **Economía:** PIB per cápita influye en capacidad de respuesta, no tanto en cantidad de casos.
- **Disparidades regionales:** Factores como testeo, infraestructura de salud, distribución de personal y medidas adoptadas explican las diferencias.

> Es fundamental continuar analizando estos datos para mejorar la preparación ante futuras emergencias sanitarias en la región.
