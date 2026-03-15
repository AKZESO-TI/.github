# 👋 Bienvenido a AKZESO LOGÍSTICA

AKZESO LOGÍSTICA es una plataforma tecnológica y operativa enfocada en la gestión integral de eventos masivos. Nuestra solución integra herramientas para la **logística de eventos, emisión de entradas, control de accesos y acreditaciones**, permitiendo a organizadores y productoras administrar sus eventos de forma eficiente, segura y escalable.

Este proyecto reúne el desarrollo de los diferentes portales y servicios que componen el ecosistema tecnológico de AKZESO LOGÍSTICA.

---

# 🚀 Qué estamos construyendo

La plataforma está compuesta por varios módulos y portales que trabajan de forma integrada:

### 🌐 Landing Page
Portal público donde se presentan los servicios de la empresa y se capturan solicitudes comerciales.

Funciones principales:
- Presentación de servicios
- Información corporativa
- Formulario de contacto
- Captura de leads

Tecnologías:
- Angular 20
- TypeScript
- CSS moderno (Flexbox / Grid)

---

### 🎟 Portal de Eventos
Portal para usuarios finales donde podrán:

- Comprar entradas
- Registrarse para eventos
- Completar formularios
- Validar su acceso al evento
- Descargar o mostrar su ticket digital

---

### ⚙ Portal Administrativo
Plataforma interna para la gestión completa de eventos.

Funciones principales:

- Creación y configuración de eventos
- Gestión de personal logístico
- Acreditaciones
- Control de acceso
- Gestión de tickets
- Reportes operativos

---

### 📡 API de Integración
Backend central que permite integrar la plataforma con:

- Aplicaciones móviles
- Dispositivos de lectura de tickets
- Sistemas externos de eventos
- Herramientas de analítica

Funciones clave:

- Validación de tickets en tiempo real
- Gestión de eventos
- Control de accesos
- Registro de validaciones

---

# 🏗 Arquitectura tecnológica

El proyecto utiliza una arquitectura moderna basada en APIs y separación de responsabilidades.

### Backend
- **PHP 8.1**
- **Laravel 10**
- **MySQL**
- API REST

### Frontend
- **Angular 20**
- TypeScript
- Arquitectura modular

### Infraestructura
- Hosting: **Hostinger Business**
- Control de versiones: **GitHub**
- Base de datos: **MySQL**

### Integraciones
- APIs para dispositivos móviles de lectura de tickets
- Validación de accesos en tiempo real
- Integración con herramientas de mensajería y notificaciones

---

# 📁 Estructura del proyecto

El ecosistema de AKZESO LOGÍSTICA se compone de varios repositorios:
akzeso-logistica
│
├── landing-frontend
│ └── Landing pública (Angular)
│
├── landing-backend
│ └── API y servicios backend (Laravel)
│
├── admin-portal
│ └── Plataforma administrativa
│
├── eventos-portal
│ └── Portal de usuarios y compra de entradas
│
└── api-specs
└── Documentación OpenAPI


---

# 🧪 Estado del proyecto

Actualmente el desarrollo se encuentra en las siguientes fases:

- ✅ Infraestructura inicial
- ✅ Configuración de dominios y base de datos
- ✅ Conexión con GitHub
- 🚧 Desarrollo de Landing Page
- 🚧 Arquitectura base del backend
- 🔜 Portal de eventos
- 🔜 Portal administrativo
- 🔜 APIs para validación de tickets

---

# 👩‍💻 Desarrollo

### Requisitos

- Node.js
- Angular CLI
- PHP 8.1
- Composer
- MySQL
- Git

---

### Ejecutar Frontend

```bash
npm install
ng serve

composer install
php artisan serve
