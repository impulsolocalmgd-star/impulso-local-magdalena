# Impulso Local Magdalena

Página web independiente en HTML, CSS y recursos locales para subir desde Visual Studio Code a un repositorio Git.

## Estructura

```text
impulso-local-git/
├── index.html
├── README.md
└── imagenes/
    ├── imagotipo.jpeg
    ├── portada-facebook.png
    └── slide-4.png
```

## Probarla en tu computadora

Abrí la carpeta en VS Code y hacé doble clic en `index.html`. También podés usar una extensión como Live Server para ver los cambios automáticamente.

## Cambiar el número de WhatsApp

En `index.html`, buscá todas las apariciones de `542224000000` y reemplazalas por el número real, incluyendo código de país y sin espacios, signos ni guiones.

## Cambiar imágenes

Reemplazá los archivos de la carpeta `imagenes/` conservando estos nombres, o modificá las rutas `./imagenes/...` dentro de `index.html`.

## Subir a Git desde VS Code

Abrí la carpeta en VS Code, iniciá un repositorio desde el panel de Control de código fuente, agregá los archivos, escribí un mensaje como `Primera versión del sitio`, hacé commit y después elegí publicar el repositorio en GitHub. Para subirlo manualmente desde una terminal:

```bash
git init
git add .
git commit -m "Primera versión del sitio de Impulso Local"
git branch -M main
git remote add origin URL_DE_TU_REPOSITORIO
git push -u origin main
```

El archivo es estático y no necesita Node.js ni una base de datos. Puede publicarse en GitHub Pages, Netlify, Vercel o cualquier hosting que sirva archivos HTML.
