# RetentionMetric-Engine: Análisis y Predicción de Churn con Enfoque Econométrico

## Descripción del Proyecto
Sistema integral para la predicción de la tasa de abandono (Customer Churn) diseñado para optimizar la toma de decisiones operativas. A diferencia de los enfoques tradicionales de "caja negra", este proyecto prioriza la interpretabilidad econométrica para entender los causantes del abandono y maximizar el retorno de inversión (ROI) de las campañas de retención.

## Tecnologías y Habilidades
* **Ingeniería:** Python, Pandas, Scikit-Learn, XGBoost, API REST (FastAPI - *Pendiente*).
* **Econometría:** Regresión Logística (Análisis de coeficientes y Odds Ratio), Feature Importance (SHAP values).
* **Negocio:** Matriz de Confusión orientada a Costos, Segmentación de Clientes.

## Estructura del Proyecto
* `data/`: Contiene los datasets crudos y procesados (no incluidos en repo por privacidad).
* `notebooks/`:
    * `01_EDA_Econometrico.ipynb`: Análisis exploratorio centrado en variables significativas.
    * `02_Model_Training.ipynb`: Entrenamiento comparativo (Logistic Regression vs Random Forest).
    * `03_Decision_Analysis.ipynb`: Evaluación de impacto en negocio y simulación de escenarios.
* `src/`: Scripts de procesamiento y modelado modularizados.

## Cómo Ejecutar
1.  Clonar repositorio.
2.  Instalar dependencias: `pip install -r requirements.txt`
3.  Ejecutar notebooks en orden.

## Autor
Jose Candon Rubio - Ingeniería Informática, Mención en Economía (UB)
