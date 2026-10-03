# E-Commerce Data Analysis & Business Hypothesis Validation

Este repositorio contiene el Análisis Exploratorio de Datos (EDA), bivariado y multivariado enfocado en evaluar el comportamiento de compra de los usuarios, el abandono de clientes (*churn*), la efectividad de los programas de fidelización y la evolución temporal de los ingresos.

## 📊 Resumen del Proyecto

El objetivo principal es validar cuantitativamente cuatro hipótesis de negocio estratégicas para guiar la toma de decisiones en marketing, producto y retención:

1. **H1 - Fidelización y Churn:** Evaluar si el nivel de membresía y la suscripción al newsletter reducen la tasa de retiro.
2. **H2 - Navegación Web vs. Monetización:** Determinar la relación entre la duración de la sesión/páginas vistas y el Ticket Promedio (AOV).
3. **H3 - Desempeño Geográfico:** Analizar los ingresos acumulados y el *churn* por región y tamaño de mercado.
4. **H4 - Serie Temporal de Ingresos:** Analizar la estabilidad y estacionalidad de la facturación mensual (2020-2026).

---

## 🔍 Principales Hallazgos

* **H1 (Refutada):** La suscripción al newsletter y los niveles de membresía (Free, Silver, Gold, Platinum) no reducen el *churn*, manteniéndose en una tasa promedio homogénea (~8% - 10%).
* **H2 (Refutada):** Correlación nula ($r = 0.00$) entre la duración de la sesión web y el valor de la compra (AOV).
* **H3 (Validada Parcialmente):** *Americas* (Mercado Grande) y *Asia* (Mercado Pequeño) generan el mayor volumen de ventas. *África* registra la menor facturación y la tasa de *churn* más alta (~15%).
* **H4 (Validada Parcialmente):** La facturación mensual fluctúa de manera cíclica entre $26,000 USD y $37,000 USD, con un promedio constante de **$31,487.18 USD**.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python 3.10+
* **Procesamiento de Datos:** Pandas, NumPy
* **Visualización de Datos:** Matplotlib, Seaborn
* **Entorno de Desarrollo:** Google Colab

---

