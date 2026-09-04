# Surshop-analytics
Análisis de 1200 pedidos: margen 82% en 2 categorías, 25.9% cancelación y $896k churn detectado

SURSHOP - Análisis de Rentabilidad, Cancelaciones y Churn

📌 Problema de Negocio
SurShop vende por 4 canales (Web, Marketplace, Instagram, Tienda MDP) pero no sabe dónde gana plata real ni por qué se le van clientes de ticket alto.

Preguntas que responde este proyecto:

¿Qué categoría deja más margen real (solo entregados)?
¿Qué canal tiene mayor tasa de cancelación y por qué?
¿Qué clientes de alto valor están en churn?

📊 Dataset
clientes.csv - 500 clientes, segmento, ciudad, fecha alta
productos.csv - costo, precio, categoría (Abrigos, Tablas, Remeras, Bermudas, Accesorios)
pedidos.csv - 1.200 pedidos, canal, estado, fecha
detalle_pedido.csv - productos por pedido, cantidad, precio unitario
🔍 Hallazgos Clave
1. Margen concentrado: 82% en 2 categorías

Abrigos: $13.56M (42%)
Tablas: $12.88M (40%)
Remeras: $3.45M, Bermudas: $1.64M, Accesorios: $0.93M
Insight: La rentabilidad depende del invierno. Cada tabla deja $140k de margen pero es poco volumen.
2. Cancelación por canal

Marketplace: 25.9% cancela (127 pedidos) - peor canal
Tienda MDP: 24.9% (134 pedidos, 48 son Remeras por probador)
Instagram: 22.8%
Web: 20.5% (mejor canal, cliente con intención clara)
Insight: No es problema de producto, es operativo (stock desincronizado en Marketplace).
3. Churn de alto valor

Cliente 407 La Plata - Recurrente - $458k margen - Última compra 09-07-2026 (53 días)
Cliente 427 Tandil - Recurrente - $438k margen - Última compra 11-07-2026 (51 días)
Ambos compran Tabla + Abrigo (ticket alto). $896k en riesgo.
💡 Recomendaciones
Pausar Tablas en Marketplace, dejar solo Abrigos con stock profundo. Sincronizar stock cada 2hs.
Bundle: Buzo + Remera Térmica para subir ticket de Abrigos en Tienda MDP.
Campaña recupero 1:1 a 407 y 427: asunto "¿Tu tabla necesita service?" + 15% OFF Abrigos + 12 cuotas sin interés en Tablas.
🛠️ Stack
Python, Pandas, Matplotlib, Deepnote, EDA, Business Intelligence

📁 Estructura del repo
/data - csv originales
/notebooks - notebook limpio con markdown
/images - 3 gráficos (margen_categoria.png, cancelacion_canal.png, top_clientes.png)
/README.md
requirements.txt
🚀 Próximos pasos (para escalar a Senior)
 RFM Segmentation
 Cohort Retention
 Modelo predictivo de churn con scikit-learn
 Dashboard Streamlit
Autor: David Alvado - La Plata, Buenos Aires
Link Deepnote: [https://deepnote.com/workspace/David-Alvado-5a46672b-e0cc-4fa6-b7f6-d4a694c82af0/project/SURSHOP-2097dc6c-8719-471d-a670-63b078b55341/notebook/SURSHOP-b2e77e0f632a4468959f05dfba6aa55c?utm_source=share-modal&utm_medium=product-shared-content&utm_campaign=notebook&utm_content=2097dc6c-8719-471d-a670-63b078b55341]
LinkedIn: [www.linkedin.com/in/david-alvado-datos]

