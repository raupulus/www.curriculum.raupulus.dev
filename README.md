# 📄 Curriculum Vitae — Raúl Caro Pastorino (@raupulus)

Sitio web estático con el Curriculum Vitae profesional de **Raúl Caro Pastorino** ([@raupulus](https://raupulus.dev)), Desarrollador Full Stack especializado en Backend con Laravel.

🌐 **Web en producción:** [curriculum.raupulus.dev](https://curriculum.raupulus.dev)

## 🧑‍💻 Sobre el proyecto

Este repositorio contiene el código fuente y los assets distribuibles del CV online de Raúl Caro Pastorino. Se trata de una página web estática, moderna y responsive que presenta la información profesional en un diseño editorial de alta calidad.

### Características

- **HTML estático** — Una sola página (`dist/index.html`) lista para servir desde cualquier hosting estático.
- **Tailwind CSS v4** — Estilos generados con Tailwind CSS usando su CLI, con un sistema de diseño personalizado basado en Material Design 3 (colores, tipografías, superficies).
- **Diseño editorial** — Tipografía dual (Inter + Noto Serif), paleta Deep Navy/Off-White, sin bordes duros, con jerarquía visual mediante superficies tonales y sombras ambientales.
- **Responsive** — Diseño adaptable a móvil, tablet y escritorio con navegación lateral flotante en pantallas grandes.
- **Google Fonts & Material Symbols** — Iconografía y fuentes cargadas desde CDN.
- **Google Analytics** — Integración con Google Tag Manager para seguimiento de visitas.
- **Descarga de CV en PDF** — Botón para descargar el CV en formato PDF directamente desde la web.

### Secciones del CV

- **Perfil** — Foto, nombre, cargo, descripción profesional y datos de contacto.
- **Experiencia** — Historial laboral con timeline visual.
- **Educación** — Formación académica y cursos.
- **Habilidades** — Stack tecnológico (Laravel, PHP, PostgreSQL, JavaScript, Vue, Python, Git, Linux, etc.).
- **Otros conocimientos** — Formaciones complementarias (Docker, Node.js, Ionic, Agile/Scrum, etc.).
- **Contacto** — Email, LinkedIn, GitHub y web personal.

## 📁 Estructura del proyecto

```
├── dist/                  # ← Archivos distribuibles (web estática lista para deploy)
│   ├── index.html         #    Página principal del CV
│   ├── cv_pdf.pdf         #    CV en formato PDF descargable
│   ├── css/
│   │   └── styles.css     #    CSS compilado y minificado (Tailwind)
│   └── images/
│       ├── logo.png       #    Foto de perfil
│       └── qr.png         #    Código QR del CV online
├── src/
│   └── input.css          # ← CSS fuente con imports de Tailwind y tema personalizado
├── template/              # ← Plantilla de diseño y referencia (no se sube a git)
│   ├── code.html
│   ├── DESIGN.md
│   └── screen.png
├── package.json           # ← Configuración npm con scripts de build
├── .gitignore
└── README.md
```

## 🚀 Despliegue y generación de assets

### Requisitos previos

- [Node.js](https://nodejs.org/) (v18 o superior recomendado)
- npm (incluido con Node.js)

### Instalación de dependencias

```bash
npm install
```

### Generar CSS para producción (minificado)

```bash
npm run build
```

Este comando ejecuta el CLI de Tailwind CSS, procesa `src/input.css` y genera el archivo de estilos optimizado y minificado en `dist/css/styles.css`.

### Modo desarrollo (watch)

```bash
npm run watch
```

Recompila automáticamente los estilos CSS cada vez que se detectan cambios en los archivos fuente.

### Despliegue

El contenido del directorio **`dist/`** es la web estática lista para servir. Puedes desplegarla en cualquier servicio de hosting estático:

- **GitHub Pages** — Sirve directamente el directorio `dist/`.
- **GitLab Pages** — Configura el CI/CD para publicar `dist/`.
- **Nginx / Apache** — Apunta el `root` del virtualhost al directorio `dist/`.
- **Netlify / Vercel / Cloudflare Pages** — Sube el directorio `dist/` como carpeta de publicación.

## 🔗 Repositorios

| Plataforma | URL |
|---|---|
| **GitHub** | [github.com/raupulus/www.curriculum.raupulus.dev](https://github.com/raupulus/www.curriculum.raupulus.dev) |
| **GitLab** | [gitlab.com/raupulus/www.curriculum.raupulus.dev](https://gitlab.com/raupulus/www.curriculum.raupulus.dev) |

## 🛠 Stack tecnológico

- HTML5
- [Tailwind CSS v4](https://tailwindcss.com/) (con `@tailwindcss/cli`)
- [Google Fonts](https://fonts.google.com/) (Inter, Noto Serif)
- [Material Symbols](https://fonts.google.com/icons)

## 👤 Autor

**Raúl Caro Pastorino** — [@raupulus](https://raupulus.dev)

- 🌐 Web: [raupulus.dev](https://raupulus.dev)
- 📧 Email: [public@raupulus.dev](mailto:public@raupulus.dev)
- 💼 LinkedIn: [linkedin.com/in/raulcaropastorino](https://www.linkedin.com/in/raulcaropastorino/)
- 🐙 GitHub: [github.com/raupulus](https://github.com/raupulus)

## 📜 Licencia

Este proyecto es de uso personal. Todos los derechos reservados © Raúl Caro Pastorino.