# Challenge numero 3
<h1>Analisis de evacion de cliente</h1>
<h2>Objetivo</h2>
- Predecir que cliente tiene mayor probabilidad de avandonar el servivio 
<h2>Pasos realizados </h2>

- Preparar los datos para el modelado es decir realizar el tratamiento, codificación y normalización de los datos.

- Realizar análisis de correlación y selección de variables.

- Entrenar los modelos de clasificación.

- Evaluar el rendimiento de los modelos con métricas.

- Interpretar los resultados, incluyendo la importancia de las variables.

<h2>Herramientas y aplicaciones que se utilizaron fueron:</h2>

- Trello.

- Github.

- Google Colab.

- libreria de Python:
    - Pandas para la Manipulación y análisis de datos.
    - NumPy para la Operaciones numéricas.
    - Matplotlib para realizar las Visualización de datos.
    - Seaborn permite Visualizaciones estadísticas.
    - sklearn para machine learning.
<h2>Modelos predictivos implementados:</h2>

- Modelo Random Fores Regresion.
- KNN (Calificador del vecino mas cercano)

<h2>Utilizacion de metricas claves</h2>

- Exactitud (Accuracy).

- Precisión.

- Recall(Sencibilidad).

- F1-score.

<h2>Diccionario de datos.</h2>

- customerID: número de identificación único de cada cliente
- Churn: si el cliente dejó o no la empresa
- gender: género (masculino y femenino)
- SeniorCitizen: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
- Partner: si el cliente tiene o no una pareja
- Dependents: si el cliente tiene o no dependientes
- tenure: meses de contrato del cliente
- PhoneService: suscripción al servicio telefónico
- MultipleLines: suscripción a más de una línea telefónica
- InternetService: suscripción a un proveedor de internet
- OnlineSecurity: suscripción adicional de seguridad en línea
- OnlineBackup: suscripción adicional de respaldo en línea
- DeviceProtection: suscripción adicional de protección del dispositivo
- TechSupport: suscripción adicional de soporte técnico, menor tiempo de espera
- StreamingTV: suscripción de televisión por cable
- StreamingMovies: suscripción de streaming de películas
- Contract: tipo de contrato
- PaperlessBilling: si el cliente prefiere recibir la factura en línea
- PaymentMethod: forma de pago
- Charges.Monthly: total de todos los servicios del cliente por mes
- Charges.Total: total gastado por el cliente
