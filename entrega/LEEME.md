# Qué subir al repositorio

Cloudflare ya está enlazado con GitHub: basta con subir estos archivos a la
carpeta **`sitio/`** de la rama `main` (la misma donde está `index.html`).

## Listo para subir hoy

    sitio/huellas.html            la tarjeta del Dr. Meza
    sitio/huellas.vcf             el contacto que se guarda en el celular
    sitio/logo-huellas.png        el logo de la tarjeta
    sitio/_headers                caché de las fuentes (un año)
    sitio/fonts/sans.woff2        \ solo si no están ya en el repo;
    sitio/fonts/sans-medium.woff2 / si ya están, no las repitas

No hay `index.html` ni `favicon.svg` a propósito: los del repositorio ya
están bien y no se deben reemplazar.

## Esperando tu número de WhatsApp

    sitio/anuncio.html            el anuncio (3 enlaces por llenar)
    sitio/ejemplo.html            tarjeta de muestra (2 enlaces por llenar)
    sitio/ejemplo.vcf             contacto de la muestra (1)
    sitio/insignes.vcf            tu contacto (1)

En esos cuatro archivos aparece el texto `57TUNUMERO`. Reemplázalo por 57 y los
diez dígitos de tu celular, sin espacios ni signos (por ejemplo `573001234567`).
Son siete apariciones en total; búscalas con Ctrl+F. Hasta entonces, esos
archivos no sirven publicados.

La tarjeta de muestra usa el nombre de una doctora inventada, pero sus botones
llevan a tu WhatsApp: quien la toque te escribe a ti, y no se marca el número
de un desconocido.

## Cómo subirlo

1. Entra a github.com/AlennaArtCode/InsignesVeterinaria, carpeta `sitio`.
2. Add file → Upload files → arrastra los archivos.
   La carpeta `fonts` se arrastra completa si hace falta.
3. Commit changes. Cloudflare compila en un minuto.

## Después de publicar

1. Abre `https://insignes.co/huellas` en el celular.
2. Prueba uno por uno: urgencias, WhatsApp, celular, consultorio, correo,
   ubicación, guardar contacto y compartir.
3. Con el enlace vivo, entra al panel, escribe el dominio arriba y usa el botón
   «código QR» de la tarjeta. El SVG es el que va a imprenta.

## Lo que aún falta del Dr. Meza

- Instagram y TikTok (hoy la tarjeta no muestra la fila de redes).
- Enlace directo de su página de Facebook.
- Confirmar el fijo: la tarjeta marca +57 602 7321768.

Cuando lleguen, se editan en el panel, se descarga otra vez `huellas.html` y se
sube encima. El código QR no cambia: apunta a la dirección, no al contenido.
