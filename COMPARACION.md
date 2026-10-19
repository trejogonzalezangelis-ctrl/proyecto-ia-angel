# Comparación de despliegue: GitHub Pages vs Vercel

## 1. Comparación técnica

| Criterio | GitHub Pages | Vercel |
|---|---|---|
| Tipo de hosting | Sitios estáticos | Estáticos + serverless/SSR |
| Despliegue | Desde una rama del repositorio (Drag & Drop o `git push`) | Importando el repo de Git o con la CLI; cada push despliega |
| Configuración inicial | Muy simple: Settings → Pages | Simple: cuenta + importar repositorio |
| URL por defecto | `usuario.github.io/repositorio` | `proyecto.vercel.app` |
| HTTPS | Incluido | Incluido |
| Dominio propio | Sí | Sí |
| Previews por rama / PR | No de forma nativa | Sí, una URL de vista previa por cada rama y PR |
| Backend / funciones | No | Sí (funciones serverless) |
| Variables de entorno | No | Sí |
| Requiere repositorio público (plan gratuito) | Sí | No necesariamente |
| Curva de aprendizaje | Muy baja | Baja |

> Los límites de ancho de banda y los planes cambian con el tiempo; verifícalos en la documentación oficial de cada plataforma antes de decidir.

## 2. Recomendación para este proyecto

El portafolio es 100 % estático (HTML, CSS y JS), por lo que **GitHub Pages es suficiente** y es lo que pide la actividad. **Vercel** sería preferible si más adelante se agrega backend propio, previews por rama o variables de entorno (por ejemplo, ocultar claves de API).

## 3. Métricas de tiempo por nivel de seniority

Estimaciones orientativas para construir este mismo portafolio (HTML/CSS/JS, Matrix, tema Dark/Light, filtros, videos, formulario y despliegue). Son rangos de referencia, no mediciones: varían según la persona y las herramientas.

| Nivel | Maquetación + estilos | JavaScript (Matrix, tema, filtros) | Formulario EmailJS | Despliegue + README | **Total aprox.** |
|---|---|---|---|---|---|
| Junior (0–2 años) | 6–10 h | 5–8 h | 2–3 h | 1–2 h | **14–23 h** |
| Semi-senior (2–5 años) | 3–5 h | 2–4 h | 1 h | 0.5–1 h | **6.5–11 h** |
| Senior (5+ años) | 1.5–3 h | 1–2 h | 0.5 h | 0.5 h | **3.5–6 h** |
| Junior + asistencia de IA | 1.5–3 h | 1–2 h | 1 h | 1 h | **4.5–7 h** |

**Conclusión:** la IA reduce de forma notable el tiempo de un perfil junior, sobre todo en código repetitivo, pero la revisión manual (contraste, accesibilidad y pruebas) sigue siendo necesaria.
