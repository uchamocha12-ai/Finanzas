MIS CUENTAS — PWA PARA IPHONE

ARCHIVOS
- index.html: aplicación completa.
- manifest.webmanifest: configuración para instalarla como app.
- sw.js: funcionamiento sin conexión después de la primera carga.
- icons/: iconos para iPhone/PWA.

PARA PROBAR EN UN PC
1. No abras index.html directamente con doble clic si quieres probar el modo PWA/offline.
2. Sirve la carpeta con un servidor web local o súbela a un alojamiento HTTPS.
3. El control de cuentas, pagos y comprobantes funciona en navegadores modernos.

PARA INSTALAR EN IPHONE
1. Sube esta carpeta a un hosting HTTPS (GitHub Pages, Netlify, Cloudflare Pages, etc.).
2. Abre la dirección en Safari.
3. Toca Compartir.
4. Selecciona "Agregar a pantalla de inicio".
5. Abre "Mis Cuentas" desde el nuevo icono.

PRIVACIDAD
Los datos se almacenan localmente en IndexedDB en el dispositivo. Esta versión no usa servidor ni nube.
Usa Ajustes > Exportar respaldo de forma periódica y guarda el archivo en iCloud Drive.

FUNCIONES INCLUIDAS
- Dashboard mensual.
- Cuentas recurrentes y de una sola vez.
- Estados: pendiente, pago parcial, pagada y vencida.
- Múltiples pagos parciales por cuenta.
- Foto o PDF como comprobante.
- Historial por mes.
- Buscador y filtros.
- Estadísticas por categoría y medio de pago.
- Respaldo e importación JSON, incluyendo comprobantes.
- Uso sin conexión tras la instalación.
