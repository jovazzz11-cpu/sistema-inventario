# Guía de Publicación (Deploy)

Tu proyecto ya está listo y guardado localmente con Git. Sigue estos pasos para subirlo a Internet usando **GitHub Pages**.

## Paso 1: Crear Repositorio en GitHub

1. Ve a [github.com/new](https://github.com/new) e inicia sesión.
2. En "Repository name", escribe: `sistema-inventarios` (o el nombre que prefieras).
3. Asegúrate de que esté seleccionado **Public**.
4. **NO** marques ninguna casilla de "Initialize this repository with..." (ya lo hicimos localmente).
5. Haz clic en **Create repository**.

## Paso 2: Subir tu código

Copia los comandos que aparecen en la sección **"…or push an existing repository from the command line"** y ejecútalos en tu terminal (PowerShell o CMD) dentro de la carpeta del proyecto.

Deberían verse algo así (reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub):

```bash
git remote add origin https://github.com/TU_USUARIO/sistema-inventarios.git
git branch -M main
git push -u origin main
```

_Te pedirá tu usuario y contraseña (o token) de GitHub._

## Paso 3: Activar GitHub Pages

1. Una vez subido, ve a la pestaña **Settings** de tu repositorio en GitHub.
2. En el menú de la izquierda, busca y haz clic en **Pages**.
3. En "Build and deployment" > "Source", selecciona **Deploy from a branch**.
4. En "Branch", selecciona **main** y la carpeta **/(root)**.
5. Haz clic en **Save**.

¡Listo! En unos minutos aparecerá un enlace en esa misma página (ej: `https://tu-usuario.github.io/sistema-inventarios/`) donde podrás ver tu sistema funcionando en vivo.
