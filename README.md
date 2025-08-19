📊 Análisis de Cancelación de Clientes (Churn Prediction)

Este proyecto tiene como objetivo identificar los principales factores que influyen en la cancelación de clientes (churn) y construir modelos de machine learning que permitan anticipar estos comportamientos, con el fin de proponer estrategias efectivas de retención.

🧠 Objetivos:
- Analizar y preparar un dataset de clientes de servicios.
- Identificar variables relevantes que afectan la cancelación.
- Construir modelos predictivos para clasificar clientes propensos al churn.
- Evaluar el rendimiento de distintos modelos.
- Proponer estrategias basadas en los hallazgos.

🗂️ Contenido:
El archivo .ipynb contiene los siguientes pasos:
🔹 1. Preprocesamiento de datos
🔹 2. Análisis exploratorio y correlación
🔹 3. Modelado predictivo y evaluación de modelos
🔹 4. Interpretación y Conclusiones

📁 Archivos: 
TelecomX_LATAM_P2.ipynb: Notebook con todo el análisis y modelado.
data/datos_tratados.csv: Archivo con datos usados en el análisis.

📌 Principales conclusiones
- Contratos más largos y cargos mensuales bajos están asociados a menor probabilidad de cancelación.
- Los métodos de pago también impactan la permanencia del cliente.
- Random Forest fue el modelo con mejor rendimiento general.
- Las variables Tiempo_contrato, Cargo_mensual y Tipo_contrato fueron clave para predecir el churn.

🚀 Herramientas y Librerías
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- SMOTE (de imblearn)
- Google Colab
