<p align="center">
  <img width="" src="./src/assets/fideposWeb.png" alt="FidePOSWEB"/>
</p>

<h3 align="center">
Web de aplicación de escritorio de punto de venta para PyMEs. Permite gestionar ventas, inventario, ingresos y pérdidas con reportes claros y en tiempo real, ayudando a mejorar la eficiencia y el control financiero del negocio.
</h3>

---

<h2 align="center">Stack Tecnológico 🧑‍💻</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=astro,tailwind" />
  </a>
</p>

## Features 🛠️

- 📦 **Gestión de Inventario:** Control total sobre productos, categorías y stock.
- 👥 **Administración de Clientes:** Seguimiento de deudas, historial de pagos y perfiles.
- 📊 **Dashboard Interactivo:** Visualización de métricas clave y estadísticas de venta mediante gráficas.
- 📄 **Reportes Profesionales:** Generación y exportación de datos en formatos **PDF, Excel y CSV**.
- 🖥️ **Arquitectura de Escritorio:** Ejecución local segura y rápida (vía Electron).
- 🌐 **Soporte Multi-idioma:** Inglés y Español con i18n.

<br/>

> [!IMPORTANT]
> ⚠️ Configuración de Credenciales de Correo (Opción: Importar Archivo)
>
> Actualmente, el sistema presenta una limitación técnica al utilizar la Opción 2 (Importar base de datos existente).
>
> Al importar un archivo .db, el flujo de inicio omite la configuración de las credenciales de email. Esta configuración solo se completa de forma automática cuando se genera una base de datos nueva desde cero.

<h2 align="center">Project Setup 🚀</h2>

### 📄 Requisitos previos

- Node.js
- npm

### 📁 Clonar Repositorio

To use this project locally, run the following commands in your terminal:

```bash
git clone https://github.com/EricV29/fidePOS-web.git
cd fidePOS-web
npm install
```

## 📸 Sistema

| Vista del Sistema                           | Descripción                                                                                                                                                                                         |
| :------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Dashboard](./src/assets/welcome.png)      | **Bienvenida:** Dos opciones de arranque: 1. Base de Datos nueva con o sin credenciales para correos electrónicos. 2. Si ya tienes una Base de Datos de FidePOS agregala y coloca tus credenciales. |
| ![Dashboard](./src/assets/dashboard.png)    | **Panel Principal:** Visualización de métricas de ventas diarias, ganancias y estado general del negocio mediante gráficas interactivas.                                                            |
| ![Inventory](./src/assets/nuevaVenta.png)   | **Ventas:** Interfaz ágil para registrar nuevas ventas, aplicar descuentos y procesar diferentes métodos de pago.                                                                                   |
| ![Customers](./src/assets/inventario.png)   | **Inventario:** Control total de stock, categorías y precios.                                                                                                                                       |
| ![Export](./src/assets/historial.png)       | **Historial de Ventas:** Registro cronológico detallado de todas las transacciones realizadas.                                                                                                      |
| ![Export](./src/assets/clientesGeneral.png) | **Clientes:** Directorio centralizado para gestionar la información de contacto y perfiles de compradores frecuentes.                                                                               |
| ![Export](./src/assets/clientesPagos.png)   | **Deudas y Pagos de Clientes:** Seguimiento especializado de créditos, saldos pendientes y registro histórico de abonos de clientes.                                                                |
| ![Export](./src/assets/reportes.png)        | **Reportes:** Interfaz Herramienta para exportar métricas de rendimiento y cierres de caja en formatos profesionales como PDF y Excel.                                                              |
| ![Export](./src/assets/configuracion.png)   | **Configuración:** Personalización del sistema, gestión de usuarios y gestion de categorías.                                                                                                        |
