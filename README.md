# Project Base Template

Repositorio plantilla (Template Repository) preconfigurado con gobernanza de ramas, workflows de GitHub Actions, plantillas de issues/PRs y estructura base para proyectos IT.

---

## Qué incluye este Template

### 1. Gobernanza de GitHub (`.github/`)
- **Workflows:**
  - `branch-policy.yml`: Validación de políticas y convenciones de ramas (Git Flow / Conventional Branches).
  - `pr-labeler.yml` y `issue-labels.yml`: Etiquetado automático de PRs e issues.
  - `backport.yml`: Gestión de retro-portes automáticos de releases hacia develop.
- **Issue Templates (`.github/ISSUE_TEMPLATE/`):**
  - Historias de usuario (`story.yml`) y Tickets técnicos (`ticket.yml`).
  - Reporte de errores (`bug_report.yml`), Requerimientos (`feature_request.yml`), Deuda técnica (`tech_debt.yml`).
- **PR Templates:** Estructurados con checklists de entrega y revisión (`pull_request_template.md`, `release.md`).
- **Políticas de contribución y seguridad:** `CONTRIBUTING.md`, `SECURITY.md`, `labeler.yml`.

### 2. Estructura de Proyecto
- `docs/`: Carpeta para la documentación del proyecto.
- `.gitignore`: Configuración limpia para SO, editores y variables de entorno.
- `.gitattributes`: Normalización de finales de línea y archivos binarios.

---

## Cómo usar este Template

1. En GitHub, haz clic en **Use this template** ➔ **Create a new repository**.
2. Marca la opción **"Include all branches"** para heredar tanto `master` como `develop`.
3. Clona tu nuevo repositorio y comienza a desarrollar siguiendo el flujo de ramas documentado en `CONTRIBUTING.md`.
