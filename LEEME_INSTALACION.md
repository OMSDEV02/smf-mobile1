# SMF Mobile — Súper Mega Football (PWA instalable)

Esta carpeta contiene la versión **3D WebGL** de SMF Mobile, con cámara lateral, estadio grande, porteros, cuatro clubes, CPU y pausa. Incluye un icono propio, manifiesto de instalación y caché offline.

## Publicar gratis (GitHub Pages)

1. En una computadora, entra en https://github.com y crea una cuenta si aún no tienes (si eres menor, pide ayuda a un adulto).
2. Crea un repositorio **público** nuevo, por ejemplo `smf-mobile`.
3. Sube **todos los archivos de esta carpeta**, manteniendo `index.html`, `manifest.webmanifest`, `sw.js` y la carpeta `icons/` en su estructura.
4. En el repositorio, abre **Settings > Pages**, selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)**, y guarda.
5. Cuando GitHub Pages indique el enlace, abre la dirección HTTPS desde Safari en iPhone/iPad o Chrome en Android. No sirve abrir el archivo `index.html` descargado directamente.

## Instalar en iPhone/iPad

Abre el enlace HTTPS en **Safari** > botón **Compartir** > **Añadir a pantalla de inicio** > **Añadir**. Si aparece la opción "Abrir como app", actívala.

## Instalar en Android

Abre el enlace HTTPS en **Chrome** > menú de tres puntos > **Instalar aplicación** o **Añadir a pantalla principal**. El nombre de la opción depende del dispositivo.

## Notas

- No es una aplicación nativa de App Store ni un APK. Es una **PWA** que se instala desde el navegador, con icono en la pantalla de inicio.
- El modo sin conexión funciona **después de cargar el juego al menos una vez** y de que el navegador complete la caché; WebGL debe estar disponible en el dispositivo.
- Es un prototipo; los gráficos y la IA no son equivalentes a los de FIFA.
- Para publicar una versión nueva, cambia el nombre de `CACHE` en `sw.js` (por ejemplo `smf-mobile-3d-v2`) y vuelve a subir los archivos.
