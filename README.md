# Proyecto BI — Ventas de Retail (Superstore Sales)

**Institución Universitaria ITM · Análisis de Datos · 2026-1**
**Docente:** Daniel Alexis Nieto Mora
**Equipo:** Equipo 1 — Ventas de Retail

---

## Objetivo

Desarrollar un proyecto integral de Business Intelligence sobre el dataset **Superstore Sales** para transformar datos de ventas al por menor en información accionable, mediante análisis estadístico, formulación y validación de hipótesis, definición de KPIs y construcción de dashboards.

---

## Dataset

| Campo | Detalle |
|-------|---------|
| Archivo | `train.csv` |
| Registros | 9 800 líneas de pedido |
| Período | 2015 – 2018 |
| Variables | 18 (Order ID, fechas, cliente, segmento, región, categoría, producto, ventas) |
| Fuente | Superstore Sales — dataset clásico de retail para análisis BI |

**Columnas principales:**
`Row ID · Order ID · Order Date · Ship Date · Ship Mode · Customer ID · Customer Name · Segment · Country · City · State · Postal Code · Region · Product ID · Category · Sub-Category · Product Name · Sales`

---

## Metodología

El proyecto se organiza en **6 fases** según la guía del docente.

### Fase 1 — Comprensión del Problema ✅

- Descripción del contexto del dataset de ventas retail.
- Identificación del problema: ¿qué factores impulsan o frenan las ventas?
- **5 preguntas clave** formuladas (segmento, región, envío, subcategoría, tiempo).
- Decisión metodológica: transformación **log(Sales+1)** para visualización, dado que `Sales` presenta skewness = 12.98 (extremadamente sesgado).

| Estadístico | Valor |
|-------------|-------|
| Media | $230.77 |
| Mediana | $54.49 |
| Ratio media/mediana | 4.2× |
| Skewness | 12.98 |
| Máximo | $22,638.48 |

### Fase 2 — Formulación de Hipótesis *(pendiente)*

### Fase 3 — Preparación y Modelado de Datos *(pendiente)*

### Fase 4 — Definición de KPIs *(pendiente)*

### Fase 5 — Dashboard *(pendiente)*

### Fase 6 — Análisis, Validación y Storytelling *(pendiente)*

---

## Estructura del repositorio

```
entrega-3/
├── train.csv              # Dataset Superstore Sales
├── analysis.ipynb         # Notebook Jupyter — Fase 1
└── README.md
```

---

## Cómo ejecutar

```bash
# Instalar dependencias
pip install pandas numpy matplotlib seaborn scipy

# Abrir el notebook
jupyter notebook analysis.ipynb
```

---

## Dependencias

| Librería | Uso |
|----------|-----|
| `pandas` | Manipulación y agregación de datos |
| `numpy` | Operaciones numéricas y transformación log |
| `matplotlib` | Visualizaciones |
| `seaborn` | Estilos y gráficas estadísticas |
