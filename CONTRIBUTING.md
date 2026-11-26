# Cómo contribuir

Normas de trabajo del equipo PM&GA S.L. en este repositorio (resumen del plan de gestión de la configuración del proyecto).

## Ramas
- `main`: solo contiene cambios finales que ya funcionan. **No se hace commit ni push directo en `main`**: solo se une una rama de tarea ya terminada.
- Rama de tarea: `TareaN_Nombre` (por ejemplo `Tarea1_Usuarios`). La crea el **responsable** de la tarea a partir de `main`.
- Rama personal: `TareaN_Nombre_Miembro` (por ejemplo `Tarea1_Usuarios_Pablo`). La crea cada miembro a partir de la rama de la tarea ya inicializada.
- Rama de incidencia: `CLAVE-XX-descripcion` (por ejemplo `PICTO-1-corrige-perfil`), con la clave de la incidencia de Jira.

## Commits
- Mensaje corto, en español y en imperativo o presente: `Tarea 1 (Pablo): asigna un tutor a cada estudiante`.
- Mínimo **dos commits** por miembro en su rama personal antes de darla por terminada.
- Los commits de incidencias empiezan por la clave de Jira: `CLAVE-XX Resumen del cambio`.

## Uniones (merge)
1. El miembro une su rama personal con la rama de la tarea.
2. Cuando todos han terminado, el **responsable de la tarea** une la rama de la tarea con `main`.
3. Todas las uniones se hacen con `--no-ff` para conservar el historial de cada rama.
4. Antes de unir, se actualiza la rama con `git pull` y se resuelven los conflictos hablando con el otro miembro.

## Versiones
Cada hito se etiqueta sobre `main` con `vX.Y` (`v1.0`: tareas 1 y 2; `v1.1`: incidencia de Jira corregida).
