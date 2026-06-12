# Suratech Plugin

Plugin de Claude Code para el equipo de Suratech Chile.

## Instalación

```bash
claude plugin install github:crisloks/suratech-plugin
```

## Requisitos

- Claude Code instalado
- Abrir Claude Code desde el directorio raíz del proyecto SURA (donde vive `gobierno-arquitectura/`)

## Contenido actual

| Directorio | Estado | Descripción |
|---|---|---|
| `agents/construir-historia` | ✅ Activo | Ensambla historias técnicas completas para Azure DevOps |
| `skills/` | 🔜 Próximo | Slash commands por capa tecnológica |
| `hooks/` | 🔜 Próximo | Automatizaciones (on-spec-change, on-pr-open) |
| `standards/` | 🔜 Próximo | Estándares técnicos versionados (API, seguridad, logging, testing) |

## Uso

Una vez instalado el plugin, invocar el agente desde una sesión de Claude Code:

```
Construye la historia TS-MOK-03
```

```
Necesito una historia para exponer GET /v1/autos/planes para que Frontend consulte los planes disponibles
```

## Actualizar el plugin

```bash
claude plugin update suratech
```

## Contribuir

Los cambios al plugin se proponen vía Pull Request. El líder técnico de Suratech revisa y aprueba antes del merge.
