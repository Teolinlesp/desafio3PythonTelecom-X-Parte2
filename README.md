# 📊 Proyecto de Modelado Predictivo: Cancelación de Clientes

## 📌 Descripción

Este proyecto tiene como objetivo desarrollar modelos de Machine Learning para predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones.

Se aplicaron técnicas de preprocesamiento, modelado y evaluación para identificar los factores que influyen en la decisión de abandono.

---

## 🧹 Preprocesamiento de Datos

- Eliminación e imputación de valores nulos.
- Codificación de variables categóricas.
- División del dataset en entrenamiento (70%) y prueba (30%).
- Normalización aplicada en modelos sensibles a la escala (cuando fue necesario).

---

## 🤖 Modelos Implementados

- Regresión Logística
- Random Forest

Los modelos fueron evaluados mediante:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

---

## 📈 Resultados Principales

El modelo Random Forest presentó el mejor desempeño general y mayor capacidad de generalización.

Las variables más influyentes en la predicción fueron:

- Cuenta_Cargo_Total
- Cuenta_Cargo_Mensual
- Antigüedad_Meses

Estas variables indican que los factores económicos y la permanencia del cliente son determinantes en la cancelación.

---

## 🎯 Conclusiones

El modelo desarrollado permite identificar clientes con alto riesgo de abandono, facilitando la implementación de estrategias preventivas.

Se recomienda aplicar programas de fidelización, optimización de precios y promoción de servicios complementarios para reducir la tasa de cancelación.

---

## 🛠 Tecnologías Utilizadas

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## 👩‍💻 Autora

Proyecto desarrollado como práctica de Modelado Predictivo.
