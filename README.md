# TerritoryOps — Sistema PWA de Gestión y Enrutamiento Territorial (600+ Familias)

[![Live Demo](https://img.shields.io/badge/Live_Demo-TerritoryOps_PWA-1D4ED8?style=flat-square&logo=googlechrome&logoColor=white)](https://alexandericastro.github.io/territory-ops-pwa/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![Architecture](https://img.shields.io/badge/Architecture-Offline--First_PWA-F59E0B?style=flat-square)](https://alexandericastro.github.io/)
[![Case Study](https://img.shields.io/badge/Portfolio_Case_Study-alexandericastro.github.io-0F766E?style=flat-square)](https://alexandericastro.github.io/#work)

**TerritoryOps** es una Progressive Web App (PWA) de tecnología cívica y operaciones de campo (MEAL) diseñada para resolver la fragmentación operativa en territorios periurbanos de alta vulnerabilidad.

Reemplaza los cuellos de botella manuales en hojas de cálculo y mensajería en **17 grupos territoriales (más de 600 familias beneficiarias)** mediante un sistema de enrutamiento autoservicio, verificación fotográfica con recorte en cliente (`Cropper.js`), resiliencia *Offline-First* y trazabilidad auditable.

---

### 📊 Impacto Operativo Comprobado

* **Cumplimiento de indicadores (MEAL):** Elevación del **30% al 65%** en 5 meses de despliegue territorial continuo.
* **Escalabilidad:** Cobertura de **610 familias y 17 sectores comunitarios**.
* **Autonomía en campo:** Registro y verificación en zonas con conectividad intermitente (0% pérdida de datos por sincronización en `localStorage`).

---

### 🌟 Módulos de la Aplicación

1. **Portal Familiar & Enrutamiento Autónomo:**
   * Búsqueda en tiempo real por código de familia (`FAM-101`) o apellidos.
   * Consulta de sedes asignadas, turnos, jornadas comunitarias y mingas territoriales.
   * Formulario digital de justificación de inasistencia y solicitud de reasignación de sector.

2. **Terminal de Líderes de Voluntariado & Operadores:**
   * Selección rápida de turno y lista activa de participantes por sector.
   * Toma de asistencia con verificación fotográfica integrada (`Cropper.js`) para validar actividades en terreno.
   * Control de incidencias y gestión de grupos.

3. **Dashboard de Supervisión & Métricas Territoriales:**
   * Monitoreo en tiempo real del porcentaje de asistencia por sector.
   * Estadísticas demográficas y consolidación de reportes de cumplimiento.

---

### 🚀 Demostración en Vivo
Puedes probar la aplicación interactiva directamente desde cualquier dispositivo:  
👉 [**Abrir TerritoryOps PWA en Vivo**](https://alexandericastro.github.io/territory-ops-pwa/)

*(Nota: Esta versión pública opera en modo demostración con un dataset completamente sanitizado de 17 sectores y participantes ficticios).*

---

### 🛠️ Stack Tecnológico

* **Frontend:** Semantic HTML5, CSS3 Glassmorphism (Mobile-Native), Vanilla JavaScript (ES6+).
* **Motor Offline-First:** Resiliencia local vía Web Storage API (`localStorage`) y sincronización por lotes.
* **Procesamiento de Imagen en Cliente:** `Cropper.js` para compresión y encuadre fotográfico antes del registro.

---
<sub>Desarrollado y diseñado por **Alexander Imbaquingo** (Jaime Alexander Imbaquingo Castro) · [alexandericastro.github.io](https://alexandericastro.github.io/)</sub>
