# 📊 Análisis Exploratorio y Estrategia de Ventas (Python EDA)

## 🎯 Contexto de Negocio:
La empresa presentaba una visibilidad limitada sobre el rendimiento real de sus ventas debido a la **fragmentación de datos** y a una alta presencia de **outliers (ruido estadístico)**. Esto provocaba:
* **Incertidumbre en la planeación:** Metas de venta poco realistas basadas en promedios "inflados" por ventas atípicas.
* **Riesgo de Inventario:** Falta de stock en regiones con picos de demanda no identificados y sobre-stock en áreas de baja rotación.
* **Estacionalidad desconocida:** Incapacidad para predecir cuándo y dónde se concentraría la mayor parte del volumen.

---

## 🛠️ Solución y Metodología
Desarrollé un **Análisis Exploratorio de Datos (EDA)** sistemático utilizando el rigor científico de mi formación doctoral para limpiar, transformar y visualizar los insights críticos:
1. **Saneamiento de Datos:** Limpieza y tratamiento de outliers (Scanning 50%) para normalizar las métricas.
2. **Correlación Estadística:** Identifiqué una correlación de **0.92** entre unidades y valor, validando el volumen como principal driver de ingresos.
3. **Análisis de Dispersión:** Uso de Boxplots para segmentar el comportamiento por categorías y regiones.

**Stack Tecnológico:** `Python` | `Pandas` | `Seaborn` | `Matplotlib` | `Looker Studio`

---

## 💡 Conclusiones y Recomendaciones de Decisión

Basado en el análisis, se proponen las siguientes acciones estratégicas:

1. **Cambio de Métrica Clave:** Dado el sesgo a la derecha en la distribución de ventas, **recomiendo utilizar la Mediana en lugar de la Media** para establecer los presupuestos de ventas de 2026. Esto evitará proyecciones inalcanzables que desmotivan al equipo comercial.
2. **Focalización Geográfica:** El análisis reveló que la región **"TOTAL AUTOS SCANNING MÉXICO"** domina ampliamente el volumen. Se debe priorizar el gasto de marketing en este nodo para maximizar el ROI.
3. **Estrategia:** Detecté productos con bajo volumen de unidades pero alto valor total (ventas extraordinarias). Recomiendo crear un segmento "Premium" para estos SKUs para capturar margen sin saturar la cadena de suministro.

---


<img width="784" height="584" alt="image" src="https://github.com/user-attachments/assets/8ca8f26d-5044-47d8-8412-4b83c8122444" />


---
**Susana Olvera Moreno
