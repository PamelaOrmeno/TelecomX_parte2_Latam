# 📊 Challenge TelecomX - Parte 2

Análisis y predicción de cancelación de clientes (Churn) en una empresa de telecomunicaciones.  
Este proyecto tiene como objetivo identificar patrones de comportamiento que lleven a la cancelación del servicio y construir modelos predictivos para anticipar este fenómeno.

---

## 🔧 Requisitos

Para ejecutar este proyecto localmente necesitas tener instalado lo siguiente:

- Python 3.8 o superior
- Jupyter Notebook o JupyterLab
- pip (gestor de paquetes de Python)

Además, las siguientes bibliotecas de Python deben estar instaladas:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📦 Instalación

1. **Clona este repositorio** en tu máquina local:

```bash
git clone https://github.com/PamelaOrmeno/TelecomX_parte2_Latam.git
cd TelecomX_parte2_Latam
```

2. **Crea un entorno virtual** (opcional pero recomendado):

```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

3. Instala las dependencias necesarias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Abre el notebook con Jupyter:

```bash
jupyter notebook TelecomX_parte2_Latam.ipynb
```

---

## 📁 Estructura del Proyecto

```plaintext
├── Data/
│ └── TelecomX_Data_Transformada.csv
├── README.md 
├── TelecomX_parte2_Latam.ipynb 
```

## 🔍 Objetivos

- Analizar el comportamiento de los clientes que cancelan el servicio.
- Preparar los datos para modelado predictivo.
- Explorar las relaciones entre variables y el churn.
- Construir y evaluar modelos de clasificación.
- Identificar las variables más influyentes.
- Proponer recomendaciones para reducir la cancelación.

## 🛠 Herramientas y Librerías

- Python 3.x
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Scikit-learn

## 🧾 Pasos Realizados

### 1. Carga y Exploración Inicial

- Carga del dataset.
- Vista de columnas y estructura.
- Revisión de valores nulos.

### 2. Preparación de los Datos

- Eliminación de columnas irrelevantes.
- Unificación de valores.
- Codificación de variables categóricas.
- Verificación del desbalance de clases.
- Escalado de variables con Min-Max Scaling (cuando corresponde).

### 3. Análisis Exploratorio

- Matriz y mapa de correlación.
- Análisis dirigido con gráficos (`tenure` vs `churn`, etc.).

### 4. Modelado Predictivo

- Separación del dataset en entrenamiento y prueba (70/30).
- Creación de modelos:
  - Regresión Logística (requiere normalización).
  - Árbol de Decisión (sin normalización).
- Evaluación:
  - Accuracy, precisión, recall, F1-score.
  - Matriz de confusión.
- Análisis crítico de los resultados.

### 5. Interpretación y Conclusiones

- Análisis de importancia de las variables con Random Forest.
- Recomendaciones estratégicas basadas en los hallazgos.

---

## 📌 Principales Hallazgos

- Las variables **`tenure`**, **`charges.monthly`** y **`contract_Mes a Mes`** fueron las más influyentes en la cancelación.
- Los clientes con contratos de corto plazo y bajo tiempo de permanencia tienen mayor probabilidad de churn.
- La regresión logística mostró mejor capacidad predictiva en este caso, aunque el Árbol de Decisión aportó mayor interpretabilidad.

---

## ✅ Conclusiones y Recomendaciones

- Ofrecer **contratos de mayor duración** con beneficios puede ayudar a reducir el churn.
- Monitorear clientes con **tenure bajo y alto gasto mensual** puede permitir intervenciones proactivas.
- Incluir modelos de machine learning en procesos de retención puede anticipar cancelaciones y mejorar la fidelización.

---

## 📎 Recursos

- 📘 Mentoría: *TelecomX - Parte 2*
- 📄 Instrucciones oficiales del desafío (PDF)
- 🧠 Curso Alura Latam - Oracle Next Education

---

## 👤 Autor

**Pamela Ormeño**  
Desarrollado como parte del programa de formación Oracle Next Education (ONE) - Alura Latam.  
📎 [LinkedIn](https://www.linkedin.com/in/pamelaormeno/)