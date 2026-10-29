# Procesamiento en Batch con Apache Spark - Tarea 3 Big Data

Este repositorio contiene el código fuente para el procesamiento por lotes (*batch*) de un conjunto de datos, desarrollado como parte de las actividades prácticas del curso de **Big Data** de la UNAD[cite: 13, 17].

## Descripción de la Solución
El script principal (`Tarea3.py`) realiza las siguientes tareas utilizando Apache Spark (`PySpark`)[cite: 14]:
* **Carga de Datos:** Importa un conjunto de datos masivo almacenado en el sistema de archivos distribuido de Hadoop (`HDFS`).
* **Esquema y Estructura:** Valida y despliega el esquema de los datos mediante `printSchema()`.
* **Análisis Exploratorio (EDA):** Muestra las primeras filas y genera estadísticas descriptivas básicas del DataFrame[cite: 14].
* **Transformaciones y Consultas:** Aplica filtros condicionales y ordenamientos descendentes utilizando funciones de Spark SQL (`F.col`, `filter`, `sort`)[cite: 14].

## Estructura del Repositorio
- `Tarea3.py`: Script en Python con la lógica de procesamiento en lotes sobre Spark.

## Instrucciones de Ejecución
Para ejecutar este script de procesamiento en batch dentro de tu entorno virtualizado con Hadoop y Spark, utiliza el siguiente comando en la terminal:

```bash
spark-submit Tarea3.py
