# 🏛️ Global E-commerce Sentiment Audit: Aspect Routing, Emotions & Business KPIs

Este repositorio contiene la entrega final correspondiente al laboratorio avanzado de **Casos de Uso del Análisis de Sentimiento**, aplicado de forma práctica a la auditoría automatizada de reseñas de productos multilingües en una plataforma global de comercio electrónico.

El foco central del desarrollo radica en la traducción de métricas técnicas de Machine Learning (F1-Score) hacia Indicadores Clave de Rendimiento (KPIs) financieros y operacionales accionables para la alta gerencia.

---

## 🏢 Escenario de Negocio y Toolkit Implementado

La solución automatiza la ingesta y el análisis estructural de opiniones de clientes, segmentando los flujos de datos bajo tres dimensiones analíticas:
1. **Enrutamiento por Aspecto de Negocio:** Clasificación automática del departamento afectado (*Calidad de Producto, Logística y Envío, Soporte Técnico, Finanzas/Pagos*).
2. **Detección de Emociones:** Identificación de estados psicológicos reactivos de fricción (*Ira, Frustración, Alegría, Gratitud*).
3. **Control Multilingüe:** Procesamiento síncrono de interacciones complejas en inglés y español.

---

## 📈 Cuadro de Mando Corporativo (KPIs de NLP)

A partir del set de datos de control, el sistema consolidó los indicadores de rendimiento utilizados para justificar el Retorno de Inversión (ROI):

* **KPI 1: Tasa de Detección de Fricción Crítica (CFDR):** **75.00%** (Mide el porcentaje de usuarios insatisfechos localizados de forma autónoma. Objetivo corporativo: >90%).
* **KPI 2: Tasa de Falsas Alarmas por Sarcasmo (FOAR):** **16.67%** (Mide el impacto financiero de errores de clasificación provocados por ironías sintácticas. Objetivo corporativo: <10%).
* **KPI 3: Brecha de Rendimiento Multilingüe (Gap EN vs ES):** **27 puntos de F1** de degradación en español debido al sesgo de preentrenamiento del Transformer comercial.

---

## ⚙️ Instrucciones de Despliegue Local

Garantice la consistencia del ecosistema analítico instalando las dependencias puras congeladas:

```bash
# 1. Clonar el repositorio institucional
git clone [https://github.com/TU_USUARIO/TU_REPOSITORIO.git](https://github.com/TU_USUARIO/TU_REPOSITORIO.git)

# 2. Instalar dependencias puras (requirements libre de marcas de texto)
pip install -r requirements.txt

