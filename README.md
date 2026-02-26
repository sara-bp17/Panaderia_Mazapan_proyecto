# 🥐 Panadería Mazapán

Sistema Web de Gestión e Inventarios (Proyecto Académico)

📌 Descripción general Panadería Mazapán es una aplicación web local diseñada para automatizar la operación de un negocio minorista, integrando ventas, inventario, compras, devoluciones, reportes y emisión de tickets. El sistema fue desarrollado como proyecto final de la materia Aplicaciones Web, siguiendo un enfoque orientado a reglas de negocio, trazabilidad y consistencia de datos, simulando un entorno real de operación.

## 🎯 Objetivo del sistema

Desarrollar un sistema que permita:

* Controlar inventario en tiempo real
* Registrar y auditar compras, ventas y devoluciones
* Diferenciar accesos y responsabilidades por rol
* Generar reportes imprimibles y exportables (CSV)
* Integrar hardware operativo (lector de códigos e impresora de tickets)

## 👥 Roles del sistema

* 👨‍💼 Administrador

  * Gestión de productos y catálogo (con imagen en BD)
    * Administración de usuarios y roles
    * Registro de compras a proveedores
    * Control de inventario y existencias
    * Gestión de devoluciones.
    * Generación de reportes y exportación CSV

* 👤 Operador (Trabajador)

  * Registro de ventas mediante lector de códigos o buscador
  * Generación automática de tickets
  * Registro de devoluciones
  * Consultas de productos e inventario
  * Cada rol accede a una interfaz específica según sus permisos.

## ⚙️ Funcionalidades clave

* Autenticación y manejo de sesiones con control de acceso por rol
* Catálogo de productos con imágenes almacenadas en base de datos
* Inventario con reglas claras:
  * Compra suma stock
  * Venta resta stock
  * Devolución restituye stock sin excedentes
* Operaciones críticas manejadas con transacciones para evitar inconsistencia
* Ventas con generación automática de ticket 80×40
* Reportes imprimibles (A4/Letter) y exportación CSV
* Búsqueda y paginación eficiente de registros
* Integración con lector de códigos de barras e impresora de tickets

## 🛠️ Tecnologías utilizadas

* PHP
* MySQL
* XAMPP
* HTML / CSS
* Jira (gestión de historias de usuario y tareas)

## 🧠 Mi rol en el proyecto

Analista de Requerimientos & Líder de Producto (Académico) 
Mi participación se enfocó en la definición, organización y validación del sistema completo, actuando como enlace entre los requerimientos académicos y la implementación técnica.

Responsabilidades principales:

* Análisis y descomposición de requerimientos funcionales
* Definición de reglas de negocio (inventario, ventas, devoluciones)
* Creación de historias de usuario y criterios de aceptación en Jira
* Asignación y priorización de tareas según el área de cada integrante
* Verificación de la consistencia entre:
  * interfaz
  * lógica de negocio
  * base de datos
  * reportes (vista vs CSV)
* Integración de la documentación final del producto, incluyendo:
  * arquitectura
  * flujos de datos
  * guía de instalación
  * plan de pruebas
  * trazabilidad requerimiento ↔ evidencia

El objetivo fue asegurar que el sistema pudiera ser instalado, ejecutado y validado por un tercero, simulando un proceso real de entrega de producto.

## 👥 Equipo de desarrollo

1. Sara Bañuelos – Líder de proyecto
2. Estrella Gutiérrez – UX/UI y Front-End
3. Valeria Macías – Base de Datos
4. David Rosas – Back-End (CRUD, lógica y transacciones)
5. Javier Muñoz – Autenticación y sesiones
6. Helen Zatarain – Impresión de tickets, lector de códigos, reportes y CSV

## 🚀 Instalación y uso

1. Clonar o descargar el repositorio
2. Instalar XAMPP
3. Colocar el proyecto en la carpeta htdocs
4. Importar la base de datos en MySQL
5. Ejecutar el sistema desde localhost

## 📎 Nota

Este proyecto fue desarrollado exclusivamente con fines académicos, replicando escenarios y reglas de negocio reales.
