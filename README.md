# 🌃 Portafolio Profesional Cyberpunk con IA

Portafolio web de **Angel Trejo González** con estética cyberpunk oscura, fondo **Matrix** animado en canvas, modo **Dark/Light** con contraste accesible, stack tecnológico con íconos oficiales, proyectos con filtros dinámicos, videos de YouTube responsivos y formulario de contacto con EmailJS. Generado con ayuda de Inteligencia Artificial y refinado manualmente.

## 🎯 Objetivo

Crear y publicar un portafolio profesional que muestre proyectos de **Web, App y Diseño**, aplicando buenas prácticas de accesibilidad, SEO y rendimiento, con despliegue en GitHub Pages.

## 🛠️ Tecnologías

- **HTML5** semántico y accesible
- **CSS3** (variables, `aspect-ratio`, `prefers-reduced-motion`)
- **Bootstrap 5.3** (grid, navbar, componentes responsivos)
- **JavaScript** vanilla (canvas Matrix, tema, filtros, formulario)
- **EmailJS** para el envío del formulario sin backend
- **Devicon** para los íconos oficiales del stack
- **YouTube (youtube-nocookie)** en iframes responsivos
- **GitHub Pages** y **Vercel** para el despliegue

## ✨ Funcionalidades

| Función | Detalle |
|---|---|
| Fondo Matrix | Canvas fijo, verde suave y translúcido; se pausa si la pestaña no está visible |
| Dark / Light | Toggle con preferencia guardada en `localStorage` |
| Contraste | Colores por variables CSS con contraste alto en ambos temas |
| Filtros | Todos / Web / App / Diseño sin recargar la página |
| Videos | 3 videos destacados en iframes 16:9 (más 9 tarjetas comentadas listas para activar) |
| Contacto | Formulario validado y enviado con EmailJS |

## 📁 Estructura

```
├── index.html        # Todo el sitio (HTML + CSS + JS)
├── README.md
├── LICENSE
└── COMPARACION.md    # GitHub Pages vs Vercel + métricas por seniority
```

## ⚙️ Configurar EmailJS

1. Crea una cuenta gratuita en [emailjs.com](https://www.emailjs.com).
2. Crea un *Email Service* y una *Email Template* con las variables `user_name`, `user_email` y `message`.
3. En `index.html`, busca la sección "Formulario EmailJS" y reemplaza `TU_PUBLIC_KEY`, `TU_SERVICE_ID` y `TU_TEMPLATE_ID`.

## 🚀 Publicar en GitHub Pages (Drag & Drop)

1. En [github.com/new](https://github.com/new) crea un repositorio **público** (por ejemplo `portafolio-cyberpunk`) con licencia MIT.
2. Pulsa **Add file → Upload files** y arrastra `index.html`, `README.md`, `LICENSE` y `COMPARACION.md`.
3. Escribe un mensaje de commit y pulsa **Commit changes**.
4. Ve a **Settings → Pages**, en *Source* elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
5. Espera 1–2 minutos y abre la URL pública.

## 📸 Capturas

> Sube tus capturas a una carpeta `img/` y reemplaza estas líneas.

```md
![Modo oscuro](img/captura-dark.png)
![Modo claro](img/captura-light.png)
![Vista móvil](img/captura-movil.png)
```

## 🔗 Enlaces

- **GitHub:** https://github.com/trejogonzalezangelis-ctrl
- **Repositorio:** `https://github.com/trejogonzalezangelis-ctrl/portafolio-cyberpunk`
- **Sitio público:** `https://trejogonzalezangelis-ctrl.github.io/portafolio-cyberpunk/`
- **Vercel:** https://vercel.com/angel-7d1b
- **YouTube:** https://www.youtube.com/@angel-_-jesustrejogonzales6055

## 📜 Licencia

Distribuido bajo la licencia **MIT**. Consulta el archivo [LICENSE](LICENSE).
