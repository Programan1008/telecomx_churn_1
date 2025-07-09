# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del mi desafío final del módulo de análisis de datos. El objetivo es identificar patrones relacionados con la evasión de clientes en una empresa de telecomunicaciones, aplicando un proceso ETL y análisis exploratorio de datos (EDA) en Python.

---

## 🎯 Objetivo

Comprender los factores que influyen en la cancelación de servicios por parte de los clientes y entregar insights estratégicos para reducir el churn.

---

## 🧱 Estructura del Proyecto

- `TelecomX_Analisis_Churn1.ipynb`: Cuaderno principal con todo el desarrollo del análisis.
- `README.md`: Este archivo con la descripción general del proyecto.

---

## ⚙️ Tecnologías Utilizadas

- Python (Pandas, Seaborn, Matplotlib)
- Google Colab
- Git & GitHub

---

## 🔄 Proceso Realizado (ETL + Análisis)

1. **Extracción de datos** desde una API JSON.
2. **Transformación**:
   - Expansión de columnas anidadas.
   - Limpieza de nulos y duplicados.
   - Creación de columna `Cuentas_Diarias`.
   - Estandarización y traducción de variables categóricas.
3. **Carga**: Los datos se preparan en un `DataFrame` listo para análisis.
4. **EDA (Exploración)**:
   - Análisis de distribución del churn.
   - Comparación por género, contrato, servicios.
   - Matriz de correlación y visualizaciones.
5. **Informe final**: Conclusiones, insights y recomendaciones estratégicas.

---

## 📈 Ejemplos de Insights

- Los contratos mensuales tienen una tasa de evasión significativamente mayor.
- Los clientes con menor tiempo de permanencia son más propensos a cancelar.
- Los métodos de pago automáticos están relacionados con menor churn.

---

## 🚀 Cómo Ejecutar el Notebook

1. Sube el archivo `.ipynb` a Google Colab.
2. Asegúrate de tener conexión a internet para cargar datos desde la API.
3. Ejecuta cada celda en orden para reproducir el análisis completo.

---

## 📌 Autor

Desarrollado por Cristopher Jimenez como parte del curso de análisis de datos de Alura LATAM.

---
