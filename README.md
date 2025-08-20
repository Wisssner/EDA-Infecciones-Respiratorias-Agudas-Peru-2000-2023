# Análisis Exploratorio de Datos (EDA) de Infecciones Respiratorias Agudas (IRA) en Perú: Vigilancia Epidemiológica (2000-2023)
<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/fef27444-bfac-46f2-bfa8-33044edf19a4" />

## Descripción del Proyecto

Este proyecto realiza un **análisis exploratorio de datos (EDA)** sobre un dataset relacionado con las **Infecciones Respiratorias Agudas (IRA)** en Perú, el cual es gestionado por el **Centro Nacional de Epidemiología, Prevención y Control de Enfermedades (CDC Perú)**. El dataset contiene información sobre los casos notificados de IRA desde el año 2000 hasta el 2023, desglosados por diferentes características geográficas, demográficas y de salud, como región, provincia, edad, tipo de diagnóstico y más.

**Dataset**: https://datosabiertos.gob.pe/dataset/vigilancia-epidemiologica-de-infecciones-respiratoiras-agudas-ira

## Objetivos

- **Explorar y limpiar los datos** para prepararlos para análisis posteriores.
- **Identificar patrones estacionales y geográficos** en la incidencia de IRA.
- **Detección de outliers** y su impacto en los análisis.
- **Análisis de tendencias** de hospitalizaciones y defunciones, especialmente en menores de 5 años y mayores de 60 años.
- **Evaluar la relación entre las variables geográficas** (como departamento y distrito) y las tasas de hospitalización.
- **Visualización geoespacial** utilizando los códigos de ubigeo.

## Tecnologías y Herramientas Utilizadas

- **Python**: Para la manipulación de datos y análisis.
- **Pandas**: Para la carga, limpieza y análisis de datos.
- **Matplotlib y Seaborn**: Para la visualización de datos.
- **Jupyter Notebooks**: Para el desarrollo interactivo del análisis exploratorio.

## Resultados Clave

### Tendencias Generales:
- La región **Sierra** muestra los valores más altos de hospitalizaciones durante casi todos los años.
- La región **Costa** tiene una estacionalidad marcada, mientras que la región **Selva** mantiene valores bajos.

### Efecto del COVID-19 (2020-2021):
- Se observó una anomalía significativa en los años 2020 y 2021, donde los niveles de hospitalización no presentaron los picos estacionales típicos, posiblemente debido a las medidas sanitarias implementadas durante la pandemia.

### Detección de Outliers:
- Se identificaron valores extremos en hospitalizaciones y defunciones, especialmente en distritos como **San Juan de Lurigancho** y **Piura**. Estos valores fueron analizados detenidamente antes de ser eliminados del dataset.

### Patrones Estacionales:
- Se detectaron picos en hospitalizaciones entre las **semanas 15 y 30**, correlacionados con las estaciones frías y lluviosas.

### Visualización Geoespacial:
- Se utilizó la información de **ubigeo** para generar mapas espaciales que identifican distritos críticos en términos de hospitalizaciones, lo que puede ser útil para acciones de salud pública dirigidas.

### Impacto de la Pandemia:
- El análisis de hospitalizaciones entre 2020 y 2021 muestra una clara reducción en los casos de IRA, sugiriendo que las medidas de contención del COVID-19 impactaron la propagación de otras infecciones respiratorias.

## Recomendaciones

- Priorizar la **vigilancia sanitaria** en la región **Sierra**, especialmente durante las temporadas frías.
- Utilizar el **ubigeo** para mapear zonas críticas y enfocar intervenciones de salud pública.
- Investigar con mayor profundidad el **impacto de la pandemia** sobre otras enfermedades respiratorias, como la neumonía.
- Considerar **factores climáticos** y de **acceso a servicios de salud** en futuros análisis.

Este análisis constituye una base sólida para la toma de decisiones en salud pública, orientada a la prevención y gestión eficiente de los recursos sanitarios en el Perú.
