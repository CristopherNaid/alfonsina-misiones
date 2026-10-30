# Alfonsina Aliaga S. · Asesora Comercial Misiones

Landing page de atención personal para parques cementerio, paquetes funerarios y salas de velación Misiones (Santa Cruz, Bolivia).

## Estructura

```
alfonsina-misiones/
├── index.html          la página
├── fonts/              tipografías (Figtree y Newsreader)
└── img/
    ├── *.jpg / *.png   fotos que usa la página (recortadas y optimizadas)
    ├── qr_alfonsina.png   QR que abre WhatsApp 70864778 con saludo escrito
    ├── tarjeta_qr.png     tarjeta QR para imprimir (300 dpi)
    └── originales/        imágenes originales sin recortar
```

Para cambiar una foto, reemplace el archivo en `img/` por otro con el mismo nombre.

## Publicar en GitHub Pages

1. Crear un repositorio público, por ejemplo `alfonsina-misiones`.
2. Subir el contenido de la carpeta (`index.html`, `fonts/`, `img/`, `README.md`) con **Add file → Upload files**. Se pueden arrastrar las carpetas completas.
3. Ir a **Settings → Pages → Branch: main / (root) → Save**.
4. La página queda en `https://TU-USUARIO.github.io/alfonsina-misiones/`.

## Cambiar el número de WhatsApp

En `index.html`, buscar `var PHONE = "59170864778";` y reemplazar el número. Usar el código de país sin el signo `+`.
