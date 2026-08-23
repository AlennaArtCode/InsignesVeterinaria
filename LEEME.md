# Se borró el repo: esto es todo, de cero

Sube el contenido completo de esta carpeta al repositorio (rama `main`),
respetando la estructura de carpetas tal cual está aquí.

## Estructura

    wrangler.jsonc                 en la raíz del repo, junto a sitio/
    sitio/index.html                página principal (la tarjeta negra que se mueve)
    sitio/anuncio.html              misma página, para pauta / enlaces de campaña
    sitio/ejemplo.html              tarjeta de muestra
    sitio/huellas.html              tarjeta del Dr. Meza
    sitio/insignes.vcf              tu contacto
    sitio/ejemplo.vcf               contacto de la tarjeta de muestra
    sitio/huellas.vcf               contacto del Dr. Meza
    sitio/logo-huellas.png          logo de Huellas
    sitio/social.png                imagen para compartir el sitio principal
    sitio/favicon.svg
    sitio/404.html
    sitio/_headers                  caché de las fuentes (un año)
    sitio/fonts/                    las 5 fuentes (cinzel, garamond ×2, sans ×2)

## Antes de subir: tu número de WhatsApp

En `anuncio.html`, `ejemplo.html`, `ejemplo.vcf` e `insignes.vcf` aparece el
texto `57TUNUMERO` (siete veces en total). Reemplázalo por 57 + tu celular sin
espacios (ej. `573001234567`) antes de subir, o el anuncio y la tarjeta de
muestra no van a servir.

## Cómo subirlo

1. github.com/AlennaArtCode/InsignesVeterinaria.
2. Add file → Upload files, y arrastra TODO el contenido de esta carpeta
   (incluida la carpeta `sitio` completa y `wrangler.jsonc` suelto en la raíz).
   GitHub conserva la estructura de subcarpetas al arrastrar.
3. Commit changes.

## Por qué falló el build antes

El proyecto de Cloudflare corre `npx wrangler deploy`, que necesita
`wrangler.jsonc` en la raíz para saber qué carpeta publicar. Sin él, wrangler
no encuentra archivos estáticos y el build muere en «Deploying». Este archivo
ya apunta a `./sitio/`.

Si el proyecto en Cloudflare no se llama `paginaprueba`, abre `wrangler.jsonc`
y cambia el valor de `"name"` por el nombre real del proyecto.

## Después de publicar

1. Abre `https://tudominio/huellas` en el celular y prueba cada botón.
2. Entra al panel, escribe el dominio arriba, y usa «código QR» en la tarjeta.

## Lo que aún falta del Dr. Meza

- Instagram y TikTok (hoy la tarjeta no muestra la fila de redes).
- Enlace directo de su página de Facebook.
- Confirmar el fijo: la tarjeta marca +57 602 7321768.
