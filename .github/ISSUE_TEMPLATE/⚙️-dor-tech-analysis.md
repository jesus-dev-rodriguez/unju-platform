---
name: ⚙️ DoR - Análisis Técnico
about: [Sello 3] Definición profunda de arquitectura, datos, API y estrategia de implementación.
title: "[TECH]: "
labels: "DoR: Análisis Técnico, Estado: Definición"
assignees: ""
---

### 🔗 Datos y API
- **Modelo de Datos:** [Esquema SQL aquí]
- **Contrato API:** [Especificación aquí]
- **Requisito:** [Enlace/ID ticket]
- **Responsable:** [Nombre]

### 🔄 Lógica y Patrones
- **Patrones:** Strategy, Repository, Observer
- **Flujo:** Validar → Autenticar → Procesar → Persistir
- **Endpoint:** [Método] /api/v1/[recurso]

### 🛡️ Seguridad y Performance
- **Roles:** [admin|user|manager]
- **Auth:** JWT / API Key
- **Caching:** Redis (TTL: [300]s)
- **Paginación:** [50] registros/página
- **Validaciones:** Formato, unicidad, seguridad

### 🚀 Plan de Despliegue
- **Breaking Changes:** [Sí/No]
- **Variables:** API_KEY_NEW_SERVICE, REDIS_CACHE_TTL
- **Dependencias:** [Nuevos paquetes]
- **Estrategia:** Feature flags + Canary release