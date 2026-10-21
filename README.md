# Hans Imports — demo web

Página estática basada en el diseño original proporcionado en `stitch_hans_design_system_generator.zip`.

## Archivos

- `index.html`: página e interacciones del formulario.
- `DESIGN.md`: sistema de diseño de referencia.
- `preview.png`: captura de la versión local.
- `vercel.json`: configuración de publicación estática.

## Desarrollo local

Con Python instalado, desde la raíz del repositorio:

```sh
python -m http.server 3000 --bind 127.0.0.1 --directory .
```

Abre http://localhost:3000.

## Publicación en Vercel

Importa este repositorio en Vercel. No requiere instalar dependencias, ejecutar una compilación ni configurar variables de entorno. `vercel.json` selecciona la raíz como directorio de salida. `.vercelignore` excluye los documentos y la captura de la publicación.

## Funcionamiento

El diseño utiliza Tailwind CDN, Google Fonts, imágenes externas y Google Maps, por lo que esos recursos requieren conexión a Internet. El formulario prepara solicitudes mediante enlaces a SMS o WhatsApp; no incluye un backend ni una base de datos.

Se conservaron los datos del diseño original: teléfono público (714) 536-4000 y número de solicitudes +1 (949) 698-8943. Los años duplicados del archivo exportado se eliminaron y se generan al cargar la página.

Este sitio es una demostración independiente y conserva el aviso del diseño original de que no es el sitio oficial de Hans Imports.
