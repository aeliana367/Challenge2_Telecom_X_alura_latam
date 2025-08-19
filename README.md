Proyecto de analisis de churn de clientes de Telecom-X


Vision  general del proyecto 



Este repositorio contiene un proyecto de analisis de datos que tiene como objetivo comprender la tasa de abandono de clientes (churn)
para Telecom X, una empresa ficticia del sector de las telecomunicaciones y como parte del rol de asistente de datos , el objetivo fue recopilar, limpiar, procesar y analizar los datos de los clientes para identificar los factores clave que contribuyen a la pérdida de usuarios. 


Objetivo y analisis 

El principal problema que enfrenta Telecom X es una alta tasa de cancelaciones de servicios, por lo tanto este proyecto  tiene como objetivo:
    *Identificar patrones y tendencias en los datos de los clientes que abandonan. 
    *Dterminar las variables clave (demograficas, de servicio, de contrato y de comportamiento de gasto) que estas relacionadas con el churn.
    *Extraer insights accionables que permitan al equipo de Data Science y a la gerencia de Telecom X comprender "por qué" los clientes se van y "qué" se puede hacer al respecto.


*Estructura del repositorio 

Este repositorio cuenta con los siguientes elementos:
    *README : Este archivo, con una breve descripcion del proyecto.
    *telecomx.ipynb : El archivo principal del proyecto que contiene todo el código Python, el análisis, las visualizaciones y el informe final.


Herramientas y librerias utilizadas

    *pandas: para la manipulacion y procesamiento de los datos. 
    *numpy: para operaciones numericas eficientes. 
    *matplotlib: para la creacion de graficos  y visualizaciones.
    *seaborn: para la visualizacion de estadisticas  complejas.


Pasos del analisis 

El proyecto tiene la siguiente estructura:

   1)_ Recopilacion y carga de datos:Importacion del dataset inicial (JSON) en un entorno de trabajo de Python.
   2)_Limpieza y procesamiento de datos: 
      *Normalizacion de la estructura JSON.
      *Manejo de valores nulos o vacios.
      *Conversion de tipos de datos.
      *Transformación de valores categóricos ('Yes'/'No' a 1/0).
      *Unión de DataFrames para crear un dataset único y consolidado.

   3)_Analisis exploratorio de datos (EDA):
      *Calculo de la tasa general del churn.
      *Analisis de la distrubucion de churn  por variables categoricas.
      *Analisis de la distrubucion de churn  por variables numericas,utilizando estadisticas descriptivas, histogramas y box plots para identificar valores.

    

    
