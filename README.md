# Lagus Live · Demo interactiva del MVP

Demo navegable de Lagus Live: App Cliente, App Agente, Panel Web, Vista pública y Recorrido SOS.

## Estructura
- `index.html`: la demo completa en un solo archivo (imágenes y fuentes incluidas).
- `vercel.json`: configuración del sitio estático.

## Publicar en Vercel
1. Sube esta carpeta a un repositorio nuevo en GitHub.
2. En vercel.com → Add New → Project → importa el repositorio.
3. Framework Preset: **Other**. No hay comando de build ni carpeta de salida.
4. Deploy.

Desde la terminal también funciona: `npx vercel --prod` dentro de la carpeta.

## Notas
- Los mapas se cargan desde Esri y requieren conexión a internet.
- Los datos que aparecen son de ejemplo.
- Cada pantalla tiene su propia URL (por ejemplo `/#/panel/p05`), útil para compartir un punto exacto de la demo.
