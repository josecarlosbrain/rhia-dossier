# rhia-dossier (Claude Code plugin)

Análisis de idoneidad + dossier de verificación de **una** hoja de vida, publicado como **Artifact** HTML compartible. El motor es **Claude** (lee el PDF directamente) — sin API externa ni pipeline local; corre en desktop, web y **celular**.

## Instalar
```
/plugin marketplace add josecarlosbrain/rhia-dossier
/plugin install rhia-dossier@rhia
```
## Usar
Adjuntá una HV (PDF) en el chat y pedí "genera el análisis y dossier". Opcional: dá un cargo/perfil para evaluar el requisito mínimo; si no, evaluación general.

⚠️ La HV entra a la sesión de Claude (nube) = dato personal.
