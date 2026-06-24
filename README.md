# Unidad-16-Casos-de-uso-del-an-lisis-de-sentimiento
Unidad 16 · Casos de uso del análisis de sentimiento

# 📉 Reputational Crisis Management: Sentiment Analysis & Metrics Dashboard

Este repositorio contiene el diseño analítico y la simulación del **esquema estratégico de métricas operativas de Procesamiento de Lenguaje Natural (NLP)** aplicado al caso de uso de alta prioridad corporativa: **Gestión y Detección Temprana de Crisis Reputacionales**.

A lo largo del proyecto se formalizan e implementan los indicadores clave exigidos por la alta gerencia para transformar variables de texto no estructurado en métricas financieras y operativas de retorno de inversión (ROI).

---

## 🏛️ Caso de Uso y Objetivos Estratégicos

El pipeline de monitoreo está diseñado para operar sobre flujos de redes sociales masivas con los siguientes objetivos:
1. **Reducción de Latencia:** Detectar anomalías en el humor social digital en una ventana de tiempo inferior a los 15 minutos (*Mean Time to Detect*).
2. **Alertas Autónomas:** Activar protocolos de contingencia de Relaciones Públicas (RRPP) de manera automática al cruzar el umbral crítico de peligro.
3. **Optimización Financiera:** Proteger el valor de marca (*Brand Equity*) mitigando crisis operativas antes de su masificación mediática.

---

## 📊 Arquitectura de Indicadores (KPIs del Sistema)

El esquema implementa cuatro métricas fundamentales extraídas de la ejecución síncrona en producción:

* **Índice de Sentimiento Neto (Net Sentiment Index - NSI):** Escalar probabilístico ajustado bajo la relación $NSI = \frac{Pos - Neg}{Total}$ para monitorizar la tendencia general de la opinión pública (Punto crítico registrado de **-0.77** durante el incidente).
* **Tiempo Medio de Detección (MTTD):** Indicador temporal fijado en **15 minutos** para medir la rapidez de aislamiento de anomalías.
* **Data Coverage Ratio (98.40%):** Porcentaje de cobertura semántica sobre el flujo total de datos entrantes para asegurar representatividad estadística.
* **Classification Accuracy (94.25%):** Métrica de calidad que mide el nivel de acierto predictivo del modelo frente a auditorías de control.

---

## ⚙️ Instrucciones de Despliegue Local

Garantice la consistencia del entorno analítico ejecutando los siguientes pasos en su terminal:

```bash
# 1. Clonar el repositorio
git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)

# 2. Instalar el entorno reproducible
pip install -r requirements.txt

# 3. Ejecutar el script analítico en su Jupyter Server o Google Colab:
# Archivo: Unidad_16_·_Casos_de_uso_del_análisis_de_sentimiento.ipynb
