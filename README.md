# E-Commerce API Testing - Postman Suite

Este repositorio contiene un proyecto de automatización de pruebas funcionales para una API REST de comercio electrónico (*FakeStoreAPI*). El objetivo del proyecto es validar los endpoints principales de gestión de productos utilizando scripts de JavaScript en **Postman** y asegurar el correcto comportamiento de la aplicación bajo pruebas.

## Escenarios de Prueba Automatizados

La suite valida dos flujos esenciales dentro de la plataforma de la tienda:

1. **Consulta de Productos (`GET /products/1`):** * Verificación de código de estado `200 OK`.
   * Validación de tiempos de respuesta óptimos (SLA menor a 800ms).
   * Aserción de contenido para asegurar que los datos del producto (ID, Título y Categoría) coincidan con la base de datos.
2. **Creación de Productos (`POST /products`):**
   * Verificación de la recepción correcta de la petición.
   * Validación de la estructura del formato JSON recibido.
   * Aserciones funcionales para comprobar que el objeto devuelto mantenga la integridad de los datos enviados (Título y Precio).

## Tecnologías Utilizadas

* **Herramienta principal:** Postman Desktop Client
* **Lenguaje de Scripts:** JavaScript (Librería Chai Assertion integrada)
* **API de Pruebas:** FakeStoreAPI

## Evidencia
https://1drv.ms/f/c/ee8f44352c0fb417/IgCLpVYrKfwiQ5ml-PHT9n5wAWbRWk9IBocNdS95Y70AotU?e=nY5eUF
