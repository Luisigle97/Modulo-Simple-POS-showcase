# 🛒 Simple POS — Software de Punto de Venta, Mesas, Comandas & Control Comercial

<p align="center">
  <img src="https://img.shields.io/badge/Estado-Producci%C3%B3n%20Activa-10b981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Producción Activa">
  <img src="https://img.shields.io/badge/Live%20Demo-lonetsolutions.com-38bdf8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Demo">
  <img src="https://img.shields.io/badge/Desarrollado%20Por-LoNet%20Solutions-f59e0b?style=for-the-badge&logo=shield&logoColor=white" alt="LoNet Solutions">
  <img src="https://img.shields.io/badge/Arquitectura-FastAPI%20%2B%20PHP%208%20SQLite-6366f1?style=for-the-badge&logo=sqlite&logoColor=white" alt="Dual Stack">
  <img src="https://img.shields.io/badge/UX-Responsive%20%3C1200px%20Card--List-ec4899?style=for-the-badge" alt="Responsive UX">
</p>

> **Plataforma POS de alta velocidad con Control Visual de Mesas, Comandas Móviles por Wi-Fi, Monitor KDS Cocina & Barra, Pago Individual / División de Cuentas, Auditoría Forense, Rendimiento de Meseros, Gestión de Imágenes y Arqueo de Caja Z**, desarrollada por **[LoNet Solutions](https://lonetsolutions.com/)**. Arquitectura Dual Stack adaptable tanto para operación local offline (`FastAPI + SQLite WAL`) como para despliegue web en hosting compartido (`PHP 8 + SQLite`).

---

## 🌐 Ecosistema, Live Demo & Repositorios

* 🚀 **Live Demo Interactivo (Marca Dinámica):** **[https://lonetsolutions.com/demo/pos/](https://lonetsolutions.com/demo/pos/)** — Sandbox comercial completo configurable con `[Nombre de tu Negocio]` y logotipo en cabecera y tirillas.
* 🎨 **Showcase Público:** **[https://github.com/Luisigle97/Modulo-Simple-POS-showcase](https://github.com/Luisigle97/Modulo-Simple-POS-showcase)**
* 🏢 **Portal de la Agencia:** **[https://lonetsolutions.com/](https://lonetsolutions.com/)**
* 🎫 **Mesa de Soporte Oficial:** **[https://lonetsolutions.com/soporte/](https://lonetsolutions.com/soporte/)**

### 🔑 Credenciales de Acceso Demo / Pruebas

| Rol de Usuario | Usuario | Contraseña | Capacidades y Alcance |
| :--- | :--- | :--- | :--- |
| 👑 **Super Admin** | `admin` | `admin123` | Control total: Mesas, POS, Finanzas, Rendimiento de Meseros y Liquidación de Propinas, Auditoría, Gestión de Imágenes, Compras, Gastos, Usuarios y Excel. |
| 🧾 **Cajero / Barra** | `cajero` | `cajero123` | Mapa de mesas, cobro completo e individual/dividido, POS Rápido, Caja Z + Datáfono, KDS Cocina & Barra, historial de tickets y pausa rápida de platos agotados. |
| 📱 **Mesero Móvil** | `mesero` | `mesero123` | Toma de comandas por rondas con notas táctiles, mapa visual de mesas en tiempo real, pre-cuenta con divisor `÷ N` y solicitud de cuenta sin acceso a caja ni costos. |

---

## 🎯 100% Personalizable a Medida (Marca Blanca & Multi-Sector)

En **LoNet Solutions** personalizamos nombre comercial, logotipo en cabecera y tirillas térmicas, zonas de atención, flujos de cocina/barra, impuestos y reglas de negocio según cada cliente:

```
  ┌──────────────────────────────────────────────────────────────────┐
  │         ADAPTABILIDAD SECTORIAL A MEDIDA (LoNet Solutions)        │
  └──────────────────────────────────────────────────────────────────┘
         │
         ├── 🍽️ Restaurantes, Clubes de Playa & Gastrobares
         │    ├── Mapa visual de mesas por zonas (LIBRE, OCUPADA, CUENTA, RESERVADA)
         │    ├── Comandas móviles por rondas vía Wi-Fi QR sin instalar apps
         │    ├── Monitor KDS Cocina & Barra FIFO con semáforos y timbre
         │    └── Pago individual / división de cuentas (Por Ítems o Partes Iguales)
         │
         ├── 🍸 Licoreras, Bares & Discotecas
         │    ├── Venta rápida por mostrador, barra o domicilio (POS Rápido)
         │    ├── Control estricto de stock físico por botellas, cervezas y licores
         │    ├── Pausa inmediata Disponible / Agotado en tiempo real
         │    └── Datáfono configurable, pagos mixtos y cierre de lote
         │
         ├── 🛒 Minimarkets, Tiendas & Cafeterías
         │    ├── Buscador predictivo con auto-reset inteligente de categoría
         │    ├── Selector desplegable de categorías unificado (Móvil, Tablet y PC)
         │    ├── Cálculo automático de devuelta en efectivo e IVA / Impoconsumo
         │    └── Arqueo de caja con Reporte Z e impresión térmica 80mm / WhatsApp
         │
         └── ⚙️ Administración, Nómina de Propinas & Auditoría
              ├── Podio Top 3 de Meseros, KPIs y liquidación de propinas Efectivo vs Electrónico
              ├── Bitácora forense con motivo obligatorio en anulaciones y eliminaciones
              ├── Gestor visual de fotografías por producto (Drag & Drop JPG/PNG/WEBP)
              └── Identidad dinámica ([Nombre de tu Negocio] + Logo) en cabecera y tickets
```

---

## 🌟 Características Técnicas y Módulos Actualizados

### 🗺️ 1. Control Visual de Mesas & Comandas Móviles (`Wi-Fi QR`)
* Mapa por zonas con actualización automática (~2.5s), estados codificados por color (`LIBRE`, `OCUPADA`, `💳 CUENTA` titilando, `RESERVADA`), contador de tiempo (`⏱ Xm`) y transferencia entre mesas libres.
* Flujo optimizado para meseros desde teléfono o tablet: rondas incrementales (`Ronda #1`, `Ronda #2`), notas rápidas táctiles, pre-cuenta y divisor rápido `÷ N`.

### 🔥 2. Monitor KDS Cocina & Barra FIFO
* Tickets agrupados por mesa y ronda, con filtro por estación (`Todos`, `🔥 Cocina`, `🍹 Barra`), alertas cromáticas a 10 y 20 minutos y timbre sonoro opcional.
* Progresión en un toque: **`🔥 Empezar`** → **`✅ ¡Listo!`** → **`🍽️ Entregado`**.

### 💳 3. Cobro de Mesas, Cuentas Separadas & Datáfono Configurable
* **Cobro Completo o Individual / Dividido:** liquidación **`Por Ítems`** (seleccionando cantidades exactas por comensal) o **`Partes Iguales / Monto Libre`**, generando tickets independientes hasta liberar automáticamente la mesa al saldar el 100%.
* **Medios de Pago:** `Efectivo` con devuelta automática, `Nequi / Daviplata`, `💳 Datáfono`, `Transferencia` y `🔀 Pago Mixto`.
* **Conector Datáfono:** **Simulador Local**, **Webhook / API Externa (HMAC)** o **Asistido Manual**, con captura de voucher, franquicia, últimos 4 dígitos y control de comisiones/retención bancaria.

### 📱 4. POS Rápido Rediseñado & UX Responsive (`< 1200px` sin Scroll Horizontal)
* **POS Rápido táctil:** interfaz móvil y tablet en pestañas limpias (*Catálogo* / *Pedido*) con barra inferior adhesiva (*sticky bar*) y selector desplegable unificado de categorías también en escritorio (`>= 1200px`). Al buscar por texto, el filtro vuelve automáticamente a **`Todos`**.
* **Card-List Layout:** todas las tablas operativas (*Carta & Stock*, *Meseros*, *Auditoría*) se transforman en tarjetas verticales estructuradas en móvil y tablet con áreas táctiles mínimas de `44x44px`.
* **Modales Seguros y Personalizados:** menú principal en `< 1200px` con accesos rápidos y enlaces a LoNet Solutions, manual interactivo con selector desplegable y modal de confirmación personalizado (`#modal-confirm`) para acciones críticas.

### 🖼️ 5. Carta, Stock Inteligente & Gestión de Imágenes por Producto
* Distinción entre platos **Preparados al momento** y productos con **Control de stock físico** (restauración automática ante anulaciones o devoluciones).
* **Gestor Drag & Drop de Fotografías:** carga `JPG`, `PNG` o `WEBP` (hasta 5 MB) con validación de firma real (*magic bytes*), vista previa cuadrada `aspect-square` y eliminación segura que limpia archivos huérfanos en servidor.

### 🏆 6. Rendimiento de Meseros, Podio Top 3 & Liquidación de Propinas (`Admin`)
* Filtros por período (**`Hoy`**, **`Esta semana`**, **`Este mes`**, **`Personalizado`**), **Podio Top 3**, ticket promedio y desglose exacto de propinas en **Efectivo vs Electrónico**.
* Flujo de **Liquidación de Propinas** (`PENDIENTE → ENTREGADA`), historial de entregas y exportación en Excel.

### 🛡️ 7. Auditoría Forense & Trazabilidad (`Admin`)
* Registro automático con metadata estructurada de **Apertura de Caja**, **Cierre / Arqueo Z**, **Anulaciones con motivo obligatorio**, **Eliminaciones de comandas/registros**, **Descuentos manuales**, **Cambios de precio**, **Liquidación de propinas** y **Gestión de imágenes**.
* Filtros combinados por **rango de fechas**, **usuario**, **tipo de evento** y **buscador rápido**.

---

## 🏗️ Arquitectura Dual Stack (Local & Nube Hosting)

```
┌────────────────────────────────────────────────────────────────────────┐
│                        ARQUITECTURA DUAL STACK                         │
└────────────────────────────────────────────────────────────────────────┘

  [Opción 1: Local Wi-Fi Offline / Servidor VPS — Simple-Pos-Restaurante]
  ┌──────────────────┐       JSON REST API       ┌─────────────────────┐
  │  Frontend HTML5  │ ◄───────────────────────► │  Python / FastAPI   │
  │  Tailwind + Lucide│                           │  SQLite WAL + Excel │
  └──────────────────┘                           └─────────────────────┘

  [Opción 2: Web Hosting Compartido / Hosting — /demo/pos/]
  ┌──────────────────┐       JSON REST API       ┌─────────────────────┐
  │  Frontend HTML5  │ ◄───────────────────────► │  PHP 8.x PDO Router │
  │  Branding Dinámico│                           │  SQLite 3 Local     │
  └──────────────────┘                           └─────────────────────┘
```

---

## 🤝 Soporte Técnico, Consultoría & Desarrollo a Medida

¿Necesita implementar este punto de venta en su restaurante, bar o comercio con facturación personalizada?

* 🏢 **Empresa:** **LoNet Solutions**
* 🌐 **Sitio Web Oficial:** [https://lonetsolutions.com](https://lonetsolutions.com)
* 🎫 **Mesa de Ayuda & Tickets:** [https://lonetsolutions.com/soporte/](https://lonetsolutions.com/soporte/)
* 📧 **Correo Electrónico:** [contacto@lonetsolutions.com](mailto:contacto@lonetsolutions.com) / [solutionslonet@gmail.com](mailto:solutionslonet@gmail.com)
* 📱 **WhatsApp Directo:** [+57 301 7686592](https://wa.me/573017686592)
* 📍 **Ubicación:** Cartagena de Indias, Colombia

---

<p align="center">
  <sub>Desarrollado por <strong>LoNet Solutions</strong> © 2026. Todos los derechos reservados.</sub>
</p>
