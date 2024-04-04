# Desafío Técnico - Análisis de Datos y Segmentación de Clientes

Este repositorio contiene la solución a un desafío técnico enviado como parte de un proceso de entrevista para una posición de trabajo. El desafío consistió en analizar datos históricos de una empresa y realizar un modelo de segmentación de clientes. A continuación se proporciona una descripción del desafío y los resultados obtenidos.

## Desafío 1: Informe

### Contexto del Desafío
La empresa desea comprender el estado de su negocio en tres pilares fundamentales: ventas, clientes y campañas. Para ello, se proporcionó un conjunto de datos transaccionales que contiene información sobre pedidos, clientes, productos, ingresos, descuentos, entre otros.

### Resultados del Análisis Descriptivo

### Ingresos Netos: 
Se observó una tendencia cíclica en los ingresos, con disminuciones durante los meses más cálidos.
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/65d9f5cb-c5d9-4ef1-afea-480072425acd)

### Total Unidades Vendidas:
La demanda de productos mostró un patrón similar al de los ingresos netos, con descensos en los últimos tres meses.
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/eeb7eabd-0e55-48ff-99e9-c9d5f2ef998a)

### Productos Más Vendidos: 
Los productos D y B fueron los más vendidos, lo que coincide con los patrones de ingresos y unidades vendidas.
Distribución de Compra y Tipo de Canal: Se detectaron cambios en los canales de compra y tipos utilizados por los clientes, con un aumento en los canales B y F en los últimos meses.
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/639442ab-1577-4524-8e11-38e84ab9d8d1)

### Análisis RFM: 
Hubo un aumento en clientes que realizaron compras en un rango de valor más alto en los últimos meses.
### Ventas por Campaña: 
Se observó una variación en la preferencia de las campañas, con un aumento en las campañas D y C en los últimos tres meses.
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/ba4cc3f8-fa0b-4cd4-ab3f-7739e6596757)


### Eficiencia de Campañas: 
La eficiencia de las campañas se mantuvo alta, con un porcentaje de eficacia mayor al 80%.
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/4bc22ddd-b7fa-417d-a660-4a77d4ac4230)


## Desafío 2: Modelo de Segmentación de Clientes
Método de Segmentación Utilizado
Se implementó un modelo de segmentación de clientes utilizando la técnica de segmentación RFM (Recency, Frequency, Monetary).

### Variables Utilizadas para la Segmentación
Las variables utilizadas para segmentar a los clientes fueron:

Recency: Última fecha de compra
Frequency: Frecuencia de compra
Monetary: Monto total gastado

### Métodos de Segmentación Utilizados
Se utilizó el método del codo para determinar el número óptimo de clusters en el modelo de segmentación RFM.

Se utilizó el coeficiente de silueta para validar la calidad de los clusters obtenidos y evaluar la cohesión y separación de los clusters.

### Resultados de la Segmentación
Número de Segmentos Identificados: Se identificaron 4 segmentos de clientes.
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/61ae5180-ff7d-49a1-b056-56aacc2fea7a)
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/6fa70afc-003f-4393-b817-9ca4ef5fdbc1)
![image](https://github.com/Yesi0/desafio_tecnico/assets/125078076/0175196c-4606-4f0c-b012-d3860e3b5ac1)


Descripción de Segmentos: Cada segmento se describió en función de sus características de recency, frequency y monetary, proporcionando una comprensión clara de los diferentes grupos de clientes.

# Conclusiones
El análisis descriptivo proporcionó información sobre el estado actual del negocio en relación con las ventas, clientes y campañas. Además, el modelo de segmentación de clientes permitió identificar grupos de clientes con características similares, lo que puede ser utilizado para desarrollar estrategias de marketing y ventas más efectivas.
