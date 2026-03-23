# 📊 CONFECCIONES LANDI EIRL: Sistema de Gestión de Ventas e Inventarios con Automatización de Stock y Dashboard Analítico

Sistema desarrollado en Google Sheets (aplicación a pedido de la empresa) que integra el registro de ventas e inventarios en un entorno unificado, permitiendo la actualización automática del stock por tienda a partir de los movimientos de entrada y salida. La información se transforma en indicadores analíticos mediante un dashboard en Looker Studio, facilitando el análisis de ventas, productos y desempeño comercial a través de visualizaciones interactivas.

---

## 🔍 Diagnóstico Inicial e Identificación de Problemas 

- Se identificaron ineficiencias e inconsistencias en los procesos de registro de ventas e inventarios, derivadas de una gestión manual y descentralizada de la información.  
- El registro de ventas se realizaba diariamente en múltiples hojas de Excel (una por día), generando fragmentación de la información, dificultad en la consolidación mensual y limitaciones para su análisis y visualización en herramientas de Business Intelligence.  
- Asimismo, el control de inventarios se gestionaba de forma manual por tienda, donde los movimientos de productos (ingresos y salidas) se registraban sin un sistema estructurado, lo que generaba descuadres en el stock y discrepancias entre la empresa y los puntos de venta, especialmente bajo el modelo de consignación.  
- Adicionalmente, se detectaron errores en la calidad del registro de ventas, como la falta de estandarización en atributos clave (producto, talla, modelo), lo que impedía realizar análisis consistentes y limitaba la generación de indicadores confiables para la toma de decisiones.  

### 📂 Registros Originales (Antes de la Implementación)

- 📄 **Registro de Ventas (Formato Antiguo):**  
  👉 [Acceder al archivo](https://docs.google.com/spreadsheets/d/1ngxgVivlIdNIfo9T7LFWG81cmaV3o18z/edit?usp=sharing&ouid=116177110913487110063&rtpof=true&sd=true)

- 📦 **Registro de Inventarios (Formato Antiguo):**  
  👉 [Acceder al archivo](https://docs.google.com/spreadsheets/d/1k2AlfIUCnjjTB9oE5uMfImJt7K2P3ZiU/edit?usp=sharing&ouid=116177110913487110063&rtpof=true&sd=true)

---

## 💡 Solución Implementada

### 🟩 Google Sheets
Se diseñó e implementó un **sistema centralizado de gestión de ventas e inventarios en Google Sheets**, orientado a mejorar la trazabilidad, calidad, transparencia y control de la información operativa.

- **Estandarización mediante codificación de productos:**  
  Creación de códigos generales (producto) y códigos específicos (producto + talla o modelo) para asegurar una identificación precisa y reducir errores en el registro.

- **Registro de ventas estructurado:**  
  Implementación de una interfaz simple para registrar el detalle de cada venta, utilizando Google Apps Script para automatizar el registro mediante macros, permitiendo almacenar cada transacción de forma automática en una base de datos consolidada.

- **Base de datos centralizada de ventas:**  
  Consolidación de todas las ventas en una única hoja, habilitando su análisis y conexión directa con herramientas de BI, en este caso Looker Studio.

- **Sistema de inventarios por tienda:**  
  Desarrollo de un registro que permite gestionar ingresos y salidas de productos por tienda, utilizando Google Apps Script para automatizar el almacenamiento de los movimientos y generar una base de datos estructurada de inventarios.

- **Automatización del stock:**  
  Integración de ventas, ingresos y salidas para actualizar automáticamente el stock por tienda, donde cada movimiento impacta directamente en el inventario.

- **Trazabilidad de la información:**  
  Registro completo de cada movimiento, asegurando consistencia, transparencia y validación del stock.

### 📈 Looker Studio
- **Integración con dashboard:**  
  Conexión de la base de datos con un dashboard en Looker Studio, permitiendo la actualización automática de indicadores y eliminando procesos manuales de análisis.  

- **Seguimiento del desempeño de ventas:**  
  Evaluación del comportamiento comercial mediante visualizaciones que permiten identificar tendencias y patrones de venta.  

- **Optimización del tiempo de análisis:**  
  Reducción del tiempo requerido para generar reportes, pasando de procesos manuales a visualización automatizada en tiempo real.  

### 📂 Registros de Ventas, Inventarios y Dashboard
Por políticas de confidencialidad, se incluyen versiones estáticas de los archivos desarrollados, sin conexión a datos en tiempo real. El dashboard se presenta únicamente en formato visual, ya que contiene información sensible y proyecciones comerciales de la empresa.

- 📄 **Registro de Ventas e Inventarios:**  
  👉 [Acceder al archivo](https://docs.google.com/spreadsheets/d/16aBkA_BGrYLpfIogN06zFZ2Dcnq3KoUXRjQLUCKx95o/edit?usp=sharing)

- 📊 **Dashboard en Looker Studio:**  
<p align="center">
  <img src="Dashboard_Looker Studio.png" width="80%">
</p>

---

## 🚀 Impacto del Proyecto

- **Centralización y unificación de datos:** consolidación de ventas e inventarios en una única fuente confiable de información.  
- **Reducción de errores operativos:** disminución de inconsistencias mediante la automatización y estandarización del registro.  
- **Mejora en la calidad de datos (data quality):** implementación de estructuras y validaciones que garantizan información consistente y analizable.  
- **Control eficiente del stock por tienda:** visibilidad y trazabilidad completa de los movimientos de inventario en el modelo de consignación.  
- **Habilitación de analítica de negocio (BI):** transformación de datos operativos en indicadores clave mediante un dashboard interactivo para la toma de decisiones.  

---

## 🛠️ Herramientas Utilizadas

- **Google Sheets:**  
  Gestión y estructuración de la base de datos de ventas e inventarios.

- **Google Apps Script:**  
  Automatización de procesos mediante macros para el registro de ventas e inventarios.

- **Looker Studio:**  
  Desarrollo de dashboards interactivos para la visualización y análisis de datos.

---

## 👨‍💻 Encargados del Proyecto

- Luis Fernando Chávez Boza  
- Johan Antoni Cesar Escobar Riveros  
