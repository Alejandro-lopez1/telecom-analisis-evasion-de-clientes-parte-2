# Análisis y Predicción de Cancelación de Clientes (Churn) - Telecom

## Descripción  
Este proyecto aborda el análisis de datos y la construcción de modelos predictivos para anticipar la cancelación de clientes en una empresa de telecomunicaciones. Utiliza técnicas de limpieza, exploración, visualización y modelado en Python para identificar factores clave que influyen en el churn y proponer estrategias de retención efectivas.

## Contenido  
- Limpieza y preprocesamiento de datos  
- Análisis exploratorio y visualización (matrices de correlación, boxplots)  
- Modelos predictivos:  
  - Regresión Logística (con normalización)  
  - Random Forest (sin normalización)  
- Evaluación con métricas: accuracy, precision, recall, F1-score, AUC-ROC, matriz de confusión  
- Análisis de variables relevantes y recomendaciones de negocio

## Tecnologías y librerías  
- Python 3.x  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn, Matplotlib  
- Google Colab (entorno de desarrollo)

## Cómo usarlo  

1. Clonar este repositorio:  
    '''git clone https://github.com/Alejandro-lopez1/telecom-analisis-evasion-de-clientes-parte-2.git'''
2. Abrir el notebook en Google Colab o Jupyter Notebook.
3. Ejecutar las celdas para reproducir el análisis y entrenar los modelos.
4. Explorar resultados y gráficos para entender las variables que impactan el churn.

## Resultados clave:
* Identificación de tenure (tiempo con la empresa) y gasto mensual como principales factores de cancelación.
* Modelos con AUC-ROC ~0.8, buen desempeño para predecir churn.
* Recomendaciones específicas para mejorar retención y personalizar ofertas.

## Contribuciones
Este proyecto está abierto para mejoras, sugerencias y colaboración.

## Autor
Alejandro Lopez
