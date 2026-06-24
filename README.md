# 📉 Enterprise Sentiment Audit: Metrics Framework, Confusion Matrix & Error Cases

Este repositorio contiene la entrega final del laboratorio de **Casos de Uso del Análisis de Sentimiento**, diseñado bajo un enfoque analítico avanzado para la gestión de crisis reputacionales corporativas.

La solución aborda de manera directa los desafíos de MLOps relacionados con el desbalance severo de clases y las limitaciones lingüísticas intrínsecas del procesamiento de lenguaje natural (NLP).

---

## 🎯 Objetivos de Ingeniería e Impacto Crítico

1. **Evaluación de Robustez:** Implementación de métricas insensibles al desbalance de clases (**F1-Score Macro**) y mapeo visual mediante **Matrices de Confusión** utilizando `scikit-learn`.
2. **Auditoría de Casos de Error:** Identificación y aislamiento automatizado de fallas sistemáticas del modelo provocadas por **sarcasmo** e **ambigüedad sintáctica**.
3. **Análisis de Espectro Técnico:** Comparación crítica del rendimiento, costos y latencias entre enfoques léxicos clásicos frente a arquitecturas profundas basadas en Transformers.

---

## 📊 Matriz de Confusión y Reporte de Inferencia

El sistema incorpora un entorno de validación cruzada que expone el balance real de Falsos Positivos y Falsos Negativos en momentos de estrés operacional:

```text
======================================================================
🎯 REPORTE DE EVALUACIÓN DE CALIDAD DEL MODELO (NLP)
======================================================================
🔹 F1-Score Global (Macro Average): 0.69
🔹 F1-Score Clase Crítica (NEGATIVE): 0.84
🔹 Precision Clase Crítica (NEGATIVE): 1.00
🔹 Recall Clase Crítica (NEGATIVE): 0.73
======================================================================


