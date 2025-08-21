🚖  Análisis de Datos de Taxis en Chicago

Este proyecto forma parte del curso de análisis de datos y tiene como objetivo explorar patrones en el transporte de taxis en Chicago durante noviembre de 2017. Incluye análisis exploratorio y pruebas de hipótesis con datos reales.

---

## 📊 Contenido del Proyecto

### Paso 4: Análisis exploratorio de datos
Se trabajó con dos datasets:
- `project_sql_result_01.csv` → compañías de taxis y número de viajes (15–16 de noviembre de 2017)  
- `project_sql_result_04.csv` → barrios de Chicago y número promedio de viajes finalizados en noviembre de 2017  

Análisis realizado:
- Importación y verificación de tipos de datos
- Top 10 compañías de taxis con más viajes
- Top 10 barrios con más finalizaciones de trayectos
- Visualizaciones (gráficos de barras y distribuciones)
- Conclusiones basadas en los resultados

### Paso 5: Prueba de hipótesis
Dataset utilizado:
- `project_sql_result_07.csv` → viajes desde el Loop hasta el Aeropuerto O’Hare  

Hipótesis probada:
> *La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos.*

Se planteó la hipótesis nula y alternativa, se definió un nivel de significación (α) y se utilizó un criterio estadístico adecuado para comprobarla.

---

## 🛠️ Herramientas Utilizadas

- Python 3  
- pandas  
- numpy  
- matplotlib / seaborn  
- scipy.stats  
- Jupyter Notebook  

---

## 📁 Archivos

- `analisis_taxis_chicago.ipynb` → Notebook con el análisis completo
- `README.md` → Este archivo con la descripción del proyecto

---

## 📌 Resultados

- Identificación de las compañías y barrios con mayor actividad en Chicago
- Visualización de los patrones de uso del taxi por ubicación y compañía
- Comprobación estadística sobre la influencia del clima en la duración de viajes desde el Loop a O’Hare
