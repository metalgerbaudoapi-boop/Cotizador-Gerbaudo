# Cotizador – Metalúrgica Gerbaudo (app para el celular)

Cáscara de aplicación (PWA) para abrir el Cotizador desde la pantalla de inicio del celular.

- **No contiene datos**: ni clientes, ni precios, ni el link del Cotizador.
- La primera vez pide el link del Cotizador (el de "Cualquier usuario") y lo guarda **solo en ese celular**.
- El acceso está protegido por la contraseña y el registro de dispositivo del propio Cotizador.

Archivos: `index.html` (pantalla de inicio + Cotizador a pantalla completa), `manifest.webmanifest`, `sw.js` (guarda solo esta cáscara), `icons/`.

Para volver a configurar el link: abrir la app agregando `?config` al final de la dirección, o usar "Cambiar el link" si no carga.
