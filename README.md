# patriciaperis.com

Portfolio de Patricia Peris: diseño editorial, dirección de arte, tipografía y audiovisual.

Proyectos: *The Liaison* Issue 1, Connect by Chanel x AnOther, Edición Limitada y Zaha.

## Estructura

```
index.html      la web completa (HTML, CSS y JS en un solo archivo)
img/            imágenes, vídeos y CV
fonts/          Instrument Sans e Instrument Serif (woff2)
vercel.json     cabeceras de caché para Vercel
```

Es una web estática: no necesita instalar nada ni compilar.

## Ver en local

Abre `index.html` en el navegador, o sirve la carpeta:

```
npx serve .
```

## Publicar en Vercel

1. En vercel.com → **Add New… → Project** e importa este repositorio.
2. Framework Preset: **Other**. Build Command: vacío. Output Directory: `.` (raíz).
3. **Deploy**.
4. Dominio: en el proyecto → **Settings → Domains** → añade `patriciaperis.com` y `www.patriciaperis.com`, y copia los registros DNS que te indique Vercel en el panel de tu proveedor de dominio (IONOS).

Cada `git push` a la rama `main` vuelve a publicar la web automáticamente.

## Notas

- La animación 3D de Zaha carga three.js desde cdnjs al llegar a esa sección.
- La tipografía Zaha va incrustada dentro de `index.html`.
