# Surshop Analytics - $896k de Churn Detectado

> Análisis de **1.200 pedidos** de e-commerce para detectar dónde se pierde plata. Proyecto real de auditoría para Tienda Nube.

### 📊 KPIs Clave Detectados

| Métrica | Valor | Impacto |
| :--- | :--- | :--- |
| **Pedidos Analizados** | 1.200 | Dataset completo |
| **Margen Alto** | **82% en 2 categorías** | Oportunidad de foco |
| **Tasa de Cancelación** | **25.9%** | Alerta operativa |
| **Churn Estimado** | **$896k** | Pérdida detectada |

### 🎯 Resumen Ejecutivo
Este proyecto responde 3 preguntas de negocio que todo dueño de e-commerce se hace:

1.  ¿Qué categorías realmente dejan plata?
2.  ¿Dónde se nos están cancelando los pedidos?
3.  ¿Cuánto estamos perdiendo por churn?

**Hallazgo principal:** 2 categorías concentran el 82% del margen, pero una tasa de cancelación del 25.9% está generando $896k de churn. La oportunidad está en optimizar stock y logística de esas 2 categorías.

### 📁 Dataset
`pedidos.csv` - 1200 registros
- **Columnas clave:** categoria, margen, estado_pedido, monto, fecha
- **Periodo:** Ene-Mar 2024 - Dataset Surshop

### 🛠️ Stack
- **Python, Pandas, NumPy**
- **Matplotlib / Seaborn** para visualización
- **Jupyter Notebook** (DeepNote)

### 🔍 Análisis Incluido
- **Rentabilidad por Categoría:** Pareto de margen
- **Análisis de Cancelación:** Motivos y % por categoría
- **Cálculo de Churn:** $896k + segmentación de clientes perdidos
- **Recomendaciones:** Qué categorías priorizar y acciones para bajar el 25.9%

### 🚀 Cómo replicar
```bash
git clone https://github.com/DVD1983/Surshop-analytics.git
pip install pandas matplotlib seaborn jupyter
jupyter notebook




