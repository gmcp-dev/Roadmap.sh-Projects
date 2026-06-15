# 🗺️ Roadmap.sh Projects

Repositorio con proyectos prácticos desarrollados siguiendo las guías de [roadmap.sh](https://roadmap.sh/). Cada proyecto está diseñado para reforzar conceptos fundamentales de desarrollo web frontend.

## Proyectos

### [single-cv-page](./single-cv-page)
Página HTML/CSS estática que muestra un currículum vitae (CV) de una sola página. Contiene información personal, habilidades, educación y experiencia laboral.

🔗 [roadmap.sh/projects/single-page-cv](https://roadmap.sh/projects/single-page-cv)

```bash
# Abrir directamente en el navegador
start ./single-cv-page/index.html
```

### [pricing-comparision-table](./pricing-comparision-table)
Tabla comparativa de planes de precios (Freemium, Pro, Business) construida con HTML semántico.

🔗 [roadmap.sh/projects/pricing-comparison-table](https://roadmap.sh/projects/pricing-comparison-table)

```bash
# Abrir directamente en el navegador
start ./pricing-comparision-table/index.html
```

### [simple-portfolio-website-v1](./simple-portfolio-website-v1)
Portfolio personal de varias páginas con navegación dinámica, secciones de proyectos, artículos y formulario de contacto. Utiliza HTML, CSS y JavaScript vanilla con carga de layouts mediante `fetch()`.

🔗 [roadmap.sh/projects/basic-html-website](https://roadmap.sh/projects/basic-html-website)

> ⚠️ Requiere un servidor HTTP local por usar `fetch()` en los layouts.

```bash
# Opción 1: con Python
cd ./simple-portfolio-website-v1
python -m http.server

# Opción 2: con Node.js
npx serve ./simple-portfolio-website-v1
```

## Requisitos

- Ninguno para los proyectos estáticos (`single-cv-page` y `pricing-comparision-table`).
- Python 3 o Node.js para servir `simple-portfolio-website-v1` localmente.
