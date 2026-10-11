# Portfolio

Web estática (HTML + CSS). No necesita instalar nada.

## Estructura

```
portfolio/
├── index.html
├── style.css
└── img/          (crea esta carpeta para tus imágenes)
```

## Personalizar

1. En `index.html` cambia "Tu Nombre", el email, los textos y los proyectos.
2. Pon tus imágenes en `img/` y sustituye el texto "Imagen 1" por
   `<img src="img/proyecto1.jpg" alt="Descripción">` dentro de cada `.thumb`.

## Subir a GitHub

1. Crea un repositorio nuevo en github.com (por ejemplo `portfolio`).
2. Pulsa "Add file → Upload files" y arrastra el CONTENIDO de la carpeta
   (index.html, style.css, img/), no la carpeta en sí.
3. Pulsa "Commit changes".

## Publicar

**Opción A: GitHub Pages**
Settings → Pages → Branch `main` / carpeta `/ (root)` → Save.
URL: `https://tuusuario.github.io/portfolio`

**Opción B: Cloudflare Pages**
Workers & Pages → Create → Pages → Connect to Git → elige el repositorio.
Build command: vacío. Output directory: `/`. Deploy.
Permite añadir un dominio propio.
