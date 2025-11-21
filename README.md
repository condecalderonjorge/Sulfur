# 🧭 BuConDa — Dashboard de Control de Precios y Stock

**Autor:** Jorge Conde Calderón  
**Tecnologías:** Power BI · KNIME · SQL · Excel  
**Fecha:** 2025

---

## 🎯 Objetivo del proyecto
Automatizar y desarrollar un sistema de **Business Intelligence** para extraer y monitorizar el rendimiento de precios, entregas, stock y proveedores en la consultora **BuConDa**, con el fin de mejorar la eficiencia logística y el abastecimiento de materias primas.

---

## 🧱 Estructura del proyecto

| Componente | Descripción |
|-----------|-------------|
| [`Reto Buconda.pbix`]([https://app.powerbi.com/viewr=eyJrIjoiZjI4OGE1MjYtZGVmZC00ZjZhLTk0ZjktMDUxMGMxYmQzYzg4IiwidCI6ImNlYTFlYTNlLTYwYjItNGY3NS1hNmMyLWE2MDIyZThmOTYxYiIsImMiOjh9](https://app.powerbi.com/view?r=eyJrIjoiZjI4OGE1MjYtZGVmZC00ZjZhLTk0ZjktMDUxMGMxYmQzYzg4IiwidCI6ImNlYTFlYTNlLTYwYjItNGY3NS1hNmMyLWE2MDIyZThmOTYxYiIsImMiOjh9)) | Dashboard de Power BI con KPIs, precios, pedidos y noticias. |


---

## 📊 KPIs principales
- **% de variación del precio**  
- **% de variación en los pedidos**  
- **Stock medio por proveedor**  
- **Importe de las compras por proveedor**  
- **Evolución de los pedidos por mes**

---

## 🔍 Proceso ETL
1. **Extracción:** datos fuente en Excel y SQL. Extracción de los precios y de noticias relevantes mediante scrapping automatizado. Tipo de cambio CNY - EUR a traves de xml web del BCE.
2. **Transformación:** normalización, unión de tablas, control de valores.  
3. **Carga:** modelo Power BI con relación estrella (Sales ↔ Product ↔ Supplier ↔ Calendar).

---

## 💡 Resultados
- Previsión (forecast) internacional del precio de compra mediante monitorización.  
- Integración de KPIs logísticos y de ventas en un único panel operativo.  
- Integración de fuentes de últimas noticias relevantes en el precio mediante scrapping.


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
