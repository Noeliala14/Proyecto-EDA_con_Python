# Proyecto-EDA_con_Python
Este repositorio contiene un análisis exploratorio de datos (EDA) centrado en las campañas de marketing directo de una institución bancaria. El objetivo principal fue utilizar Python y la librería Pandas para limpiar, transformar y analizar dos conjuntos de datos (bank-additional.csv y customer-details.xlsx), con el fin de identificar patrones clave y entender el comportamiento de los clientes. 
El análisis se enfoca en determinar qué factores influyen en la suscripción de un depósito a plazo.

# 1. Transformación y Limpieza de los Datos
Fuentes de datos: Se trabajó con dos datasets: bank-additional.csv (información de la campaña) y customer-details.xlsx
Integración de datos: Se realizó la fusión de ambos conjuntos de datos en un único DataFrame para un análisis unificado.
Manejo de valores faltantes y duplicados: Se identificaron y gestionaron los valores faltantes para asegurar la calidad de los datos. 
Transformación de datos: Se convirtieron variables categóricas a numéricas

# 2. Análisis Descriptivo de los Datos
Estadísticas de la campaña: Se calcularon métricas clave como la tasa de éxito de la campaña (tasa de suscripción) y el recuento de contactos por cliente.

Correlación de variables: Se calculó la correlación entre variables para identificar las relaciones entre las características de los clientes (como la edad y la duración de la llamada) y la suscripción al producto


# 3. Visualización de los Datos
-Librerías de visualización: Se utilizaron librerías de Python como Matplotlib y Seaborn para crear visualizaciones claras y efectivas.

-Gráficos clave: Se crearon visualizaciones para ilustrar los hallazgos:

-Distribución de variables: Histogramas y gráficos de barras para mostrar la distribución de la edad, la ocupación y el estado civil.

-Análisis de correlación: Un gráfico de dispersión que relaciona la edad con la tasa de interés (euribor3m) para observar patrones en la suscripción del producto.

# Hallazgos y Conclusiones del Análisis
Factores de éxito de la campaña: El análisis demostró una fuerte correlación entre la duración de la llamada y la suscripción del producto. Los clientes que recibieron llamadas más largas tenían una mayor probabilidad de suscribir el servicio.

Impacto demográfico: La edad de los clientes no tuvo una correlación significativa con la tasa de suscripción. Sin embargo, se observó que clientes con un mayor número de visitas mensuales a la web eran más propensos a aceptar la oferta.

Éxito de campañas previas: El resultado de campañas de marketing anteriores (poutcome) demostró ser un predictor clave; los clientes que ya habían tenido un éxito previo eran más propensos a suscribir el producto.
