# 📡 Telecom X Parte 2: Machine Learning para la Predicción de Churn

Este repositorio contiene un proyecto integral de Ciencia de Datos enfocado en la retención de clientes para la empresa **Telecom X**. A través de modelos de clasificación, identificamos qué usuarios tienen mayor riesgo de cancelar su servicio.

## 📋 Objetivos del Proyecto

1.  **Limpieza y Normalización:** Tratamiento de datos JSON y escalado de variables.
2.  **Análisis Exploratorio (EDA):** Identificación de correlaciones clave mediante mapas de calor.
3.  **Modelado Predictivo:** Implementación de Regresión Logística y Random Forest.
4.  **Balanceo de Datos:** Uso de técnicas SMOTE para manejar clases desbalanceadas.
5.  **Estrategia de Negocio:** Propuestas basadas en la importancia de las variables.

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python 3.11
* **Librerías:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, Imbalanced-Learn.

## 📊 Hallazgos Principales

Tras el análisis de importancia de variables (`Feature Importance`), determinamos que los factores que más impulsan la cancelación son:
* **Tipo de Contrato:** Los contratos mes a mes son los más volátiles.
* **Antigüedad:** Los primeros 12 meses son críticos para la retención.
* **Servicios Adicionales:** Clientes sin soporte técnico o seguridad online tienden a abandonar la empresa con mayor frecuencia.

## 📉 Resultados del Modelo

El modelo final (**Random Forest + SMOTE**) logró un equilibrio óptimo, priorizando el **Recall** para asegurar que la empresa pueda intervenir antes de que el cliente finalice su contrato.

## 💡 Estrategias Recomendadas

1.  Incentivar la migración de contratos mensuales a anuales.
2.  Fortalecer el servicio de post-venta en clientes con menos de 6 meses de antigüedad.
3.  Ofrecer paquetes de servicios de seguridad como valor agregado gratuito por tiempo limitado.

---
Proyecto desarrollado por **Karina Furlan** - 2026.
