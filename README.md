# Suratech Plugin

Plugin de Claude Code para el equipo de Suratech.

## Instalación

```bash
claude plugin install github:crisloks/suratech-plugin
```

## Contenido actual

| Artefacto | Estado | Descripción |
|---|---|---|
| `CLAUDE.md` | ✅ Activo | Lineamientos de equipo: identidad, validación, idioma, colaboración |
| `skills/` | 🔜 Próximo | Slash commands por capa tecnológica |
| `hooks/` | 🔜 Próximo | Automatizaciones (on-spec-change, on-pr-open) |

## Agentes del equipo

Los agentes viven en cada proyecto, no en el plugin. Al abrir un proyecto del equipo en Claude Code, el `CLAUDE.md` del proyecto indica qué agentes están disponibles y cómo invocarlos.

## Actualizar el plugin

```bash
claude plugin update suratech
```

## Contribuir

Los cambios al plugin se proponen vía Pull Request. El líder técnico de Suratech revisa y aprueba antes del merge.
