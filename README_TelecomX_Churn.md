
# 📊 Telecom X – Churn Prediction & Retention Strategy (Parte 2)

## 📌 Descripción del Proyecto

Este proyecto desarrolla un modelo predictivo de **fuga de clientes (Churn)** para Telecom X, integrando análisis exploratorio de datos (EDA) y técnicas de Machine Learning con el objetivo de:

- Identificar patrones de cancelación.
- Estimar la probabilidad individual de abandono.
- Proponer estrategias de retención basadas en evidencia cuantitativa.

El enfoque combina análisis técnico y visión estratégica de negocio, permitiendo transformar datos históricos en decisiones accionables.

---

# 🎯 Objetivos del Proyecto

## Objetivo General
Desarrollar un modelo predictivo capaz de identificar clientes con alta probabilidad de cancelación y generar recomendaciones estratégicas para reducir la tasa de churn.

## Objetivos Específicos

- Analizar variables determinantes del abandono.
- Construir y evaluar modelos de clasificación.
- Medir desempeño mediante métricas robustas (Accuracy, Precision, Recall, F1-Score, AUC-ROC).
- Identificar segmentos de alto riesgo.
- Proponer acciones estratégicas basadas en resultados analíticos.

---

# 🏗️ Estructura del Proyecto

TelecomX-Churn-Prediction/
│
├── TelecomX_Parte_2.ipynb
├── data/
│   └── dataset.csv
├── README.md
└── requirements.txt

---

# 🛠 Metodología

## 1️⃣ Preparación de Datos
- Limpieza y tratamiento de valores nulos.
- Codificación de variables categóricas.
- Normalización y transformación de variables.
- Separación en conjunto de entrenamiento y prueba.

## 2️⃣ Modelado Predictivo
Se entrenaron modelos de clasificación para estimar la probabilidad de churn.

## 3️⃣ Evaluación del Modelo

Se utilizaron métricas estándar de clasificación:

- Accuracy
- Precision
- Recall
- F1-Score
- Matriz de Confusión
- Curva ROC
- AUC (Área Bajo la Curva)

La métrica clave para el negocio es el Recall en la clase Churn, dado que el objetivo es minimizar falsos negativos.

---

# 🔎 Principales Hallazgos Analíticos

## 1️⃣ Antigüedad como Variable Crítica
La probabilidad de abandono es significativamente mayor durante los primeros meses de relación contractual.

## 2️⃣ Contratos Mensuales
Los clientes con modalidad "Mes a Mes" presentan mayor volatilidad y tasa de cancelación.

## 3️⃣ Sensibilidad al Precio
Cargos mensuales elevados se asocian a mayor riesgo de churn en ciertos segmentos.

## 4️⃣ Servicios Adicionales
Clientes con menor número de servicios complementarios presentan menor nivel de vinculación y mayor facilidad de abandono.

## 5️⃣ Método de Pago
Determinados métodos de pago presentan tasas de abandono desproporcionadamente altas.

---

# 💡 Recomendaciones Estratégicas

- Implementar programas de retención temprana.
- Incentivar migración a contratos anuales.
- Promover servicios adicionales como mecanismo de fidelización.
- Integrar el modelo al CRM para alertas automáticas.
- Ejecutar pruebas A/B para medir ROI de estrategias.

---

# ⚠️ Limitaciones

- Dependencia de la calidad de los datos históricos.
- No incorpora variables macroeconómicas externas.
- Riesgo de degradación del modelo en entorno productivo.
- Requiere monitoreo y recalibración periódica.

---

# 🚀 Impacto Esperado

- Reducción de churn temprano.
- Optimización del presupuesto de retención.
- Incremento del Customer Lifetime Value (CLV).
- Mayor estabilidad de ingresos recurrentes.

---

# 🧰 Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📌 Conclusión

El churn en Telecom X es estructural y predecible. La implementación del modelo predictivo permite transformar la gestión comercial desde un enfoque reactivo hacia una estrategia preventiva basada en datos.
