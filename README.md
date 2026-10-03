# R360 GB Android

Aplicación Android móvil para el Campus Virtual GB Capacitación.

- Nombre: R360 GB
- Package ID: `cl.gbcapacitacion.r360`
- URL inicial: `https://aulagb.cl/`
- minSdk: 23
- targetSdk / compileSdk: 36
- Versión: 1.0.0 (versionCode 1)

## Funciones
- Inicio de sesión y navegación de Moodle/R360 mediante WebView.
- Cookies/sesión persistentes durante el uso.
- JavaScript y DOM Storage.
- Selector de archivos para formularios.
- Descargas mediante DownloadManager.
- Enlaces externos se abren en la app correspondiente.
- Botón Atrás navega por el historial web.

## Build
GitHub Actions genera un AAB release sin firmar. El AAB final para Google Play se firma fuera del repositorio con la clave de carga del proyecto.
