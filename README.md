#  Análisis de Campañas de Marketing Bancario (Bank Marketing Project)

Este proyecto combina el análisis exploratorio de datos (EDA) con **Python** y la visualización interactiva en **Power BI** para identificar los factores clave que influyen en la contratación de depósitos a plazo fijo por parte de clientes bancarios.

## Objetivo del Proyecto
Optimizar las estrategias de marketing telefónico mediante la identificación de segmentos de clientes con mayor tasa de conversión, permitiendo al equipo de ventas priorizar esfuerzos y mejorar el ROI de las campañas.

##  Tecnologías Utilizadas
* **Python (Google Colab):** Procesamiento de datos, limpieza y análisis estadístico.
    * *Librerías:* Pandas, Seaborn, Matplotlib.
* **Power BI:** Creación de un Dashboard interactivo para la toma de decisiones.
* **Dataset:** Datos de campañas de marketing basadas en llamadas telefónicas.

##  Análisis Exploratorio (EDA con Python)
En el notebook `bank_marketing_ve.py` se realizaron las siguientes tareas:
- **Limpieza de datos:** Tratamiento de nulos y verificación de tipos de datos.
- **Análisis de Correlación:** Identificación de variables críticas (duración de la llamada, educación, profesión).
- **Segmentación:** Análisis de éxito según el perfil demográfico del cliente.

**Hallazgos clave:**
1.  **Duración de la llamada:** Existe una correlación directa; los primeros 120 segundos son vitales para la retención.
2.  **Perfiles de éxito:** Los grupos de **estudiantes** y **jubilados** presentan las tasas de conversión más altas.
3.  **Nivel Educativo:** Los clientes con educación terciaria muestran una mayor propensión a aceptar el producto.

##  Dashboard de Power BI
El archivo `bank_marketing_ve.pbix` contiene una solución visual que permite a los usuarios:
- Filtrar resultados por profesión y nivel educativo.
- Visualizar la tasa de éxito de la campaña de manera dinámica.
- Identificar rápidamente los segmentos con mayor potencial de conversión.

## Estructura del Repositorio
- `bank_marketing_ve.py`: Script de Python con el análisis exploratorio completo.
- `bank_marketing_ve.pbix`: Archivo de Power BI con el dashboard interactivo.
- `Bank marketing Venezuela.xlsx`: Dataset utilizado para el análisis.

##  Cómo ejecutar el proyecto
1.  **Python:** Puedes abrir el script en Google Colab o cualquier entorno local de Jupyter. Asegúrate de tener instaladas las librerías `pandas`, `seaborn` y `matplotlib`.
2.  **Power BI:** Requiere Power BI Desktop para abrir el archivo `.pbix` y explorar las visualizaciones.

---
**Autor:** Mikhail Acevedo
**LinkedIn:** https://www.linkedin.com/in/mikhailacevedo/




<img width="868" height="527" alt="image" src="https://github.com/user-attachments/assets/cb520736-7e49-44e0-8c3b-c06c33b14208" />


