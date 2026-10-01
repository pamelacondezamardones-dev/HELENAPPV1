HelenAPP Mi Voz — versión PWA

Publica TODOS estos archivos manteniendo la estructura de carpetas en un servidor HTTPS.
El archivo principal debe ser index.html.

Android (Chrome/Edge): abre la URL HTTPS y usa el botón “Instalar app” o el menú del navegador → Instalar aplicación.
iPhone/iPad (Safari): abre la URL HTTPS → Compartir → Añadir a pantalla de inicio.

No abras index.html directamente como archivo local (file://), porque el Service Worker y la instalación PWA requieren un origen web seguro (HTTPS; localhost sirve para desarrollo).
