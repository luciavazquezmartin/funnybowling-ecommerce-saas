# FunnyBowling - Plataforma SaaS y E-Commerce para centros de ocio

Este repositorio contiene la memoria técnica y de negocio del proyecto **FunnyBowling**, una plataforma integral diseñada para la digitalización de boleras y centros arcade bajo un modelo de software como servicio (SaaS).

## Contenido del repositorio
* `FunnyBowling.pdf`: Documento completo con el modelo de negocio, investigación de usuarios, mapas de empatía y arquitectura de la plataforma.

---

## Enfoque tecnológico y arquitectura de negocio

El proyecto no solo aborda la viabilidad comercial, sino que define la arquitectura lógica y el modelado de un sistema transaccional complejo:

### 1. Arquitectura Multi-Rol (RBAC)
El sistema está diseñado para soportar tres niveles de acceso diferenciados para un entorno B2B2C:
* **Perfil jugador (B2C):** Interfaz para el consumidor final, incluyendo wallet digital (conversión de dinero a puntos arcade) y catálogo de e-commerce.
* **Perfil empleado (B2B):** Panel de gestión operativa del local físico (mapa interactivo de pistas, validación de reservas y gestión de stock temporal como tallas de zapatos).
* **Perfil superadministrador:** Panel de control de alto nivel para el mantenimiento de la plataforma SaaS y monitorización de las empresas cliente.

### 2. Analítica de datos y tracking web
* Integración y configuración de **Google Analytics** para el rastreo del comportamiento de los usuarios.
* Definición de métricas clave de rendimiento y eventos de conversión en tiempo real para optimizar el embudo de ventas y la toma de decisiones basada en datos (data-driven).

### 3. Ingeniería de producto y E-Commerce
* Diseño del modelo de negocio (Canvas) adaptado a un entorno digital.
* Flujos transaccionales para reservas de pistas en tiempo real y canjeo de puntos.

---

## 💻 Entorno de pruebas (Demo)
El proyecto incluye un entorno funcional desplegado (`funnybowling.com`). Las credenciales de acceso para probar los diferentes niveles de permisos (jugador, trabajador, superadministrador) se encuentran detalladas en el **Anexo I** del documento PDF adjunto.
