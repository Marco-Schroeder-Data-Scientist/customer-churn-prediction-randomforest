# Proyecto de Predicción de Churn en Clientes de Seguros

## Descripción
Este proyecto analiza y predice el churn (abandono) de clientes en una compañía de seguros usando un dataset de hackathon (Train.csv y Test.csv). Incluye EDA exhaustivo, segmentación RFM, pruebas estadísticas, modelado predictivo (Logística, Decision Tree, Random Forest) con optimización de hiperparámetros, y estimación de impacto económico. El enfoque prioriza retención eficiente, con transición de análisis descriptivo a predictivo y métricas de negocio.

Objetivos:
- Identificar patrones de churn mediante EDA y RFM.
- Predecir churn con modelos ML, optimizando para desbalance.
- Cuantificar ahorro neto y ROI de intervenciones.

Dataset: ~33.908 registros en Train (17 features anónimas + target 'labels'), 11.303 en Test.

## Instalación
1. Clona el repositorio: `git clone <repo_url>`
2. Instala dependencias: `pip install -r requirements.txt`
3. Coloca `Train.csv`, `Test.csv` y `sample_submission.xlsx` en la raíz.

## Uso
- Ejecuta el notebook secuencialmente (Jupyter/Colab).
- Ajusta umbrales o costos en secciones correspondientes.
- Submission generada: `submission_rf_umbral0.4.csv` (ajustable).

## Resultados clave
- RFM: Churn hasta 20.78% en segmentos de alto riesgo.
- Modelo ganador: Random Forest (AUC 0.9997, Recall 100%, Precision 93%).
- Impacto: Ahorro neto ~$506k, ROI 830% en Test.

## Contribuciones
Sugerencias/PR bienvenidas. Contacto: [tu_email].

## Licencia
MIT License.