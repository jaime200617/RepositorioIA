# Tema 2 Historia y Ciclo de Vida de una Aplicación de Aprendizaje de Máquina
## Por: Jaime Londoño

### Introduccion Machine Learning
- Programación Lineal: Entradas Datos y Reglas. Salida: Resultado
- Machine Learning: Entradas Respuestas y Datos. Salida: Reglas

#### Fases:
1 Identificación del problema: Definir el objetivo del proyecto y como el aprendizaje de máquina puede ayudar a alcanzarlo.
2 Recolección de datos: Datos relevantes, precisos y representativos del problema.
3 Preparación de datos: Lmpiar datos, manejar valores faltantes, normalizar, escalar caracteristicas, dividir en conjuntos.
4 Ingenieria de modelos: Selección de algoritmos, feature engineering, ajustes hiperparámetros. 
5 Evaluación del modelo: Medir precisión, exactitud, recall, F1-score.

   Parámetros: Variables numéricas internas que el modelo aprende
   Hiperparámetros: Variables numércias externas que nosotros debemos fijar al momento de hacer el algoritmo.

6 Despliegue: Ponerlo en producción, integrarlo con aplicaciones.

   Requerimientos de diseño: Tipo de predicción (Tiempo real o por lotes), latencia, rendimiento (numero solicit  udes por segundo)
   Alternativas de despliegue: En la nube, on the edge.

7 Mantenimiento y actualización: Monitoreo, actualizaciones periódicas, ajustar parámetros.

   Fallos de software: Código para despliegue por ejemplo
   Fallos en el modelo: Deriva de datos, Deriva de concepto.
   Monitoreo con métricas globales.
   Distribuciones estadísticas.

#### HISTORIA
- Arthur Samuel (1959), disciplina que estudia habilidad de aprendizaje de computadores.
- Tom Mitchel (1998), aprendizaje computacional.
- 1950 Artificial Intelligence, 1980 Machine Learing, 2010 Deep Learning.

Medicina: Reconocimiento de imagenes con cáncer.
Políticas publicas: predicción de riesgo (delitos, violencia, etc.)
Fiscalización: detección de fraude.
Manufactura: predicción de fallas
Agricultura: identificación de cultivos
Comercio: segmentación de clientes.

Sistemas Bioinspirados: Algoritmos genéticos, Algoritmos de enjambre, Redes Neuronales.

Aprendizaje supervisado: Clasificaciones (Arboles de decisión, Naive Bayes, XGB, Redes neuronales), Regresiones (Regresión lineal, Arbol de regresión, regresión Logística, Redes neuronales).

Aprendizaje no supervisado: Agrupaciones (Clustering).

