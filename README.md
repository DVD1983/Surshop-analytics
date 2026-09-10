Surshop Analytics - Análisis de Rentabilidad y Churn
Análisis de 1200 pedidos de e-commerce para detectar categorías más rentables, tasa de cancelación y pérdida por churn.

Jupyter Notebook
Python
Pandas

📊 KPIs Clave Detectados
Métrica	Valor	Impacto
Pedidos Analizados	1.200	Dataset completo
Margen Alto	82% en 2 categorías	Oportunidad de foco
Tasa de Cancelación	25.9%	Alerta operativa
Churn Estimado	$896k	Pérdida detectada
🎯 Resumen Ejecutivo
Este proyecto analiza 1200 transacciones para responder 3 preguntas de negocio:

¿Qué categorías realmente dejan plata?
¿Dónde se nos están cancelando los pedidos?
¿Cuánto estamos perdiendo por churn?
Hallazgo principal: 2 categorías concentran 82% del margen, pero una tasa de cancelación del 25.9% está generando $896k de churn. La oportunidad está en optimizar stock/logística de esas 2 categorías.

📁 Dataset
pedidos.csv - 1200 registros
Columnas clave: categoria, margen, estado_pedido, monto, fecha
Periodo: [agrega tu periodo]
🛠️ Stack
Python, Pandas, NumPy
Matplotlib / Seaborn para visualización
Jupyter Notebook (DeepNote)
🔍 Análisis Incluido
Rentabilidad por Categoría: Pareto de margen.
Análisis de Cancelación: Motivos y % por categoría.
Cálculo de Churn: $896k - segmentación de clientes perdidos.
Recomendaciones: Qué categorías priorizar y acciones para bajar el 25.9%.
📈 Cómo replicar
bash
git clone https://github.com/DVD1983/Surshop-analytics.git
pip install pandas matplotlib seaborn jupyter
jupyter notebook
➡️ Próximos Pasos
 Dashboard en Streamlit / Power BI
 Modelo predictivo de cancelación
 Segmentación RFM de clientes
Autor: David Alvado - DSIA 2026 | Gerli, BA
[LinkedIn] - [Portfolio]



