Este repositorio contiene un proyecto completo de Business Intelligence desarrollado en Tableau, utilizando múltiples fuentes de datos relacionadas y enfocándose en la identificación de patrones de rentabilidad, desempeño territorial y comportamiento del público.
El objetivo es demostrar habilidades técnicas en ETL, modelamiento relacional, visual analytics y comunicación de insights para la toma de decisiones.

Este proyecto implementa un modelo de datos compuesto por diversas tablas interrelacionadas. A partir de ellas se construyen dashboards orientados al análisis de:

  - Ingresos y ganancias por ciudad.
  - Rentabilidad por función (evento/película).
  - Relación entre entradas vendidas y rentabilidad.
  - Cantidad de ventas de entradas por cada cine.
  - Distribución territorial de ganancias mediante mapas.

Cada visualización no solo permite explorar los datos, sino explicar dinámicas de negocio y soportar decisiones estratégicas.


Arquitectura del Modelo de Datos

  El proyecto está basado en una estructura multitabla, lo que permite realizar análisis cruzados entre:

    - Localidades → Ciudad/Región
    - Funciones → Tipo de evento / Película / Horarios
    - Entradas vendidas
    - Ganancias generadas
    - Periodo temporal (meses)

Procesos realizados:
  - Limpieza de datos
  - Homologación de nombres de ciudades
  - Conversión de formatos de fecha
  - Normalización de columnas numéricas (ganancia, entradas)

Modelamiento relacional
  - Llaves primarias definidas por ID de función, ciudad y fecha
  - Integración de tablas auxiliares para enriquecimiento del modelo

Cálculo de métricas clave (KPIs)
- Ganancia mensual por ciudad
- Ganancia por tipo de función(Ebtradas vendidas - Costos Operativos)
- Promedios móviles (cuando corresponde)

Diseño de visualizaciones
- Gráficos comparativos
- Mapas de calor
- Mapas geográficos
- Diagramas de dispersión (scatterplot) para correlaciones

📈 Dashboards y Visualizaciones Incluidas
1) Ganancia por Cine(en cada ciudad)

- Comparación temporal del rendimiento de cada cine en sus respectivas ciudades en base a ganancias obtenidas.
- Insights que permite obtener:
  - Identificación de cines mas rentables.
  - Determinar patrones de mayor ganancia.
  - Cines con mas proyeccion v/s cines con mayores pérdidas.
📎 Imagen referenciada:
Venta de entradas por Cine.png

2) Ganancia por Ciudad (por Mes)

- Comparación temporal del rendimiento de cada ciudad en 4 meses en base a ganancias obtenidas vs costos operativos.
- Insights que permite obtener:
  - Identificación de ciudades más rentables
  - Estacionalidad mensual
  - Ciudades emergentes vs ciudades en declive
  - Meses con mayor impacto en el negocio
📎 Imagen referenciada:
Ganancia Ciudad por mes.png


3) Ganancia por Entradas Vendidas en Funciones

- Diagrama que muestra la relación directa entre volumen de entradas vendidas y expectativas de venta por cada función.
- Insights que permite obtener:
  - Funciones mas rentables
  - Ganancias obtenidas en cada funcion
📎 Imagen referenciada:
Ganancia por entradas en Funciones.png

4)  Mapa de Ganancias por Ciudad

- Mapa geográfico en Tableau que muestra el nivel de ganancia acumulada para cada ubicación.
- Insights que permite obtener:
  - Distribución territorial del ingreso
  - Concentración de ganancias (hotspots)
  - Ciudades clave para expansión comercial
  - Brechas geográficas en el desempeño
📎 Imagen referenciada:
Mapa_Ciudades.png

5) Distribucion de ingresos por función.
- Histograma que permite en base a parametros(100.000 dolares), determinar como se distribuyen las funciones en base al ingreso obtenido. 
- Insights que permite obtener:
  - Identificar en qué intervalos de ingreso existe mayor frecuencia de funciones, ya sea en rangos bajos, medios o altos.
  - Permite ver si hay pocos rangos con muy pocas funciones, lo cual indicaría posibles outliers (ya sea muy altos o muy bajos).
  - Que agrupacion de ingresos presenta la myor cantidad de funciones


📌 KPI Calculados en Tableau

-  Ganancia mensual/total por cine.
-  Ganancia total por mes.
-  Ganancia mensual
-  Promedio de ganancia por función
-  Entradas vendidas por función
-  Margen entrada/ganancia
-  Ranking de ciudades más rentables
-  Comparación intermensual (%)

🧪 Habilidades Demostradas

Este proyecto evidencia dominio en:

.- Business Intelligence
- Construcción de dashboards ejecutivos
- Presentación clara de insights
- Metodologías de descubrimiento visual (Visual Analytics)
- Data Analytics
- Análisis exploratorio (EDA)
- Detección de patrones y outliers
- Métricas comparativas
- ETL / Preparación de Datos
- Normalización y limpieza
- Unión y relación entre múltiples fuentes
- Buenas prácticas de modelado en Tableau
- Storytelling con Datos
- Diseño orientado a decisiones
- Representación visual estratégica
- Narrativa a través de dashboards-
- Ciudades emergentes vs ciudades en declive
- Meses con mayor impacto en el negocio
