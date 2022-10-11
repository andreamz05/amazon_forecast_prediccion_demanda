## Predicción de demanda usando Amazon Forecast

El forecasting consiste en permitir la estimación y previsión de la demanda de un producto o servicio, haciendo uso de los datos históricos de venta y de cualquier otra información que pueda ser útil para obtener una predicción acertada.

Dadas las consecuencias de hacer predicciones, la precisión importa de verdad:
* Si la predicción es muy baja o una subestimación, se va a sub-invertir, lo que conduce a un déficit de material e inventario, creando una mala experiencia de usuario.
* Si la predicción es muy alta, se va a sobre-invertir en productos y personal, lo que va a resultar en un desperdicio de inversión.

[Amazon Forecast](https://docs.aws.amazon.com/es_es/forecast/latest/dg/what-is-forecast.html) ofrece ahora toda la experiencia de Amazon en sus 25 años de construir el e-commerce más grande del mundo en un servicio listo para ser implementado por cualquier compañía.

Amazon Forecast es un servicio administrado que utiliza ML para entregar predicciones precisas basado en la misma tecnología que utiliza Amazon.com, pudiendo usarse para cualquier condición de negocio, como demanda y venta de producto, requerimientos de infraestructura, consumo energético, niveles de personal, entre otros. Forecast es fácil de usar y no require experiencia previa en ML, el servicio se encarga de levantar automáticamente toda la infraestructura necesaria para trabajar.

En este [notebook](./DemandaForecast.ipynb) podrá aprender a cómo hacer una predicción de demanda utilizando Amazon Forecast, preparando los datos y entrenando al servicio con los mismos. 