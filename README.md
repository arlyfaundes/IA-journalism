# IA y periodismo

Monitoreo diario sobre usos de inteligencia artificial generativa en medios de comunicacion y periodismo, con foco en America Latina.

## Como funciona

- Consulta GDELT DOC 2.0 una vez al dia mediante GitHub Actions.
- Filtra resultados a medios de noticias identificables.
- Genera informes Markdown en `reports/`.
- Publica informes HTML en `docs/` para GitHub Pages.
- Incluye graficos automaticos sobre tipos de uso de GenIA, paises/regiones y temas editoriales.

## Publicacion

En GitHub Pages, configurar:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/docs`

El workflow se puede ejecutar manualmente desde Actions o de forma diaria por cron.
