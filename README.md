# AWS

# Laboratorio AWS Glue
## Arquitectura

[Diagrama en blanco.pdf](https://github.com/user-attachments/files/22059759/Diagrama.en.blanco.pdf)


## **Objetivo**
* Construir un ETL (Extract, Transform, Load) en los servicios de AWS Glue.

## **Descripción**
* Este código lee desde el AWS Glue Datacatalog la tabla en una base de datos, después realiza una eliminacion de las columnas especificadas. Finalmente, escribe el resultado en un archivo Parquet en S3. 

## **Qué vamos a Aprender?** 
Al final del laboratorio el estudiante aprenderá:
* Como construir un ETL en AWS Glue y toda la configuración requerida para lograrlo.
* Como utilizar los rastreadores de AWS Glue para identificar estructuras de datos y alimentar el AWS Glue Data Catalog.
* Como leer información del AWS Glue Data Catalog y utilizarla para hacer las transformaciones necesarias.
* Como convertir archivos de CSV a Parquet.
* Como Cargar información transformada a Amazon S3.

## **Servicios de AWS a Utilizar**
* [Amazon Athena](https://aws.amazon.com/athena/).
* [AWS Glue](https://aws.amazon.com/glue/).
* [AWS Glue Data Catalog](https://docs.aws.amazon.com/es_es/glue/latest/dg/start-data-catalog.html).
* [AWS Glue Crawler](https://docs.aws.amazon.com/glue/latest/dg/add-crawler.html).
* [Amazon S3](https://aws.amazon.com/s3/).
* [IAM](https://aws.amazon.com/iam/).

## **Conceptos**
* **Dynamic Frame:** Es una estructura de datos similar a un DataFrame de Apache Spark, pero con características adicionales que lo hacen más adecuado para los procesos de transformación de datos en AWS Glue. 
* **Data Frame:** Es una estructura de datos similar a un DataFrame de Apache Spark, pero con características adicionales que lo hacen más adecuado para los procesos de transformación de datos en AWS Glue.
* **Inner Join:** es un tipo de operación de combinación (join) en bases de datos y sistemas de procesamiento de datos (como SQL, Spark, etc.) que se utiliza para combinar filas de dos tablas basándose en una condición común.

## **Explicación del Código**
A continuación voy a explicar detalladamente el código del archivo glue_dyf.py
