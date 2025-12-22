---
name: "🛠️ Tarea Técnica"
about: Tareas de limpieza, actualización de dependencias o refactorización interna.
title: "[CHORE] <Tarea de mantenimiento>"
labels: "Mantenimiento"
assignees: ""
---

## 1. Objetivo Técnico

**Tipo de Tarea:** [Refactor / Update / Cleanup / Config]
**Justificación:** ¿Por qué es necesario hacer esto ahora? (e.g. Vulnerabilidad de seguridad, deprecación, código sucio).

---

## 2. Alcance del Cambio

**Librerías/Dependencias:**

- Actualizar `paquete-x` de v1.0 a v2.0.

**Archivos/Directorios:**

- Limpieza en `src/legacy/...`

---

## 3. Plan de Ejecución

- [ ] Leer changelog de dependencias.
- [ ] Actualizar `package.json`.
- [ ] Adaptar breaking changes en el código.
- [ ] Correr suite de pruebas completa.

---

## 4. Plan de Rollback

**Riesgo:** [Bajo / Medio / Alto]
**Acción en caso de fallo:** (e.g. Revertir commit, bajar versión de librería).

---

## 5. Criterios de Aceptación

- [ ] El proyecto compila correctamente.
- [ ] Todos los tests automáticos pasan.
- [ ] El linter no arroja errores.
