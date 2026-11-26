# PictoPlan - Práctica 9 (Gestión de la configuración)

Repositorio de la **Práctica 9** de *Planificación y Gestión de Proyectos Informáticos* (Máster en Ingeniería Informática, UGR, curso 2026/2027).
Simula el seguimiento y el control de la implementación de dos tareas en paralelo del proyecto **PictoPlan** (agenda accesible para el Colegio de Educación Especial Purísima Concepción), con **Git** y **Jira**. Los ficheros de texto simulan el código.

Equipo **PM&GA S.L.**: Pablo Maté Gómez y Germán Álvarez Gavilán.

## Ramas

| Rama | Tipo | Responsable | Miembros que trabajan en ella |
|---|---|---|---|
| `main` | Principal (cambios finales, ya funcionando) | Ambos | Pablo, Germán |
| `Tarea1_Usuarios` | Tarea 1: usuarios, roles y perfiles | **Pablo Maté Gómez** | Pablo, Germán |
| `Tarea1_Usuarios_Pablo` | Rama personal de la tarea 1 | Pablo Maté Gómez | Pablo |
| `Tarea1_Usuarios_German` | Rama personal de la tarea 1 | Germán Álvarez Gavilán | Germán |
| `Tarea2_TareasCentro` | Tarea 2: tareas del centro (reprografía, comedor, menú) | **Germán Álvarez Gavilán** | Pablo, Germán |
| `Tarea2_TareasCentro_Pablo` | Rama personal de la tarea 2 | Pablo Maté Gómez | Pablo |
| `Tarea2_TareasCentro_German` | Rama personal de la tarea 2 | Germán Álvarez Gavilán | Germán |
| `<CLAVE-XX>-...` | Corrección de una incidencia de Jira | Cualquier miembro | Se indicará al crearla |

## Flujo de trabajo

1. El responsable de cada tarea crea la rama de la tarea desde `main` y la inicializa con dos ficheros.
2. Cada miembro crea su rama personal desde la rama de la tarea, hace al menos dos commits y la une a la rama de la tarea.
3. Cuando todos han terminado, el responsable une la rama de la tarea con `main`.
4. Con las dos tareas en `main` se etiqueta la versión **v1.0**.
5. Se conecta el repositorio con Jira, se crea una incidencia y se corrige en una rama con su clave (`CLAVE-XX`), y se etiqueta **v1.1**.

Las normas de ramas, commits y uniones están en [CONTRIBUTING.md](CONTRIBUTING.md). Los commits de incidencias empiezan por la clave de Jira (`CLAVE-XX Resumen`).

## Versiones

| Etiqueta | Contenido |
|---|---|
| `v1.0` | Tareas 1 y 2 unidas en `main` |
| `v1.1` | Incidencia de Jira corregida |
