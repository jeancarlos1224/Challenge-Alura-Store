# Análisis de Tiendas — Alura Store

### *Proyecto de Evaluación de Rendimiento de 4 Tiendas*

Este repositorio contiene el análisis completo de rendimiento de cuatro tiendas pertenecientes a la cadena **Alura Store**, con el objetivo de determinar cuál de ellas debería ser vendida por el Sr. Juan para financiar un nuevo emprendimiento.

El proyecto incluye:
✔ Exploración de datos
✔ Visualización con Matplotlib
✔ Cálculo de métricas clave
✔ Comparación entre tiendas
✔ Una recomendación final basada en datos

---

## **Tecnologías utilizadas**

* **Python 3**
* **Pandas**
* **Matplotlib**
* **Google Colab / Jupyter Notebook**

---

## **Archivos del proyecto**

```
📦 proyecto-alura-store
 ┣ 📄 AluraStoreLatam.ipynb   ← Notebook con todo el análisis
 ┗ 📄 README.md                ← Este archivo
```

---

## **Carga y Exploración de Datos**

Se cargaron los cuatro archivos CSV correspondientes a las tiendas.
En la etapa de exploración se revisaron:

* Estructura de columnas
* Tipos de datos
* Valores nulos
* Primeras filas del dataset
* Distribuciones iniciales

Se identificaron las siguientes categorías clave:
✔ Producto
✔ Categoría
✔ Precio
✔ Costo de envío
✔ Fecha de compra
✔ Tipo de pago
✔ Calificación del cliente
✔ Coordenadas geográficas

---

## **Métricas Analizadas**

### **1. Ingreso Total por Tienda**

Se calculó sumando el valor de la columna **Precio**.

### **2. Ventas por Categoría**

Agrupamiento por la columna **categoría_producto**.

### **3. Calificación Promedio**

Promedio de la columna **calificación_compra**.

### **4. Productos Más y Menos Vendidos**

Se ordenaron los productos según su frecuencia de venta.

### **5. Costo de Envío Promedio**

Promedio de la columna **costo_envío**.

---

## 📊 **Visualizaciones Generadas**

Se construyeron al menos 3 gráficos usando Matplotlib:

* **Barras**: Ingreso total de cada tienda
* **Barras múltiples**: productos por categoria más vendidos
* **Barras**: calificación promedio por tienda
  
<img width="460" height="384" alt="Ingreso total" src="https://github.com/user-attachments/assets/3438a4a7-5991-4539-91ad-45d7d2d15fa7" />

<img width="717" height="446" alt="Captura desde 2025-11-25 12-52-33" src="https://github.com/user-attachments/assets/adfaf85d-d87f-4592-9de2-efeb19597688" />

<img width="545" height="387" alt="calificacion promedio" src="https://github.com/user-attachments/assets/ca1f61d3-19b8-4c57-bfab-b190130f591c" />


Estas visualizaciones permitieron comparar tiendas y detectar patrones clave.

---

## 🧮 **Resumen General de Tiendas**

| Tienda | Ingreso Total | Nº Ventas | Ingreso por Venta | Calificación Promedio | Envío Promedio |
| ------ | ------------: | --------: | ----------------: | --------------------: | -------------: |
| **1**  | 1,150,880,400 |      2359 |        487,867.91 |                  3.98 |      26,018.61 |
| **2**  | 1,116,343,500 |      2359 |        473,227.43 |                  4.04 |      25,216.24 |
| **3**  | 1,098,020,000 |      2359 |        465,459.77 |                  4.05 |      24,805.68 |
| **4**  | 1,038,375,700 |      2358 |        440,362.89 |                  4.00 |      23,459.46 |

---

## 🏁 **Conclusión y Recomendación Final**

### **Recomendación: El Sr. Juan debería vender la *Tienda 4*.**

**Justificación basada en datos:**

* Es la **tienda con menor ingreso total**.
* Tiene el **menor ingreso promedio por venta**.
* Aunque su envío es el más bajo, **no compensa la baja rentabilidad**.
* No destaca en calificaciones ni en productos de alto rendimiento.

Vender la Tienda 4 representa **el menor impacto negativo en las operaciones generales**, permitiendo optimizar el portafolio de tiendas del Sr. Juan.

---


¿Quieres alguna mejora extra?
