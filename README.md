# Análisis Enfermedades Cardiacas

El siguiente dataset contiene 13 columnas con información que podría ser relevante a la hora de entender por qué algunas personas tienen problemas cardiacos y por qué otras no.

 - Age
 - Sex: (1=male, 0= female)
 - Cp: Chest pain type
 - trestbps: resting blood pressure (in mm Hg on admission to the hospital)
 - cholserum: cholestoral in mg/dl
 - fbs(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
 - restecgresting: electrocardiographic results
 - thalachmaximum: heart rate achieved
 - exangexercise: induced angina (1 = yes; 0 = no)
 - oldpeakST: depression induced by exercise relative to rest
 - slopethe: slope of the peak exercise ST segment
 - ca: number of major vessels (0-3) colored by flourosopy
 - thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
 - target1 or 0
 
 
## Primera etapa: Eliminar sesgos.
Existe mucho "conocimiento colectivo" sobre problemas cardiacos, en una primera etapa se requiere analizar el dataset para validar si las siguientes afirmaciones son correctas. 

1. Solo la gente mayor tiene problemas cardiacos
2. Si mi colesterol está bajo entonces no tengo por qué preocuparme
3. Las mujeres tienen menores probabilidades de tener problemas cardiacos
4. Si tengo el colesterol alto y la presión arterial alta, entonces me sentiría mal.
5. El ejercicio es beneficioso para mi corazón.
6. Si tengo dolor en el pecho, entonces debo preocuparme porque tendré un infarto.


**NOTA: puede que no todas las afirmaciones se puedan responder utilizando este datsaset, en caso de ser así indicar por qué no se puede**

## Segunda etapa: Insigths.
Nombrar al menos 2 conclusiones interesantes que se puedan encontrar a través del análisis de este dataset.

## Tercera etapa: Modelo Predictivo.
En caso que sea posible, crear un modelo para predecir la presencia de problemas cardiacos. En este punto se debe indicar:

 - ¿Qué tipo de modelo se usará?
 - Metodología de entrenamiento. ¿Cómo se dividió la data de entrenamiento y prueba?¿Qué métricas se usarán para medir que el modelo funcione bien?
 - ¿Qué columnas entrarán al modelo? ¿Por qué?
 - ¿Se usó alguna metodología de limpieza? ¿Por qué?
 - Resultados obtenidos.
 
## Algunas consideraciones

1. Esto es una guía para que más o menos tengas una idea sobre como abordar el análisis, puede agregar todo lo que estimes conveniente.
