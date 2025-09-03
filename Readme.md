Este repositorio contiene la estructura y entregables requeridos para una prueba técnica para el puesto de MLOps.

La estructura principal del proyecto se basa en una serie de notebooks que sirven como pipeline del flujo de trabajo aplicado para la resolución de dicha asignación. Dicha estructura se describe a continuación:

- `0_Initial_setup.ipynb` 
    *Inicializa la configuración de bibliotecas necesarias para el resto del proyecto*
- `1_Data_Prep.ipynb`
    *Carga de datos, EDA y primer procesamiento de la información (cortes para el entrenamiento)*
- `2_Model_Training.ipynb`
    *Proceso de entrenamiento del modelo dados los datos tratados en el paso anterior*
- `3_Global_Explanations.ipynb`
    *Interpretabilidad del comportamiento global del modelo entrenado en el paso anterior*
- `4_Local_Explanations.ipynb`
    *Interpretabilidad del comportamiento local del modelo entrenado sobre un par de observaciones determinadas*
- `5_Report.ipynb`
    *Resumen ejecutivo final con el conjunto de hallazgos relevantes obtenidos en los pasos previos*

Como se puede notar, cada notebook describe de forma general el paso del flujo de trabajo aplicado a este proyecto y el tratamiento a los datos/modelo por etapas. Cuando era necesario, se guardaba una versión de dicha información para ser procesada por el notebook siguiente.




