# DA-promoc-modulo3-sprint1-judith-gadea

***Repositorio con los trabajos de Gadea Autric y Judith Blanco***


----------------------------
## Modulo 3: Machine Learning
--------------------------------------------------


*[Regresión lineal](#Regresión-lineal)

*[Regresión logistica](#Regresión-logistica)

*[Decisión Tree y Ramdon Forest](#Decisión-Tree-y-Ramdon-Forest)



---------------------------
### Regresión lineal
 ---------------------------
 
 
En el estudio de nuestro modelo de regresión lineal hemos utilizado las siguientes metodologías:

   - 1 Test_Estadisticos, 
   - 2 Correlación_Covarianza
   - 3 Asunciones
   - 4 Normalización
   - 5 Estandardizacion
   - 6 Anova
   - 7 Encoding
   - 8 Regresion_lineal
   - 9 Regresion_lineal_Metricas
   - 10 Decision_tree
   - 11 Random_Forest

   *  [Carpeta RL](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RL)

 Contiene todos los ficheros utilizados en el desarrollo del estudio, análisis y preparación de nuestro modelo de Regresión lineal mediante el cual queremos predecir los quilates de un conjunto de diamantes.


   *  [Carpeta Datos](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RL/datos)
     
   Se encuentran los archivos generados.
   
   
    # Tratamiento de datos
    import numpy as np
    import pandas as pd
    from tqdm import tqdm

    
    # Representación de Gráficos
    import matplotlib.pyplot as plt
    import seaborn as sns
    import statsmodels.api as sm

    # Test estadisticos
    import researchpy as rp
    from scipy import stats
    from scipy.stats import kstest
    from scipy.stats import levene
    from scipy.stats import skew
    from scipy.stats import kurtosistest
    import statsmodels.api as sm
    from statsmodels.formula.api import ols
    from statsmodels.multivariate.manova import MANOVA
    from sklearn.preprocessing import StandardScaler
    
     # Transformación de los datos 
    from sklearn.preprocessing import MinMaxScaler
    from sklearn.preprocessing import StandardScaler
    from sklearn.model_selection import train_test_split
    from sklearn.tree import DecisionTreeRegressor
    from sklearn.ensemble import RandomForestRegressor
    from sklearn import tree
    import math
    from sklearn.metrics import r2_score, mean_squared_error, mean_absolute_error
    from sklearn.model_selection import GridSearchCV
    from sklearn.model_selection import cross_val_score
    from sklearn.model_selection import cross_validate
    from sklearn import metrics

    

    # Codificación de las variables numéricas
    from sklearn.preprocessing import LabelEncoder # para realizar el Label Encoding 
    from sklearn.preprocessing import OneHotEncoder  # para realizar el One-Hot Encoding

    # Configuración warnings
    import warnings
    warnings.filterwarnings('once')
   
 
 
---------------------------
### Regresión logistica
---------------------------
  
  
En el estudio de nuestro modelo de regresión logistica hemos utilizado las siguientes metodologías:

  - 1. EDA
  - 2. Preparacion_Datos
  - 3. Ajuste
  - 4. Metricas
  - 5. Decision_Tree
  - 6. Random_Forest
  
 
   *  [Carpeta RLog](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RLog)

 Contiene todos los ficheros utilizados en el desarrollo del estudio, análisis y preparación de nuestro modelo de Regresión logística mediante el cual queremos predecir, el porcentaje de  personas que hiceron click en un anuncio o no.

   *  [Carpeta Datos](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/tree/main/RLog/datos)
      
   Se encuentran los archivos generados.



-----------------------------
### Decisión Tree y Ramdon Forest
--------------------------------


   *  [Carpeta RL Decision Tree](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RL/RL-11-DecisionTree.ipynb)
   
   *  [Carpeta RL Ramdon Forest](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RL/RL-12-RandomForest_tree.ipynb)

   *  [Carpeta RLog Decision Tree](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RLog/RLo-5-DecTree.ipynb)

   *  [Carpeta RLog Ramdon Forest](https://github.com/Adalab/DA-promoc-modulo3-sprint1-judith-gadea/blob/main/RLog/RLo-6-Ran-Forest.ipynb)



Integrantes
----------------

[Gadea Autric](https://github.com/gadeatric/gadeatric)

[Judith Blanco](https://github.com/Jumblan)







