## Parte 1 – Configuración y Ramas

1. Clona el repo y crea la rama `feature/<tu_nombre>`.
2. Agrega tu nombre a `participantes.md`.
3. Commit con mensaje: `Agrega <tu_nombre> a la lista de participantes`.

## Parte 2 – Commits y Amend

1. En `README.md` agrega: `Git es una herramienta poderosa`.
2. Commit con mensaje: `cambios varios`.
3. Cambia el mensaje del último commit con `--amend` a: `Agrega frase sobre Git en README`.

## Parte 3 – Conflictos y Merge

1. En `main`, añade al final de `conflicto.md`: `Cambio desde main` y haz commit.
2. En tu rama, añade en la misma posición: `Cambio desde <tu_nombre>` y haz commit.
3. Merge de tu rama en `main`. Resuelve el conflicto dejando: `Cambio final resuelto`.
4. Commit de merge.

## Parte 4 – Reset y Recuperación

1. Crea `nota.md` con: `Commit para prueba de reset` y haz commit.
2. Ejecuta `git reset --soft HEAD~1` (verás tu cambio en staging pero sin commit).
3. Usa `git reflog` para recuperar el commit y re-aplícalo.

## Entrega

Ejecuta y sube la salida:

```bash
git log --oneline --graph --all > resultado_<tu_nombre>.txt
```
