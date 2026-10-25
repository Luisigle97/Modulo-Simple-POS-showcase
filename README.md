# 🛒 Simple POS — Software de Punto de Venta & Facturación a Medida

<p align="center">
  <img src="https://img.shields.io/badge/Estado-Producci%C3%B3n%20Activa-10b981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Producción Activa">
  <img src="https://img.shields.io/badge/Live%20Demo-Hostinger-38bdf8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Demo Hostinger">
  <img src="https://img.shields.io/badge/Desarrollado%20Por-LoNet%20Solutions-f59e0b?style=for-the-badge&logo=shield&logoColor=white" alt="LoNet Solutions">
  <img src="https://img.shields.io/badge/Arquitectura-Dual%20Stack-6366f1?style=for-the-badge&logo=fastapi&logoColor=white" alt="Dual Stack">
  <img src="https://img.shields.io/badge/Dise%C3%B1o-Frontend%20Design-ec4899?style=for-the-badge&logo=figma&logoColor=white" alt="Frontend Design">
</p>

> **Sistema de Punto de Venta (POS), control de inventario, arqueo de caja registradora, facturación térmica y auditoría de transacciones**, desarrollado por **[LoNet Solutions](https://lonetsolutions.com/)**. Diseñado para operar de forma ultrarrápida, sin retrasos, con arquitectura adaptable tanto para servidores locales/nube como para hosting compartido optimizado.

---

## 🌐 Live Demo & Acceso de Prueba en Vivo

El sistema se encuentra desplegado y plenamente operativo para pruebas interactivas en el portal oficial de la agencia y servidores dedicados:

* 🚀 **Live Demo Nativo en LoNet Solutions:** **[https://lonetsolutions.com/demo/pos/](https://lonetsolutions.com/demo/pos/)** (Sandbox 100% independiente con persistencia en navegador)
* 🏢 **Portal de la Agencia:** **[https://lonetsolutions.com/](https://lonetsolutions.com/)**
* 🎫 **Mesa de Soporte Oficial:** **[https://lonetsolutions.com/soporte/](https://lonetsolutions.com/soporte/)**

### 🔑 Credenciales de Acceso Sandbox

| Rol de Usuario | Nombre de Usuario | Contraseña | Capacidades y Alcance |
| :--- | :--- | :--- | :--- |
| **Administrador** | `admin` | `admin123` | Control total: Apertura/cierre de caja, inventario, reportes de ventas, auditoría de cuentas, gestión de usuarios. |
| **Vendedor / Cajero** | `vendedor` | `vendedor123` | Terminal ágil: Registro de ventas, consulta de catálogo, emisión de facturas y visualización de su turno. |

---

## 🎯 100% Personalizable a Medida para su Negocio

En **LoNet Solutions** entendemos que ningún negocio opera exactamente igual que otro. Por ello, **Simple POS** no es un software rígido ni una plantilla genérica: **adaptamos y personalizamos la lógica operativa, flujos de cobro, tipos de venta e integraciones a los requerimientos específicos de cada punto de venta:**

```
  ┌──────────────────────────────────────────────────────────────────┐
  │         ADAPTABILIDAD SECTORIAL A MEDIDA (LoNet Solutions)        │
  └──────────────────────────────────────────────────────────────────┘
         │
         ├── 🍸 Licoreras, Bares & Discotecas
         │    ├── Venta fraccionada (Tragos / Copas / Botellas)
         │    ├── Control estricto de mermas y descorche
         │    ├── Cuentas abiertas y cobro por comandas
         │    └── Promociones dinámicas (2x1, Happy Hours)
         │
         ├── 🍽️ Restaurantes, Cafeterías & Pizzerías
         │    ├── Mapa interactivo de mesas y zonas
         │    ├── Impresión dividida de comandas a cocina y barra
         │    ├── Cuentas separadas por comensal
         │    └── Gestión de adiciones, ingredientes y propinas
         │
         ├── 🛒 Minimarkets, Tiendas de Abarrotes & Supermercados
         │    ├── Soporte nativo para lectores de código de barras (USB/Bluetooth)
         │    ├── Conexión con balanzas y básculas para venta por gramaje/peso
         │    ├── Alertas visuales de stock mínimo y reposición urgente
         │    └── Venta a granel y empaquetados
         │
         ├── 🔧 Ferreterías, Tiendas de Repuestos & Construcción
         │    ├── Búsqueda inteligente por código OEM, referencia técnica o marca
         │    ├── Conversión automática de unidades (metros, pulgadas, kilos, cajas)
         │    ├── Manejo de listas de precios mayorista, técnico y público general
         │    └── Generación de cotizaciones previas antes de facturar
         │
         ├── 💊 Droguerías & Farmacias
         │    ├── Trazabilidad de lotes y fechas de expiración
         │    ├── Buscador alternativo por principio activo (Genérico vs Comercial)
         │    └── Control de fórmulas médicas y despacho asistido
         │
         └── 👗 Tiendas de Ropa, Calzado & Boutiques
              ├── Matrices multidimensionales (Talla / Color / Colección)
              ├── Gestión de cambios, notas de crédito y devoluciones
              └── Etiquetas de precio con código de barras propio
```

---

## 🌟 Características Técnicas y Módulos Principales

### ⚡ 1. Terminal de Ventas de Alta Velocidad (POS)
* **Búsqueda Instantánea:** Filtrado en tiempo real por nombre, categoría o código sin recargas de página.
* **Carrito Dinámico:** Adición inmediata con un solo clic, ajuste de cantidades por teclado o botones táctiles, y advertencia automática si la cantidad solicitada supera el stock disponible.
* **Múltiples Métodos de Pago:** Cobro en Efectivo con cálculo de cambio, Tarjeta débito/crédito, Transferencia bancaria (Nequi, Daviplata, Bancolombia) o Pago Mixto.
* **Facturación Imprimible:** Generación de recibo/factura con desglose completo de productos, impuestos, medio de pago, fecha, cajero responsable y número de comprobante. Compatible con impresoras térmicas (58mm / 80mm) y formatos estándar.

### 💰 2. Control Integral de Caja Registradora (Cash Management)
* **Apertura de Caja con Base Inicial:** Registro obligatorio del monto de dinero base con el que inicia operaciones el cajero.
* **Control de Movimientos:** Entrada y salida de efectivo para gastos menores o pagos a proveedores con motivo documentado.
* **Arqueo y Cierre de Caja:** Comparativa entre ventas registradas por sistema y el dinero físico contado, detectando faltantes o sobrantes de forma automática.

### 📦 3. Gestión Inteligente de Inventario & Catálogo
* Creación, edición y categorización de productos con precio de venta, costo y stock disponible.
* Badges de alerta por **Stock Bajo** para evitar quiebres de inventario no anticipados.
* Modales limpios para reabastecimiento o corrección rápida de existencias.

### 📋 4. Historial de Auditoría & Trazabilidad Inmutable
* Registro cronológico de todas las transacciones realizadas en la plataforma.
* Rastreo de usuario responsable, fecha/hora exacta, tipo de operación (Venta, Apertura, Movimiento de Caja, Ajuste de Inventario) y montos asociados.
* Filtros de consulta para inspecciones financieras y conciliación contable.

### 📊 5. Panel de Métricas & Reportes
* Indicadores clave de rendimiento (KPIs): Total vendido en la jornada, ticket promedio, cantidad de transacciones, producto más vendido y medio de pago predominante.
* Histórico mensual de ventas para análisis comparativo de ingresos.

---

## 🎨 Identidad Visual & Frontend Design

La interfaz del software fue construida siguiendo los estándares de **Frontend Design** de alta gama, alejándose de los patrones genéricos de plantillas prediseñadas:

* **Paleta Cromática Obsidian & Malt Gold:**
  * Fondo base: Obsidian Slate `#090d16` y `#0d1424`.
  * Acentos de lujo: Malt Gold `#f59e0b` y `#fbbf24` con resplandores sutiles en ámbar.
  * Estados funcionales: Esmeralda `#10b981` (ventas exitosas/aprobadas), Rubí `#ef4444` (alertas de stock y bajas de caja), Cian `#38bdf8` (información del sistema).
* **Tipografía Editorial:**
  * Títulos y encabezados: `Outfit` (alta legibilidad geométrica).
  * Textos y cuerpo de datos: `Plus Jakarta Sans`.
  * Valores monetarios, facturas y códigos: `JetBrains Mono` con tabulación numérica uniforme.
* **100% Responsive & Adaptable a Móvil:**
  * Totalmente utilizable desde teléfonos inteligentes (Android / iOS) de meseros y cajeros ambulantes.
  * Disposición optimizada para tablets de mostrador y monitores táctiles de punto de venta.

---

## 🏗️ Arquitectura Dual Stack (Híbrida)

El proyecto cuenta con una arquitectura diseñada para operar de dos formas según la infraestructura del cliente:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        ARQUITECTURA DUAL STACK                         │
└────────────────────────────────────────────────────────────────────────┘

  [Opción 1: Servidores Dedicados / Cloud / Local]
  ┌──────────────────┐       JSON REST API       ┌─────────────────────┐
  │   Frontend Web   │ ◄───────────────────────► │  Python / FastAPI   │
  │   Modern HTML5   │                           │  SQLite / Postgres  │
  └──────────────────┘                           └─────────────────────┘

  [Opción 2: Web Hosting Compartido / Hostinger / Apache / LiteSpeed]
  ┌──────────────────┐       JSON REST API       ┌─────────────────────┐
  │   Frontend Web   │ ◄───────────────────────► │   PHP 8.x Router    │
  │   Modern HTML5   │                           │   MySQL / MariaDB   │
  └──────────────────┘                           └─────────────────────┘
```
## 🤝 Soporte Técnico, Consultoría & Desarrollo a Medida

¿Necesita implementar este punto de venta en su establecimiento comercial o requiere una solución a medida adaptada a la dinámica de su empresa?

* 🏢 **Empresa:** **LoNet Solutions**
* 🌐 **Sitio Web Oficial:** [https://lonetsolutions.com](https://lonetsolutions.com)
* 🎫 **Mesa de Ayuda & Tickets:** [https://lonetsolutions.com/soporte/](https://lonetsolutions.com/soporte/)
* 📧 **Correo Electrónico:** [contacto@lonetsolutions.com](mailto:contacto@lonetsolutions.com) / [solutionslonet@gmail.com](mailto:solutionslonet@gmail.com)
* 📱 **WhatsApp Directo:** [+57 301 7686592](https://wa.me/573017686592)
* 📍 **Ubicación:** Cartagena de Indias, Colombia

---

<p align="center">
  <sub>Desarrollado con dedicación e ingeniería de software de alto impacto por <strong>LoNet Solutions</strong> © 2026. Todos los derechos reservados.</sub>
</p>
