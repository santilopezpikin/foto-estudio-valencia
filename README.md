# Foto Estudio Valencia

Página web y asistente de chat de **Foto Estudio Valencia**, estudio fotográfico profesional en Tlalnepantla de Baz desde 1967.

## Contenido

| Archivo o carpeta | Qué es |
| --- | --- |
| `index.html` | La página completa: secciones, lista de precios y asistente de chat. |
| `img/` | Logo del estudio (SVG), fotos de título y diploma, collage de medidas, álbum, portadas de video, imagen para compartir y favicon. |
| `video/` | Video de introducción y video de fotografía análoga, comprimidos para web. |

## Publicar con GitHub Pages

1. El repositorio debe ser **público** (en el plan gratuito, GitHub Pages solo funciona con repositorios públicos).
2. En **Settings → Pages**, elige *Deploy from a branch*, rama `main` y carpeta `/ (root)`.
3. La dirección queda como `https://<usuario>.github.io/foto-estudio-valencia/`.
4. Ya publicada, en `index.html` cambia `img/og-valencia.jpg` (etiqueta `og:image` y datos para Google) por la dirección completa, por ejemplo `https://<usuario>.github.io/foto-estudio-valencia/img/og-valencia.jpg`.

## Cambiar precios, horario o contacto

Todo está en el objeto `NEGOCIO`, al inicio del `<script>` de `index.html`. Al cambiar un dato ahí se actualiza en la lista de precios y en el asistente de chat. Si cambian teléfono u horario, actualízalos también en los datos para Google (`application/ld+json`, dentro de `<head>`).

## Cambiar fotos o videos

Sube el archivo nuevo a `img/` o `video/` con el mismo nombre, o cambia la ruta en `index.html`.
