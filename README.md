# Prática Machine Learning - CUNEF

## Alumno: Amadeo Gustavo Ancarani

### Definición del problema:
En base a los datos de los accidentes de tráfico canadienses desde 1999 a 2014, se intenta predecir si una persona involucrada en un accidente fallecería. 

Se tomarán las caracterisicas de los accidentes y de las personas involucradas para aplicar algoritmos de Machine Learning.
Estos algoritmos aplicarán diferentes técnicas estadisticas y matemáticas para lograr obtener la mejor clasificación posible.  

El motivo principal por el cual realizamos estas estimaciones es las aseguradoras tienen que inmovilizar capital para pagar estas casuísticas. Entonces, se busca minimizar el capital inmovilizado dado que se pierde la rentabilidad de tener el dinero invertido, sin afectar el hecho de que este dinero inmovilizado estará disponible para cubrir de alguna manera las necesidades de quienes sean afectados por estos hechos.

### Scripts planteados:

Los scripts utilizados para realizar esta solución son los siguientes y realizarán las tareas desarrollas:

* **01_ETL_EDA:** Se encarga de la extracción de los datos originales, se realizan observaciones y controles utilizando el diccionario de datos. Se reserva un subconjunto de los mismos para realizar las pruebas de los algoritmos. Con el dataset restante se aplican tranformaciones y filtros necesarios para un correcto procesamiento de los datos.  


* **02_Tranformation_data_test:** Se le realizarán al dataset de test las mismas tranformaciones aplicadas en este proceso. Al final del mismo se crea una función que replicará todo el tratamiento en una única ejecución. 
 
 
* **03_Model_Training:** Se realizarán multiples pruebas, tanto de estimación con diferentes algoritmos de ML como también tranformaciones en el dataset de entrenamiento para balancear los valores observados. Todo esto se realiza para verificar cual es el método óptimo. Sobre el final del mismo, se generan variables auxiliares, las cuales estarán a cargo de almacenar tanto el procesamiento del dataset y la predicción con el threshold optimizado. Estos procesos serán utilizados  ante nuevas consultas (este paso resulta vital para la puesta en producción del modelo). 
 
 
* **04_Model_Interpretation_Conclutions:** Al modelo con mejores resultados en el dataset de test, se desarrollará una descripción sobre como trabaja internamente para lograr las predicciones realizadas. Por último, se establecen algunas alternativas a probar para intentar lograr una mejor predicción en iteraciones futuras del modelo.









