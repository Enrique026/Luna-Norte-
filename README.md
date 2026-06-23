# Luna Norte — Sitio Web Oficial

Sitio web de Luna Norte, marca de ropa nacida en Mérida, Yucatán.

**Para quienes avanzan en su propia dirección.**

## Estructura

Un solo archivo `index.html` — todo el CSS, JS y contenido está inline.

## Cómo editar

### Cambiar datos de contacto
Busca en el `<script>` al final del archivo:
```js
const WHATSAPP_NUM  = "529991234567"; // ← Tu número real
const CORREO_TIENDA = "hola@lunanorte.mx"; // ← Tu correo real
```

### Agregar/editar productos
Busca el array `PRODUCTOS[]` en el script y edita los campos de cada objeto.

### Marcar producto agotado
En el producto correspondiente cambia `agotado: false` a `agotado: true`.

### Agregar artículo al journal
Busca el array `ARTICULOS[]` en el script, copia un bloque `{}` y llena los campos.

## Deploy en Netlify

1. Ve a [app.netlify.com/drop](https://app.netlify.com/drop)
2. Arrastra la carpeta completa
3. Listo — URL pública en 30 segundos

O conecta este repositorio de GitHub a Netlify para deploys automáticos al hacer push.

## Tecnología

HTML + CSS + JS vanilla. Sin dependencias externas excepto Google Fonts.

---

© 2026 Luna Norte · Mérida, Yucatán · Todos los derechos reservados.
