- [Gateway]: API Gateway para conectar con las APIs
- [Products Management API](https://github.com/mmrasteu/ims-products-management-api): Gestión de productos
- [Inventory Control API](https://github.com/mmrasteu/ims-inventory-control-api): Control de existencias en el inventario
- [Orders Management API]: Gestión de pedidos
- [Reports and Analytics API]: Generación de infomres y analíticas

# Objetivo del Proyecto

El objetivo principal de IMS es de carácter educativo, tanto para mi aprendizaje como para que sirva de referencia de aprendizaje para quien lo necesite, y de esta forma tener un proyecto con características realistas (entiéndase que pueda tener un uso para una empresa real) donde aplicar diferentes conocimientos tanto de arquitectura como de lenguajes, frameworks, etc. En la descripción de las características principales se indicará el stack tecnológico utilizado.

# IMS - Sistema de Gestión de Inventarios

IMS es un sistema de gestión de inventarios diseñado para ayudar a las empresas a administrar eficientemente sus existencias y procesos relacionados. El sistema proporciona una plataforma robusta y escalable para el seguimiento preciso de productos, control de existencias, gestión de pedidos y generación de informes analíticos.

### Características Principales:
- **Gateway**: API Gateway para conectar con las APIs. Se encarga de dirigir las solicitudes de los clientes a las distintas APIs del sistema y de gestionar la autenticación, autorización, monitoreo y limitación de tráfico. (Pendiente...)

- **Gestión de Productos**: Permite a los usuarios crear, editar, eliminar y buscar productos en el inventario, incluyendo detalles como nombre, descripción, categoría, precio, etc. (Laravel/MySQL - En desarrollo)

- **Control de Existencias**: Realiza un seguimiento en tiempo real de las existencias disponibles de cada producto, registrando las entradas y salidas de inventario y actualizando automáticamente los niveles de existencias. (NodeJS/Express/MongoDB - En desarrollo)

- **Gestión de Pedidos**: Facilita la creación, edición y seguimiento de pedidos de productos, integrando la disponibilidad de productos con el control de existencias para validar los pedidos. (Pendiente...)

- **Generación de Informes y Analíticas**: Proporciona herramientas para generar informes detallados sobre el estado del inventario, tendencias de ventas, análisis de datos, etc., para ayudar en la toma de decisiones empresariales. (Pendiente...)


### Estructura del Proyecto:

- **Repositorios de APIs**: Este repositorio actúa como un repositorio central que contiene enlaces a los diferentes repositorios de las APIs utilizadas en el proyecto IMS, como la API de gestión de productos, control de existencias, gestión de pedidos, etc. Cada API se desarrolla y mantiene de forma independiente para una mayor modularidad y escalabilidad.
