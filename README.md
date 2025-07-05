# 📊 TelecomX - Parte 2: Predicción de Cancelación de Clientes (Churn)

Bienvenido al proyecto **TelecomX Parte 2**, un desafío práctico de Machine Learning orientado a predecir qué clientes tienen mayor probabilidad de cancelar su servicio en una empresa de telecomunicaciones ficticia.

## 🚀 Objetivo del Proyecto

Desarrollar un modelo predictivo robusto que permita identificar los factores más influyentes en la cancelación de clientes y anticipar posibles cancelaciones, contribuyendo a estrategias de retención.

---

## 🔧 Tecnologías utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Git y GitHub
- Trello (para gestión ágil de tareas)

---

## 📁 Estructura del proyecto

```bash
├── data/
│   └── telecom_churn_clean.csv       # Dataset tratado desde la Parte 1
├── notebooks/
│   └── churn_modeling.ipynb          # Desarrollo del pipeline de ML
├── images/
│   └── correlacion_matriz.png        # Visualizaciones relevantes
├── README.md                         # Este archivo

```
---
## 🧠 Pasos desarrollados
- Carga y limpieza de datos tratados previamente
- Eliminación de columnas irrelevantes
- Codificación de variables categóricas (Encoding)
- Análisis de proporción de cancelación (Churn)
- (Opcional) Balanceo de clases
- Normalización/Estandarización si es necesario
- Análisis de correlación y selección de variables
- Visualización dirigida de variables clave
- Separación de datos (train/test)
- Entrenamiento de al menos dos modelos (uno con normalización, otro sin)
- Evaluación del rendimiento (accuracy, precision, recall, F1, matriz de confusión)
- Interpretación y comparación de modelos
- Análisis de importancia de variables
- Conclusiones estratégicas para el negocio

---

## 📌 Recomendaciones
Usa git desde el inicio para versionar tu trabajo.

Registra tu progreso en el tablero Trello para practicar metodologías ágiles.

Comunica tus resultados con claridad técnica y visión estratégica.

## ✨ Créditos
Desafío diseñado como parte del programa de formación de Alura Latam.