# Proyectil gastronomía — sitio web

Landing page de una sola página (Inicio · Nosotros/Método · Servicios · Contacto), hecha con Hugo y publicada en GitHub Pages.

## Dónde se edita cada cosa (sin tocar código)

| Qué querés cambiar | Archivo |
|---|---|
| Todos los textos (títulos, método, servicios, capacitaciones, contacto) | `content/_index.md` |
| WhatsApp, email, Instagram | `hugo.toml` |
| Colores y tipografías de marca | `assets/css/main.css` (bloque de arriba, `:root`) |
| Logo e imágenes | carpeta `static/img/` |

Se puede editar directo desde la web de GitHub: abrís el archivo, tocás el lápiz ✏️, cambiás el texto y hacés **Commit changes**. A los 1–2 minutos el sitio se actualiza solo.

> Ojo en `content/_index.md`: respetá las comillas y los espacios al principio de cada línea.

## Publicar por primera vez en GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo `proyectil-web`).
2. Subí todo el contenido de esta carpeta (botón **Add file → Upload files**, arrastrando los archivos y carpetas, incluida `.github`).
3. En el repo: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
4. Andá a la pestaña **Actions** y esperá que termine "Publicar sitio" (tilde verde).
5. El sitio queda en `https://TU-USUARIO.github.io/proyectil-web/`.

## Dominio propio (más adelante)

En **Settings → Pages → Custom domain** cargás el dominio (ej. `proyectil.com.ar`) y configurás el DNS como indica GitHub.

## Ver el sitio en tu computadora (opcional)

Con Hugo instalado: `hugo server` y abrís `http://localhost:1313`.
