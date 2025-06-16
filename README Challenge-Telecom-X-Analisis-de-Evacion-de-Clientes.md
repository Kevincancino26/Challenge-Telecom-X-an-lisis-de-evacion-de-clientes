# README - Telecom X: Análisis de Evasión de Clientes (Churn Prediction)

## Descripción del Proyecto 
Este notebook realiza un análisis exploratorio y predictivo del fenómeno de "churn" (evasión de clientes) para Telecom X, una empresa de telecomunicaciones que enfrenta altas tasas de cancelación de servicios. El proyecto incluye:

1._Limpieza y transformación de datos

2._Análisis exploratorio (EDA) con visualizaciones clave

3._Modelado predictivo de churn

4._Recomendaciones estratégicas basadas en hallazgos

## Estructura del Notebook
### 1. Configuración Inicial
* Importación de bibliotecas (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* Carga de datos desde archivo JSON
### 2. Limpieza y Preprocesamiento
* Normalización de datos anidados

* Tratamiento de valores nulos/missing

* Transformación de tipos de datos

* Creación de nuevas variables (ej: costos diarios)

### 3. Análisis Exploratorio (EDA)
* Distribución de churn (yes/no/unknown)

* Análisis por categorías:

* Demográficas (edad, género, estado civil)

* Servicios contratados (internet, telefonía, streaming)

* Tipos de contrato

* Análisis económico:

  - Costos mensuales vs. churn

  - Costos totales por evasión

  - Tiempo de permanencia antes del churn

### 4. Modelado Predictivo
* Preparación de datos para modelos

    - Prueba de varios algoritmos:

    - Regresión Logística

    - Random Forest

    - XGBoost

* Análisis de importancia de características

### 5. Resultados y Recomendaciones
* Principales hallazgos del análisis

* Factores clave que influyen en el churn

* Recomendaciones estratégicas para reducir la evasión

##Hallazgos Clave
1._Los clientes con contratos mensuales tienen 3x más probabilidad de churn

2._Los costos elevados son el principal motivo de cancelación

3._Los primeros 10 meses son críticos para la retención

4._Problemas técnicos en fibra óptica impactan significativamente

## Cómo Ejecutar el Notebook
1._Abrir en Google Colab mediante el enlace proporcionado

2._Ejecutar las celdas secuencialmente

3._Para replicar con nuevos datos:
   * Subir archivo JSON con misma estructura

   * Actualizar ruta de carga en la sección inicial

## Requisitos
- Python 3.8+

- Bibliotecas listadas en el notebook

- ~2GB RAM para procesamiento

## Autor
Kevin Cancino - Analista de Datos

Licencia
MIT License

Contacto
kcancino@ejemplo.com

Notas Adicionales
Los datos utilizados son confidenciales propiedad de Telecom X. Este análisis se realizó en el marco del Challenge Analítico LATAM 2023.


  
