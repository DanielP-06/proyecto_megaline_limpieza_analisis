# Análisis de Rentabilidad de Tarifas de Megaline: Surf vs Ultimate

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los usuarios de Megaline que utilizan las tarifas de prepago Surf y Ultimate para determinar cuál de las dos genera mayores ingresos. El análisis se basa en datos de 500 clientes, incluyendo su información demográfica, plan de tarifa, y su consumo de llamadas, mensajes e internet durante el año 2018. Los hallazgos de este análisis buscan proporcionar información valiosa al departamento comercial de Megaline para optimizar su presupuesto de publicidad.

## Metodología

La metodología seguida en este proyecto incluye los siguientes pasos clave:

1.  **Inicialización y Carga de Datos:** Carga de los conjuntos de datos proporcionados en DataFrames de pandas.
2.  **Preparación de Datos:** Exploración, limpieza y corrección de los datos, incluyendo el manejo de valores ausentes y la conversión de tipos de datos. Se enriquecieron los datos extrayendo el mes de las fechas relevantes.
3.  **Análisis de Datos por Usuario y Periodo:** Agregación de datos por usuario y mes para calcular el consumo de minutos, mensajes y tráfico de internet.
4.  **Cálculo de Ingresos Mensuales:** Determinación del ingreso mensual generado por cada usuario, considerando las condiciones y cargos adicionales de cada tarifa.
5.  **Estudio del Comportamiento del Usuario:** Análisis estadístico descriptivo y visualización del comportamiento de los usuarios por tarifa en cuanto a llamadas, mensajes e internet.
6.  **Prueba de Hipótesis Estadísticas:** Realización de pruebas t de Student para comparar los ingresos promedio entre las tarifas y entre la región NY-NJ y otras regiones.
7.  **Conclusión General:** Resumen de los hallazgos principales y su utilidad práctica para el negocio.

## Resultados Clave

*   El plan **Ultimate** genera un ingreso promedio por usuario más alto y más estable que el plan Surf.
*   El comportamiento de los usuarios difiere principalmente en el uso de **mensajes**, donde los usuarios de Ultimate envían significativamente más mensajes. El consumo de llamadas e internet es similar entre planes.
*   Existe una diferencia estadísticamente significativa en el ingreso promedio de los usuarios en la región **NY-NJ** en comparación con otras regiones.

## Utilidad Práctica

Los resultados de este proyecto son directamente aplicables para el departamento comercial de Megaline. La recomendación principal es enfocar una mayor parte del presupuesto publicitario en el Plan Ultimate debido a su mayor rentabilidad promedio por usuario. Además, se sugiere investigar más a fondo el mercado de NY-NJ para comprender las diferencias de ingresos y desarrollar estrategias regionales específicas.

## Tecnologías Utilizadas

*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   SciPy (para pruebas estadísticas)

## Cómo Ejecutar el Proyecto

1.  Clona este repositorio.
2.  Asegúrate de tener las librerías de Python mencionadas instaladas (`pip install pandas numpy matplotlib seaborn scipy`).
3.  Coloca los archivos CSV (`megaline_users.csv`, `megaline_calls.csv`, `megaline_messages.csv`, `megaline_internet.csv`, `megaline_plans.csv`) en la ubicación especificada en el código o actualiza las rutas de archivo dependiendo de donde los guardes.
4.  Ejecuta el notebook en un entorno Python (como Jupyter Notebook o Google Colab).

## Autor

Daniel Pineda
