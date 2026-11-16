# Mis Finanzas

App personal para controlar gastos, ingresos, ahorro mensual y vencimientos (seguros, ITV, impuestos…).
Se actualiza arrastrando extractos bancarios y documentos: Excel, CSV, PDF y PowerPoint.

## Privacidad

- Este repositorio solo contiene el programa. No hay ningún dato personal aquí.
- Los archivos que importas se leen en tu navegador y no se suben a ningún servidor.
- De cada movimiento solo se guardan la fecha, el concepto y el importe. Los IBAN, tarjetas, DNI/NIE y teléfonos que aparezcan en el concepto se borran.
- La sincronización opcional guarda una copia **cifrada con tu contraseña** (AES-256-GCM, clave derivada con PBKDF2) en la carpeta oculta de la app en tu Google Drive (`appDataFolder`), a la que solo esta app tiene acceso.

## Archivos

- `index.html`: la app completa.
- `manifest.webmanifest` e iconos: para instalarla en el móvil con «Añadir a pantalla de inicio».
