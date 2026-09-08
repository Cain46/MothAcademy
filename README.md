# Moth Academy · QA Study & Practice

**Aprender · Practicar · Evolucionar**

Web estática de estudio y repaso. Sin login, sin backend, sin notas.

## Paleta oficial V1
- Deep Navy `#06111A`
- Surface Navy `#0B2136`
- Secondary Navy `#102B45`
- Moth Gold `#D5A641`
- Light Gold `#F0D38A`
- Ivory `#F5F1E8`
- Muted Steel `#A7B2BF`
- Success `#49C584`

## Cómo probarla localmente
Desde esta carpeta:

```bash
python -m http.server 8080
```

Abrí `http://localhost:8080`.

## Publicar en GitHub Pages
Esta versión no requiere build.

1. Crear un repositorio, por ejemplo `moth-academy`.
2. Subir el contenido de esta carpeta a `main`.
3. En GitHub: **Settings → Pages**.
4. Elegir **Deploy from a branch**.
5. Branch `main`, carpeta `/ (root)`.
6. Guardar.

GitHub publicará el sitio en una URL del tipo `https://usuario.github.io/moth-academy/`.

## Progreso
El progreso y las respuestas se guardan en `localStorage`. El usuario puede exportarlas e importarlas como archivo JSON.


## Abrir directamente en Windows
Esta versión incluye `bundle.js` y puede abrirse haciendo doble clic en `index.html` (`file://`) sin servidor local. También sigue siendo compatible con GitHub Pages.
