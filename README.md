# Ecobici CDMX — Análisis y visualización geoespacial

## Descripción
El analisis de estaciones del sistema Ecobici de Ciudad de México que se presenta, utiliza Python para procesar datos, calcular la frecuencia de retiros por estación y visualizar su distribución geográfica mediante un mapa interactivo.

## Objetivos
- Explorar y transformar datos de estaciones Ecobici.
- Identificar las estaciones con mayor actividad.
- Visualizar los resultados mediante un mapa interactivo.

## Herramientas
- Python
- Pandas
- Jupyter Notebook
- Folium

## Metodología
1. Carga y exploración de los datos.
2. Cálculo de frecuencias de retiros por estación.
3. Integración de las frecuencias con los datos geográficos.
4. Clasificación de estaciones según su frecuencia.
5. Creación de un mapa interactivo con marcadores, leyenda y ranking de las diez estaciones con mayor frecuencia.

## Resultados
El análisis integra 480 estaciones. Se encontraron frecuencias de retiros para 273 estaciones; las 207 restantes no tuvieron una frecuencia asociada en los datos utilizados. Estos valores faltantes no implican necesariamente que las estaciones no hayan tenido actividad.

Si se desea **observar el resultado final** (sin necesidad de correr el codigo) se recomienda observar las **imagenes** contenidas en este mismo repositorio

## Ejecución
Abre `ecobici_analysis.ipynb` en Jupyter Notebook y ejecuta las celdas en orden. Consulta las instrucciones de obtención de los datos originales antes de ejecutar el análisis.

## Limitaciones
Los resultados dependen del periodo y de la cobertura de los datos de origen. La frecuencia de retiros no representa por sí sola el uso total ni la disponibilidad de bicicletas en cada estación.
