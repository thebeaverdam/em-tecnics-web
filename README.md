# EM-Tecnics static website

Web estática para EM-Tecnics y The Beaver Dam.

## Estructura

- `index.html`: página principal con dos áreas de negocio.
- `em-tecnics.html`: servicio técnico, reparación y alarmas.
- `the-beaver-dam.html`: hardware, IoT, ESP32, ESPHome y automatización.
- `proyectos.html`: portfolio inicial editable con enlaces a proyectos de GitHub.
- `contacto.html`: contacto directo por teléfono, WhatsApp y email.
- `assets/styles.css`: diseño responsive.
- `assets/main.js`: menú móvil y año del footer.

## Publicación rápida

### Cloudflare Pages

1. Crea un repositorio en GitHub y sube estos archivos.
2. Entra en Cloudflare Pages.
3. Conecta el repositorio.
4. Framework preset: `None`.
5. Build command: dejar vacío.
6. Output directory: `/`.
7. Asocia el dominio `em-tecnics.com`.

### GitHub Pages

1. Sube estos archivos a un repositorio.
2. Ve a Settings > Pages.
3. Source: Deploy from branch.
4. Branch: `main` / root.

## Personalización pendiente recomendada

- Sustituir textos genéricos por casos reales.
- Añadir fotos propias de reparaciones, instalaciones y prototipos.
- Añadir enlaces a GitHub, Play Store o LinkedIn si procede.
- Cambiar el formulario mailto por Netlify Forms o Formspree si quieres recepción directa desde web.
