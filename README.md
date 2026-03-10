# 🏪 AluraStore Latam — Challenge 1: Análisis de Tiendas

## 📌 Descripción

Este proyecto forma parte del **Challenge 1 de Data Science** de Alura Latam. El objetivo es ayudar al Sr. Juan a decidir cuál de las 4 tiendas de su cadena **Alura Store** debe vender para financiar un nuevo emprendimiento.

Para ello se analizan datos reales de ventas, calificaciones de clientes, categorías de productos y costos de envío, con el fin de identificar la tienda con menor rendimiento.

---

## 🎯 Objetivos

- Cargar y manipular datos CSV con **Pandas**
- Crear visualizaciones con **Matplotlib**
- Analizar métricas clave: ingresos, categorías, calificaciones, productos y envíos
- Presentar una recomendación final basada en los datos

---

## 📁 Estructura del Proyecto

```
alura-store-latam/
│
├── AluraStoreLatam_Completo.ipynb   # Notebook principal con todo el análisis
├── README.md                        # Este archivo
└── datos/
    ├── tienda_1_.csv
    ├── tienda_2.csv
    ├── tienda_3.csv
    └── tienda_4.csv
```

---

## 📊 Análisis Realizados

| # | Análisis | Descripción |
|---|---|---|
| 1 | 💰 Facturación | Ingreso total por tienda (suma de precios) |
| 2 | 🛍️ Ventas por categoría | Productos agrupados por tipo en cada tienda |
| 3 | ⭐ Calificación promedio | Satisfacción del cliente por tienda |
| 4 | 📦 Productos más/menos vendidos | Ranking de productos en cada tienda |
| 5 | 🚚 Costo de envío promedio | Gasto promedio de envío por tienda |
| 6 | 🌎 Análisis geográfico (extra) | Distribución de ventas por coordenadas y ciudad |

---

## 📈 Visualizaciones

El notebook incluye **6 gráficos** de diferentes tipos:

1. **Barras verticales** — Ingresos totales por tienda
2. **Barras horizontales** — Calificación promedio de clientes
3. **Gráficos de torta** — Distribución de categorías por tienda
4. **Gráfico de línea** — Costo de envío promedio
5. **Barras horizontales** — Top 5 productos más vendidos por tienda
6. **Radar/Spider chart** — Comparativo general normalizado de métricas

---

## 🚀 Cómo ejecutar el proyecto

### Opción 1 — Google Colab (recomendado)
1. Abre [Google Colab](https://colab.research.google.com)
2. Ve a **Archivo → Subir notebook**
3. Selecciona `AluraStoreLatam_Completo.ipynb`
4. Ejecuta todas las celdas con `Runtime → Run all`

> Los datos se cargan automáticamente desde GitHub, no es necesario subir los CSV.

### Opción 2 — Local
```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/alura-store-latam.git
cd alura-store-latam

# Instalar dependencias
pip install pandas matplotlib numpy

# Abrir el notebook
jupyter notebook AluraStoreLatam_Completo.ipynb
```

---

## 🧰 Tecnologías utilizadas

- **Python 3**
- **Pandas** — manipulación y análisis de datos
- **Matplotlib** — visualización de datos
- **NumPy** — operaciones numéricas
- **Google Colab** — entorno de ejecución

---

## ✅ Conclusión

Tras analizar las 4 tiendas en todas las métricas disponibles, la recomendación es:

> **🏷️ El Sr. Juan debería vender la Tienda 4.**

**Razones principales:**
- 📉 Genera los **menores ingresos totales** de las cuatro tiendas
- 📦 Tiene el **menor volumen de ventas**
- 🌍 Su **cobertura geográfica** es más limitada
- A pesar de tener el costo de envío más bajo, no logra convertirlo en una ventaja competitiva real

Vender la Tienda 4 le permitirá al Sr. Juan obtener capital para su nuevo emprendimiento conservando las tiendas más rentables.


