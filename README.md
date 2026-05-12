Optimización de Modelo RandomForest.

Clasificación binaria sobre el dataset de diabetes de scikit-learn, aplicando selección de características, pipeline y validación cruzada.

Tecnologías: 
Python · pandas · NumPy · scikit-learn

Qué hace?: 
Convierte un problema de regresión en clasificación binaria
Selecciona las 4 características más relevantes con SelectKBest y el test ANOVA F
Crea un pipeline con normalización (StandardScaler) y clasificador (RandomForestClassifier) para evitar perdida de datos(data leakage)
Evalúa el modelo con validación cruzada de 5 folds para una métrica más fiable que un solo split

Resultados: 
Precisión en test0.74
Media validación cruzada (cv=5)~0.68
