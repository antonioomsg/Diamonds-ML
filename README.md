
<p align="center">
  <gif src=https://github.com/antonioomsg/Diamonds-ML/blob/master/imputs/Diamante-88735.gif" />
</p>

# Entrenamos diferentes modelos de Machine Learning para preveer los precios de los diamantes segun sus caracteristicas.

Se trata de una competición en Kaggle, que hemos iniciado los alumnos de ironhack. 
El dataset tiene los siguientes parametros:

* id           El id del diamante.
* carat        La estructura del diamante.
* cut          El corte que le han dado al diamante.
* color        El color del diamante.
* clarity      Es la calidad de los cristales del diamante.
* depth        Se trata de la profundidad del diamante.
* table        Es la multiplicación de x,y,z es decir el volumen total.
* x            Constituye parte del volumen del diamante.
* y            Constituye parte del volumen del diamante.
* z            Constituye parte del volumen del diamante.
* price        Siendo este el precio del diamante.


### Método para la limpieza de los datos.

En primer lugar he entendido la naturaleza de cada variable del dataset. 

Posteriormente he hecho una revisión de los datos del dataset, para saber si existian valores nulos, y si así fuese eliminarlos. 

Ha continuación he realizado una matriz de correlacion para determinar que columnas eran las mas importantes para explicar el precio del diamante. 

Finalmente, he decidido quitar la columna de deph por su poca correlación con el precio, además de ID ya que esto podría distorsionar nuestros modelos de Machine learning.

#### Modelos de Machine Learning

He utilizado los diferentes modelos para realizar la predicción del precio según nuestras variables predictoras. 

* KNeighborsRegressor
* MLPRegressor
* LinearRegression
* RandomForestRegresor
* Gradient Boosting Regressor

La mejor prediccion la he conseguido con Gradient Boosting.



