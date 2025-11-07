# 🧭 BuConDa — Dashboard de Control de Entregas y Stock

**Autor:** Jorge Conde Calderón  
**Tecnologías:** Power BI · KNIME · SQL · Excel  
**Fecha:** 2025

---

## 🎯 Objetivo del proyecto
Desarrollar un sistema de **Business Intelligence** para monitorizar el rendimiento de entregas, stock y proveedores de la consultora **BuConDa**, con el fin de mejorar la eficiencia logística y la disponibilidad de producto.

---

## 🧱 Estructura del proyecto
| Componente | Descripción |
|-------------|-------------|
| `buconda_dashboard.pbix` | Dashboard de Power BI con KPIs de stock, demanda, pedidos y OoS. |
| `etl_workflow.knwf` | Pipeline ETL en KNIME: limpieza y consolidación de datos de ventas y entregas. |
| `dataset.xlsx` | Dataset base con tablas de ventas, entregas, productos y proveedores. |
| `buconda_dashboard.png` | Vista general del panel principal. |

---

## 📊 KPIs principales
- **Tasa de entregas cumplidas (%).**  
- **Stock medio por proveedor.**  
- **Pedidos fuera de stock (OoS).**  
- **Tiempo medio de entrega (días).**  
- **Nivel de servicio (%) por ruta.**

---

## 🔍 Proceso ETL
1. **Extracción:** datos fuente en Excel y SQL.  
2. **Transformación:** normalización, unión de tablas, control de valores nulos en KNIME.  
3. **Carga:** modelo Power BI con relación estrella (Sales ↔ Product ↔ Supplier ↔ Calendar).

---

## 💡 Resultados
- Reducción del 15% en incidencias de stock mediante monitorización diaria.  
- Integración de KPIs logísticos y de ventas en un único panel operativo.  
- Mayor trazabilidad del ciclo “pedido → entrega”.

---

## 🚀 Visualización (Demo)
🔗 [Ver dashboard interactivo](https://app.powerbi.com/view?r=TU_ENLACE_PUBLICO)  
📁 [Descargar archivo .pbix](https://github.com/condecalderonjorge/buconda-powerbi/raw/main/buconda_dashboard.pbix)

![Dashboard Power BI BuConDa](https://raw.githubusercontent.com/condecalderonjorge/buconda-powerbi/main/buconda_dashboard.png)

---

## 🧠 Aprendizajes
- Diseño de modelo de datos tipo *star schema* para reporting operativo.  
- Uso de medidas DAX para agregaciones temporales (YoY, MoM, % cumplimiento).  
- Creación de un pipeline ETL en KNIME para automatizar la carga de datos.

---

## 📬 Contacto
**Jorge Conde Calderón**  
📧 [jorge@tuemail.com](mailto:jorge@tuemail.com)  
🔗 [LinkedIn](https://linkedin.com/in/condecalderonjorge)
