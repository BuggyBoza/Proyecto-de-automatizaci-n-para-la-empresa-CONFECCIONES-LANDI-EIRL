# 📊 Sistema de Gestión de Ventas e Inventarios con Automatización de Stock y Dashboard Analítico

Sistema desarrollado en Google Sheets (aplicacióna a pedido de la empresa) que integra el registro de ventas e inventarios en un entorno unificado, permitiendo la actualización automática del stock por tienda a partir de los movimientos de entrada y salida. La información es transformada en indicadores analíticos mediante un dashboard en Looker Studio, facilitando el análisis de ventas, productos y desempeño comercial a través de visualizaciones interactivas.

---

## 🔍 Diagnóstico Inicial e identificación de problemas 

- Se identificaron ineficiencias e inconsistencias en los procesos de registro de ventas e inventarios, derivados de una gestión manual y descentralizada de la información.
- El registro de ventas se realizaba diariamente en múltiples hojas de Excel (una por día), generando fragmentación de la información, dificultad en la consolidación mensual y limitaciones para su análisis y visualización en herramientas Business Information.
- Asimismo, el control de inventarios se gestionaba de forma manual por tienda, donde los movimientos de productos (ingresos y salidas) se registraban sin un sistema estructurado, lo que generaba descuadres en el stock y discrepancias entre la empresa y los puntos de venta, especialmente bajo el modelo de consignación.
- Adicionalmente, se detectaron errores en la calidad del registro de ventas, como la falta de estandarización en atributos clave (producto, talla, modelo), lo que impedía realizar análisis consistentes y limitaba la generación de indicadores confiables para la toma de decisiones.

### 📂 Registros Originales (Antes de la Implementación)

- 📄 **Registro de Ventas (Formato Antiguo):**  
  👉 [Acceder al archivo](https://docs.google.com/spreadsheets/d/1ngxgVivlIdNIfo9T7LFWG81cmaV3o18z/edit?usp=sharing&ouid=116177110913487110063&rtpof=true&sd=true)

- 📦 **Registro de Inventarios (Formato Antiguo):**  
  👉 [Acceder al archivo](https://docs.google.com/spreadsheets/d/1k2AlfIUCnjjTB9oE5uMfImJt7K2P3ZiU/edit?usp=sharing&ouid=116177110913487110063&rtpof=true&sd=true)

---

## 💡 Solución Implementada

Se diseñó e implementó un **sistema centralizado de gestión de ventas e inventarios en Google Sheets**, orientado a mejorar la trazabilidad, calidad y control de la información operativa.

- **Estandarización mediante codificación de productos:**  
  Creación de códigos generales (producto) y códigos específicos (producto + talla) para asegurar una identificación precisa y reducir errores en el registro.

- **Registro de ventas estructurado:**  
  Implementación de una interfaz simple para registrar transacciones, capturando el detalle de cada venta y almacenándola automáticamente en una base de datos consolidada.

- **Base de datos centralizada de ventas:**  
  Consolidación de todas las ventas en una única hoja, habilitando su análisis y conexión directa con herramientas de BI.

- **Sistema de inventarios por tienda:**  
  Desarrollo de un registro que permite gestionar ingresos y salidas de productos por tienda, generando una base de datos estructurada de inventarios.

- **Automatización del stock:**  
  Integración de ventas, ingresos y salidas para actualizar automáticamente el stock por tienda, donde cada movimiento impacta directamente en el inventario.

- **Trazabilidad de la información:**  
  Registro completo de cada movimiento, asegurando consistencia, transparencia y validación del stock.

- **Integración con dashboard:**  
  Conexión de la base de datos con un dashboard en Looker Studio, permitiendo la actualización automática de indicadores y eliminando procesos manuales de análisis.


---

## 👨‍💻 Autor

Fernando Chávez
