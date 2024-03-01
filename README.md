# ReSource_Colaboration

## Table of contents
- README.md --> Project motivation | Goals | Methodology | Results | Conclussions | Limitations | Future Work | Contributions | Tools
- Survey.ipynb --> Sample code used for the study
- Labeler.ipynb --> Sample code used for labeling participants

## Motivation
El proyecto surge de una profunda preocupación por el fenómeno de la despoblación rural que afecta a numerosas comunidades en todo el mundo. Observamos con inquietud cómo estas áreas, que alguna vez fueron prósperas y llenas de vida, están experimentando un éxodo masivo de población, dejando tras de sí un vacío socioeconómico y cultural que amenaza su supervivencia.

Esta preocupación no solo radica en el impacto inmediato en la calidad de vida de los habitantes rurales, sino también en la pérdida de recursos humanos, tradiciones arraigadas y la disminución de la diversidad cultural, enfrentándonos a la posibilidad de perder un patrimonio invaluable, moldeado a lo largo de generaciones.

Motivado por el deseo de abordar este desafío, decidí unirme al proyecto Re-Source, un equipo multidisciplinario comprometido a afrontar esta circunstancia desde diversas perspectivas, tratando de sensibilizar y concienciar sobre la problemática, fomentando el pensamiento crítico para idear soluciones sostenibles y efectivas.

## Goals
El proyecto Re-Source tiene como objetivo principal crear un espacio de encuentro e intercambio para todas aquellas personas interesadas en abordar el fenómeno de la despoblación rural. A través de una serie de conferencias impartidas por expertos de diferentes campos, se busca ofrecer una visión integral de la problemática, fomentando el debate y la participación activa de los asistentes.

Además, después de identificar y comprender las complejas dinámicas detrás de este fenómeno, se trata de impulsar la creación de estrategias inclusivas y sostenibles que promuevan el desarrollo económico, social y cultural de las comunidades rurales en riesgo de despoblación. Para ello, se llevan a cabo sesiones prácticas en las que los participantes trabajan en grupos para identificar y diseñar soluciones adaptadas a las necesidades específicas de cada pueblo.

De este modo, a demás de lograr una asignación de pueblos óptima, lograr también una segmentación que propície un mayor entendimiento entre los integrantes de un mismo grupo, y una diversidad de opiniones a la hora de poner en común el trabajo de cada equipo.

Como parte de este proceso, mi objetivo personal es desarrollar una metodología efectiva para segmentar a los participantes en grupos de trabajo, asignándoles pueblos acorde a sus preferencias. Esta segmentación no solo busca facilitar una distribución óptima en cuanto a los intereses de grupo, promoviendo un mayor entendimiento entre los integrantes, sinó también buscar una diversidad intergrupal de perspectivas, enriqueciendo así el proceso de colaboración y la calidad de las soluciones propuestas.

Además, en mi rol como investigador de la felicidad, contribuyo al proyecto ofreciendo insights y reflexiones sobre cómo abordar la despoblación rural desde una perspectiva centrada en el bienestar y la calidad de vida de sus habitantes.

## Methodology
Iniciamos la metodología con el diseño de una encuesta que trate de captar las preferencias de los encuestados a la hora de caracterizar el pueblo ideal en el que quisieran vivir, teniendo en cuenta preguntas como la temperatura, clima, zona geográfica y población, a demás de otras que tratan de crear un perfil personal del encuestado.

La encuesta fué respondida por cerca de 100 encuestados ajenos al proyecto.

Una vez adecuado el conjunto de datos, nos preparamos para su clusterización mediante k-means. Identificamos el número óptimo de grupos con métodos como Elbow y Silhouette, así como el ajuste de hiperparámetros mediante gridsearch. 

Posteriormente, empleando un modelo de Gradient Boosting, encontramos la importancia de características en la predicción del grupo al que pertenece cada encuestado.

Éste se trata de un proceso iterativo de mejora contínua, en el que se evalúa cómo varía el rendimiento del modelo en la predicción después de procesos de feature selection y feature engineering.

Luego de tener la arquitectura de clusterización seleccionada, continuamos con un análisis estadístico de diferencias significativas entre grupos, permitiéndonos la caracterización de grupos para facilitar una óptima elección de pueblos a asignar a cada grupo.

En última instáncia, pedimos a los participantes del proyecto que respondan la misma encuesta, permitiendo predecir a qué grupo pertenece a partir de las distancias de centroides, asignándolos a los grupos adecuados.

## Results and conclusions

## Limitations

## Future work

## Contributions

## Tools
- Technologies: Python | Excel | Google Forms | Coogle
- Libraries: numpy | pandas | matplotlib | seaborn | graphviz | sklearn | scipy | statsmodels | skmultilearn | xgboost | prince | itertools
- Machine Learning Models: K-Means | Decission Tree | Random Forest | Gradient Boosting | Extreme Gradient Boosting | Support Vector Machine | Linear Regression | Ensemble approach
