# task-manager

Roadmap personal de proyectos en un único archivo HTML, sin servidor ni dependencias.

## Uso

1. Abre `roadmap.html` en **Edge o Chrome** (usa la File System Access API).
2. La primera vez, elige la carpeta donde está el HTML. La app crea ahí sus archivos de datos:
   - `roadmap_tareas.json` — proyectos, fases y tareas
   - `roadmap_hist_cambios.txt` — historial de cambios
   - `roadmap_proyectos_eliminados.json` — copia de los proyectos borrados
3. Las siguientes veces basta con un clic para volver a dar permiso a la carpeta.

Los archivos de datos están en `.gitignore` y no se suben al repositorio.
