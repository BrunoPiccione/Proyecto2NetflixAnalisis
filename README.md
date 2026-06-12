# 📊 Dashboard de Netflix en Power BI

Este proyecto consiste en un cuadro de mando interactivo desarrollado en **Power BI** para analizar el catálogo global de Netflix. El objetivo es transformar datos brutos en insights visuales que permitan entender la estrategia de contenido de la plataforma.

## 📸 Vista del Dashboard
*(Acá vas a poner la imagen de tu panel para que se vea apenas entren)*
![Pantalla Principal del Dashboard](dashboard_netflix.png)

## 🛠️ Procesos de Datos Utilizados
Para armar este reporte apliqué el flujo completo de BI:
* **ETL (Power Query):** Limpieza de textos, separación de géneros fusionados, manejo de valores en blanco y transformación de tipos de datos (fechas y países).
* **Modelado de Datos:** Creación de tablas de dimensiones (Calendario, Geografía) para armar un modelo en **Esquema de Estrella (Star Schema)** eficiente.
* **Métricas DAX:** Creación de medidas calculadas para KPIs clave (Total de Títulos, % de Películas vs Series, Promedio de Años en Catálogo, etc.).

## 💡 ¿Qué se puede analizar en este panel?
El usuario puede interactuar con el reporte y filtrar por:
1. **Tipo de contenido:** Segmentación instantánea entre Películas y Series.
2. **Análisis Geográfico:** Mapa interactivo con la concentración de producciones por país.
3. **Evolución Temporal:** Gráfico de líneas que muestra la tendencia de adición de títulos a lo largo de los años.
4. **Top Categorías:** Gráficos de barras con los géneros más repetidos.
