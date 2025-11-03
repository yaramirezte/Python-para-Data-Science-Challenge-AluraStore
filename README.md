# 📊 Análisis Comparativo de Rendimiento: Alura Store Latam

Este proyecto de analisis de datos se basa en el analisis de información sobre las ventas, categorías de productos, precios y costos de envío en las tiendas de **Alura Store Latam** para ayudar a **identificar la tienda menos eficiente** y emitir una **recomendación final** sobre qué sucursal debe vender el Sr. Juan, propietario de la cadena, quien busca iniciar un nuevo emprendimiento y requiere vender una de sus cuatro tiendas. 

---
## 💻 Datos y Requisitos de Análisis

El análisis se centra en la evaluación comparativa de las 4 tiendas de Alura Store, examinando los siguientes aspectos:

* **Métricas Financieras:** Ingresos totales por tienda.
* **Comportamiento de Ventas:** Categorías y productos más vendidos en cada sucursal.
* **Experiencia del Cliente:** Evaluación de las reseñas de clientes y puntuación de satisfacción.
* **Eficiencia Logística:** Análisis del costo de envío promedio.
* **Rendimiento General:** Evaluación de la eficiencia de ventas por tienda.

### Requisitos Cumplidos:

1.  **Manipulación de Datos:** Carga y limpieza de datos CSV utilizando la biblioteca Pandas.
2.  **Visualización de Datos:** Creación de gráficos diferentes utilizando Matplotlib y/o Seaborn para una presentación visual clara de los resultados.
3.  **Recomendación Final:** Un texto conclusivo que explica la decisión de venta basada rigurosamente en la evidencia de los datos.

---

## 🛠️ Tecnologías y Dependencias

Para ejecutar este análisis, se requiere el siguiente entorno:

| Herramienta / Librería | Descripción |
| :--- | :--- |
| **Python** | Lenguaje de programación principal. |
| **Pandas** | Manipulación, agregación y análisis de estructuras de datos. |
| **NumPy** | Soporte para operaciones numéricas y matemáticas eficientes. |
| **Matplotlib / Seaborn / plotly / folium / Nominatim** | Creación de visualizaciones estáticas e interactivas para los gráficos de comparación. |
| **Jupyter Notebook / Google Colab** | Entorno de desarrollo interactivo. |

---

## 📂 Estructura del respositorio

```
Python-para-Data-Science-Challenge-AluraStore/
│
├── datasets/ # CSV conjuntos de datos usados para el projecto
│
├── docs/ # documentacion del projecto, graficos, mapas and notas
│  
├── AluraStoreLatam.ipynb/ # Archivo principal que contiene carga de datos, análisis y visualizaciones
│
└── README.md # Instrucciones del proyecto

```
---

## 💡 Resultados y Conclusiones
Del análisis realizado se observa que **Tienda1** destaca por sus altos ingresos, pero presenta debilidades en la satisfacción del cliente y en sus elevados costes de envío. **Tienda2** muestra un equilibrio ideal entre ingresos, satisfacción del cliente y costes competitivos, posicionándose como la tienda más eficiente. **Tienda3** ofrece la mejor valoración por parte de los clientes, aunque sus ingresos son ligeramente menores. En contraste, **Tienda4** tiene el coste de envío más bajo, pero también los ingresos y calificaciones más bajas del grupo.

Conclusión Principal:
se determina que la **Tienda4**es la menos eficiente dentro de la cadena AluraStore, ya que su bajo desempeño en ventas y satisfacción del cliente no compensa su menor coste de envío. Por ello, se recomienda que el **Sr. Juan** venda la **Tienda4** para enfocar sus recursos en las tiendas con mejor rendimiento, especialmente Tienda2 y Tienda3, optimizando así la rentabilidad y el crecimiento de su nuevo emprendimiento.
