# 🧭 BuConDa — Dashboard de Control de Precios y Stock

**Autor:** Jorge Conde Calderón  
**Tecnologías:** Power BI · KNIME · SQL · Excel  
**Fecha:** 2025

---

## 🎯 Objetivo del proyecto
Desarrollar un sistema de **Business Intelligence** para extraer monitorizar el rendimiento de precios, entregas, stock y proveedores en la consultora **BuConDa**, con el fin de mejorar la eficiencia logística y la disponibilidad del azufre a un cliente.

---

## 🧱 Estructura del proyecto
| Componente | Descripción |
|-------------|-------------|
| `Reto Buconda.pbix` | Dashboard de Power BI con KPIs, precios, pedidos, noticias y OoS. |
| `dashboard 1.png` | Vista general del panel de análisis de precios. |
| `dashboard 2.png` | Vista general del panel de análisis de pedidos. |
| `dashboard 1.png` | Vista general del panel de noticias. |

---

## 📊 KPIs principales
- **% de variación del precio**  
- **% de variación en los pedidos**  
- **Stock medio por proveedor**  
- **Importe de las compras por proveedor**  
- **Evolución de los pedidos por mes**

---

## 🔍 Proceso ETL
1. **Extracción:** datos fuente en Excel y SQL. Extracción de los precios de mercado mediante scrapping. 
2. **Transformación:** normalización, unión de tablas, control de valores.  
3. **Carga:** modelo Power BI con relación estrella (Sales ↔ Product ↔ Supplier ↔ Calendar).

---

## 💡 Resultados
- Previsión (forecast) internacional del precio de compra mediante monitorización.  
- Integración de KPIs logísticos y de ventas en un único panel operativo.  
- Integración de funtes de últimas noticias relevantes en el precio mediante scrapping.


---

## 🧠 Aprendizajes
- Diseño de modelo de datos para reporting operativo.  
- Uso de medidas DAX para agregaciones temporales (YoY, MoM, % cumplimiento).  
- Creación de un pipeline ETL en KNIME para automatizar la carga de datos.

---

## 📬 Contacto
**Jorge Conde Calderón**  
📧 [condecalderonjorge@gmail.com](mailto:condecalderonjorge@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/jorge-conde-calderon/)
