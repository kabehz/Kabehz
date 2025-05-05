# 🧪 Release Candidate v0.4.0-RC - AstroKit CI/SDLC

> Versión candidata al cierre para la línea base funcional de JaSiLez con validación SDLC modular.

## ✅ Objetivos
- Integrar validación SemVer automática.
- Añadir gates de seguridad (CodeQL, OPA, OSS Licenses).
- Consolidar entregables técnicos de módulos Odoo y manuales complementarios.

## 📦 Contenido del Release
- `*.pdf` / `*.docx`: Documentación de arquitectura, módulos, guía Docker y onboarding.
- `.github/workflows`: Pipeline CI completo.
- `README-release-v0.4.0-RC.md`: Este archivo.

## 🔐 Validaciones Pre-PR
- [x] Commits cumplen convención (Conventional Commits)
- [x] Pruebas automatizadas pasan (pytest)
- [x] Auditoría estática (flake8, CodeQL)
- [x] Validación de políticas OPA
- [x] Chequeo de licencias OSS

## 📋 Checklist Humano para Cierre PR
- [ ] Revisar y firmar el manifiesto de versión (SemVer tag `v0.4.0-RC`)
- [ ] Aprobar Pull Request por al menos un maintainer con rol `@security` o `@qa`
- [ ] Confirmar que todos los checks en GitHub Actions están verdes ✅
- [ ] Merge a `main` desde `release/v0.4.0-RC`

---

© JaSiLez | AstroKit CI/SDLC `v2` — Licencia EUPL 1.2
