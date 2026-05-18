# Mis Vehiculos

Aplicacion web instalable para gestionar documentacion y mantenimiento de vehiculos.

## Probar en local

Abre esta carpeta con un servidor web local y entra en `index.html`.

Ejemplo:

```bash
python3 -m http.server 4173
```

Despues abre `http://127.0.0.1:4173/`.

## Subir a GitHub

1. Crea un repositorio nuevo en GitHub.
2. Sube los archivos de esta carpeta:
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
   - `icon.svg`
   - `netlify.toml`
   - `README.md`
3. No hace falta configurar ningun build.

## Desplegar en Netlify

Opcion recomendada:

1. Entra en Netlify.
2. Elige `Add new site` > `Import an existing project`.
3. Conecta tu repositorio de GitHub.
4. En configuracion de despliegue:
   - Build command: deja vacio.
   - Publish directory: `.`
5. Publica el sitio.

## Instalar en el movil

Publica la carpeta en un hosting con HTTPS. Despues:

- iPhone: abre la URL en Safari, comparte y pulsa `Anadir a pantalla de inicio`.
- Android: abre la URL en Chrome y pulsa `Instalar app` o `Anadir a pantalla principal`.

Los datos se guardan en el navegador del dispositivo con `localStorage`.
