# 📊 Catálogo de Inventario Multi-Bodega (Integración ERP)

*(Coloca aquí un GIF o captura de la vista principal del catálogo, idealmente mostrando el "Modo Cliente").*

**Ecosistema web en tiempo real conectado a Microsoft Dynamics 365 Business Central para la visualización dinámica de stock de SKUs de alto valor.**

### 🎯 El Desafío Operativo
El equipo de ventas y operaciones carecía de visibilidad instantánea del stock cruzado entre bodegas (PAV y PCO). Las consultas de disponibilidad dependían de llamadas telefónicas al área de logística o extracciones manuales del ERP, lo que generaba fricción comercial y errores de venta por productos agotados.

### 🚀 La Solución y Resultados
Desarrollé una plataforma in-house a costo cero en licencias, que extrae, cruza y publica la data del ERP en una interfaz de alto rendimiento.
* **Visibilidad 24/7:** Cruce matemático automático entre el stock total contable y el físico en las bodegas.
* **Modo Cliente (UI/UX):** Interfaz adaptable que oculta códigos internos y cantidades exactas de stock (con alertas de "Últimas Unidades"), permitiendo a los asesores mostrar la pantalla directamente a las familias.
* **Gestión de Activos Visuales:** Repositorio integrado de fotografías de productos (con remoción de fondo) servidas directamente desde GitHub.
* **Reducción de Carga Operativa:** Eliminación del 100% de las consultas telefónicas de stock hacia el equipo de bodega.

### 🛠️ Arquitectura y Stack Tecnológico
* **Frontend:** HTML5, CSS3 (Diseño Glassmorphism, Paletas de Alto Contraste), Vanilla JavaScript.
* **Backend / Pipeline de Datos:** Google Apps Script, Google Sheets como base de datos intermedia.
* **Automatización & ERP:** Microsoft Power Automate para la extracción automatizada de datos desde Microsoft Dynamics 365 Business Central.

### 📸 Vistas del Sistema
*(Agrega 2 capturas pequeñas: una de la vista técnica de inventario con códigos, y otra demostrando el cruce de stock PAV/PCO).*
