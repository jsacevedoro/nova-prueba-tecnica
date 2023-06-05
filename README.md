# Modelo para predicción de impagos

**Objetivo:** <br> Contruir un modelo para identificar a los clientes que no pagarán su deuda de la tarjeta de crédito el próximo mes. Para ello se analiza información socio-demográfica de los clientes como Edad, Sexo, Estado civil y nivel de escolaridad, como también datos sobre el pago, deuda y retraso de los últimos 6 meses. 

**Mapa:**

1. *exploracion.ipynb* : Análisis exploratorio del conjunto de datos. 

2. *limpieza_inicial.ipynb* : Limpieza y preparación inicial de los datos, identificando y eliminando valores inconsistentes.

3. *ingenieria_caracteristicas.ipynb* : Análisis detallado de las variables explicativas en relación con la variables objetivo. Se realiza segmentación en deciles y se proponen nuevos atributos y métricas de negocio. 

4. *seleccion_modelo.ipynb* : Resolución del problema de desbalance de clase y construcción de un modelo de ML, usando el algortimo XGBoost y obteniendo precisión mayor al 80% en todas las métricas de desempeño.

