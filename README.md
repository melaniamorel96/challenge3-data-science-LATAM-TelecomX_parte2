# challenge3-data-science-LATAM-TelecomX_parte2

Este proyecto busca detectar los factores que influyen en la deserción de clientes (churn) mediante técnicas de aprendizaje automático. Con base en el análisis de los datos, se construyeron modelos predictivos capaces de anticipar la probabilidad de cancelación, junto con propuestas de estrategias de retención derivadas de los resultados obtenidos.

📊 Análisis Predictivo de Churn
📌 Descripción

El propósito principal del proyecto es identificar qué variables afectan la cancelación de clientes. Para ello, se aplicaron algoritmos de machine learning que permitieron generar modelos predictivos y plantear acciones concretas para reducir la pérdida de clientes.

🤖 Modelos Implementados

🌳 Árbol de Decisión: alcanzó un accuracy del 80.05%, mostrando un equilibrio adecuado entre clases sin necesidad de normalizar datos.

👥 K-Nearest Neighbors (KNN): obtuvo un accuracy del 78.31%, aunque requiere normalización y es más sensible a la distribución de las variables.

➡️ Finalmente, se seleccionó el Árbol de Decisión como el modelo más sólido para la puesta en producción, gracias a su mejor rendimiento global.

🔍 Variables Más Influyentes

Los factores con mayor peso en la predicción de cancelación fueron:

📄 Contract (tipo de contrato)

⏳ Tenure (antigüedad del cliente)

💳 PaymentMethod (método de pago)

🧾 PaperlessBilling (facturación electrónica)

🌐 InternetService (tipo de servicio de internet)

🛠️ Metodología y Técnicas

⚖️ Tratamiento del desbalance de clases con SMOTE.

📈 Evaluación de desempeño mediante métricas de accuracy, precision y recall.

💡 Estrategias de Retención

🔒 Promover contratos de mayor duración ofreciendo beneficios.

👋 Brindar atención personalizada a clientes recientes.

💰 Incentivar el uso de pagos automáticos.

🧑‍💻 Optimizar soporte técnico y mejorar la calidad del servicio.

🧠 Implementar sistemas de monitoreo predictivo continuo.

🧰 Requisitos

🐍 Python 3.x

📦 Librerías: pandas, scikit-learn, imblearn, matplotlib, seaborn, entre otras.

▶️ Ejecución

Clonar el repositorio.

Instalar las dependencias necesarias
