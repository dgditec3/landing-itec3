# Actualización de la home · 17 de septiembre de 2026

## Archivos para subir

Descomprimí el ZIP y subí su contenido a la misma carpeta del repositorio donde ya están `index.html`, `netlify.toml`, `_headers` y `assets/`. No agregues una carpeta contenedora extra.

- Reemplazá `index.html`.
- Incorporá a `assets/` los seis WebP nuevos: `estudiantes-itec3-*`, `ted-auditorio-*` y `comunicacion-institucional-*`.
- Los demás recursos se incluyen para que la carpeta también funcione como copia completa. Conservá cualquier otro archivo que tenga tu repositorio.
- `netlify.toml` y `_headers` se incluyen idénticos a los que compartiste. El proxy `/api/noticias` sigue configurado.

Si Netlify está conectado a ese repositorio y rama, el commit activará el despliegue configurado. Esta entrega prepara los archivos; no realiza un commit ni cambia el sitio publicado.

## Cambios realizados

- Novedades: título **Actualidad** y descripción **Enterate de los acontecimientos, talleres y novedades de nuestro instituto.** Se retiraron «Institucional» y el mensaje permanente «Últimas publicaciones del ITEC 3». Se mantienen los mensajes útiles de carga, ausencia de entradas y error.
- Noticias: imagen destacada y título son enlaces al permalink de cada entrada, igual que «Leer noticia completa». Incluye navegación por teclado y foco visible.
- Contacto: se retiró «Estamos para acompañarte».
- Instituto: se retiraron «Somos parte de tu comunidad» y el pie de la fotografía. Título y párrafos conservados.
- Clubes TED Ed: se retiraron el rótulo de edición y los dos textos pequeños. Se conservan el título, descripción, enlace y «Tu voz. Tus ideas. Nuestra comunidad.». La foto del auditorio lleva un degradado azul superior para dar contraste al texto.
- Nueva carrera: la imagen del equipo con laptop reemplaza el mosaico. Se conserva el enlace a `https://itec3comunicacion.netlify.app/`.
- Inicio: foto original del grupo de estudiantes, con su transparencia y equipo de iluminación, sobre una composición CSS azul y fucsia. Sin alteración de los rostros.

## Verificación

- Revisión en 320, 375, 768, 1024, 1440 y 2560 px, sin desbordamiento horizontal.
- Menú móvil: apertura con Enter y cierre con Escape.
- Tres noticias de prueba en un servidor de desarrollo separado: coincidencia de destinos en foto, título y enlace final; estado vacío tras una carga exitosa. Los datos de prueba no están en los archivos entregados.
- Carga verificada también con las tres entradas reales de WordPress mediante el proxy del servidor de revisión: foto, título y enlace final coinciden en cada noticia.
- Sintaxis de JavaScript, recursos locales, anclas e identificadores revisados.

Para ver la portada sin servidor podés abrir `index.html`; para comprobar el proxy y las noticias usá el despliegue de Netlify.
