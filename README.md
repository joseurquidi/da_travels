# Travel Dataset
Este proyecto analiza datos de vuelos y hoteles para identificar los destinos más populares y económicos entre usuarios de 25 a 35 años, calculando el costo total del viaje (vuelo + hospedaje). A través de limpieza de datos, uniones entre tablas y visualizaciones, detectar patrones de demanda, precios y estacionalidad que permiten entender mejor el comportamiento de viaje de este segmento.
## Preguntas de negocio
- ¿Cuáles son los destinos más populares entre usuarios de 25 a 35 años?
- ¿Cuáles son los destinos más económicos considerando el costo total del viaje (vuelo + hospedaje)?
## Proceso de análisis
El análisis se desarrolló a través de las siguientes etapas:

### Exploración inicial
- Revisión general de los datasets
- Identificación de valores nulos y comprensión de la estructura de los datos
### Limpieza y preparación de datos
- Conversión de tipos de datos
- Renombramiento de columnas para mayor claridad
- Detección y tratamiento de valores duplicados (exactos y lógicos)
- Estandarización de variables categóricas
- Validación de consistencia en variables numéricas
### Selección y validación de variables
- Selección de columnas relevantes para el análisis
- Evaluación de rangos de variables y outliers
### Análisis exploratorio de datos (EDA)
- Identificación de patrones, tendencias y comportamientos
- Análisis orientado a negocio
- Filtrado de datos según criterios relevantes
### Integración de datos
- Validación de la integridad entre tablas (relaciones entre datasets)
### Visualización
- Construcción de gráficos para facilitar la interpretación de los datos

## Conclusiones y Recomendaciones
### Conclusiones
- El costo del viaje a Rio de Janeiro es relativamente estable durante el año Oscila aproximadamente entre ~1790 y ~2180

- El análisis mensual del costo total de viaje a Rio de Janeiro muestra una estacionalidad moderada, con precios relativamente estables durante la mayor parte del año. Sin embargo, se identifica un pico significativo en octubre, lo que sugiere una alta demanda o eventos específicos en ese periodo. Por otro lado, los meses de mayo y julio presentan los costos más bajos, posicionándose como las mejores opciones para viajeros que buscan minimizar gastos.

### Recomendaciones
- Diseñar estrategias de fidelización enfocadas en usuarios recurrentes para maximizar su valor.

- Analizar el comportamiento de usuarios con alta frecuencia para identificar patrones replicables.

- Evaluar otros factores que puedan influir en la disminución de usuarios, como experiencia, disponibilidad o competencia.

- En futuros análisis, incorporar datasets más completos que incluyan conexiones y comportamiento realista de viaje.
