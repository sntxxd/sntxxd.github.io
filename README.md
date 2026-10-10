# Santiago Alonso — SYNTX / sntxxd

Sitio estático minimalista para GitHub Pages, en español, con tema oscuro, portafolio de proyectos, certificados y metadatos SEO.

## Publicar en GitHub Pages
1. Crea un repositorio llamado `sntxxd.github.io` (si tu usuario de GitHub es `sntxxd`) o usa cualquier repositorio público.
2. Sube el contenido de esta carpeta a la raíz del repositorio.
3. En **Settings → Pages**, selecciona **Deploy from a branch**, elige `main` y la carpeta `/ (root)`.
4. Espera a que termine el despliegue y abre la URL que GitHub Pages te indique.

## Antes de publicar
- Confirma que `https://github.com/sntxxd` sea tu perfil correcto; si no, cambia los enlaces en `index.html` y `llms.txt`.
- Si tienes una URL personalizada, añade `canonical`, `og:url` y un `sitemap.xml` con esa URL real.
- Añade enlaces de contacto/redes que quieras hacer públicos.
- Actualiza los datos y fechas conforme avances. No publiques información privada.

## SEO incluido
- Título, descripción, idioma, robots, Open Graph y Twitter Card.
- Datos estructurados JSON-LD `Person`.
- `robots.txt` y `llms.txt`.
- Encabezados semánticos, contenido de texto rastreable, enlaces a certificados y diseño responsive.

El SEO ayuda a los buscadores a entender el sitio, pero no garantiza aparecer inmediatamente ni que una IA cite la página. Tras publicar, registra el dominio en Google Search Console y envía el sitemap cuando tengas una URL definitiva.


## SEO: publicar y solicitar indexación

Este sitio incluye `robots.txt`, `sitemap.xml`, `llms.txt`, una URL canónica y datos estructurados `Person`. Después de subir los archivos a la raíz del repositorio `sntxxd.github.io`:

1. Comprueba que `https://sntxxd.github.io/robots.txt` y `https://sntxxd.github.io/sitemap.xml` abran correctamente.
2. Añade `https://sntxxd.github.io/` como propiedad de prefijo de URL en Google Search Console y completa la verificación.
3. En Search Console, abre **Sitemaps** y envía `sitemap.xml`.
4. En **Inspección de URLs**, inspecciona `https://sntxxd.github.io/` y solicita indexación si Google puede acceder a la página.
5. Revisa el informe de indexación posteriormente. La indexación puede tardar y no está garantizada.

No añadas perfiles sociales a `sameAs` a menos que sean perfiles públicos tuyos. Mantén el nombre, alias y enlaces coherentes en tus perfiles reales.
