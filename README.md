# Matriz - Personal GitHub Pages Site

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://jjs001.github.io/matriz/)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.3.4-red)](https://jekyllrb.com/)
[![Quarto Ready](https://img.shields.io/badge/Quarto-Ready-blue)](https://quarto.org/)

Matriz es un sitio web personal construido con Jekyll y GitHub Pages, diseñado para mostrar proyectos, análisis de datos y recursos técnicos. Incluye integración con Quarto para documentación científica y técnica.

## 🚀 Características

- **Jekyll 4.3.4** con tema Minima
- **Quarto integration** para documentos dinámicos
- **GitHub Pages** deployment automático
- **Responsive design** optimizado para móviles
- **SEO optimizado** con jekyll-seo-tag
- **Sitemap automático** para mejor indexación
- **Feed RSS** para suscriptores

## 📁 Estructura del Sitio

```
matriz/
├── index.md                    # Página principal
├── _config.yml                 # Configuración Jekyll
├── Gemfile                     # Dependencias Ruby
├── .github/workflows/          # GitHub Actions
│   └── jekyll-gh-pages.yml    # Workflow de deployment
├── quarto/                     # Sección Quarto
│   ├── _quarto.yml            # Configuración Quarto
│   ├── index.qmd              # Página principal Quarto
│   ├── styles.css             # Estilos personalizados
│   └── examples/              # Ejemplos de documentos
│       ├── data-analysis.qmd
│       ├── visualizations.qmd
│       ├── technical-docs.qmd
│       └── tutorials.qmd
├── demos/                      # Demostraciones
├── repositorios/              # Información de proyectos
└── contacto/                  # Información de contacto
```

## 🛠️ Tecnologías Utilizadas

### Frontend
- **Jekyll 4.3.4** - Generador de sitios estáticos
- **Minima Theme** - Tema responsive y limpio
- **Sass/SCSS** - Preprocesador CSS
- **HTML5 & CSS3** - Marcado y estilos

### Análisis y Documentación
- **Quarto** - Publicación científica y técnica
- **Python** - Análisis de datos (Pandas, Matplotlib, Plotly)
- **R** - Estadísticas y visualizaciones
- **Markdown** - Formato de contenido

### DevOps
- **GitHub Actions** - CI/CD automático
- **GitHub Pages** - Hosting gratuito
- **Bundler** - Gestión de dependencias Ruby

## ⚡ Inicio Rápido

### Prerrequisitos

- Ruby 3.2+
- Bundler
- Git

### Instalación Local

```bash
# Clonar el repositorio
git clone https://github.com/JJS001/matriz.git
cd matriz

# Instalar dependencias
bundle install

# Ejecutar servidor local
bundle exec jekyll serve

# Abrir en navegador
open http://localhost:4000
```

### Desarrollo con Quarto

```bash
# Instalar Quarto (Linux/macOS)
curl -LO https://quarto.org/download/latest/quarto-linux-amd64.deb
sudo dpkg -i quarto-linux-amd64.deb

# Verificar instalación
quarto --version

# Renderizar documentos Quarto
cd quarto
quarto render
```

## 📝 Contenido y Secciones

### 📊 Quarto
Documentos dinámicos con código ejecutable:
- **Análisis de datos** con Python y R
- **Visualizaciones interactivas** con Plotly
- **Documentación técnica** con ejemplos
- **Tutoriales** paso a paso

### 🎯 Demos
Demostraciones interactivas:
- Aplicaciones web
- Visualizaciones de datos
- Proyectos de Machine Learning
- Herramientas y utilidades

### 📚 Repositorios
Colección de proyectos:
- Herramientas de desarrollo
- Bibliotecas y frameworks
- Proyectos personales
- Recursos educativos

### 📧 Contacto
Información de contacto y formulario

## 🚀 Deployment

El sitio se despliega automáticamente en GitHub Pages mediante GitHub Actions:

1. **Push a main** → Trigger del workflow
2. **Build con Jekyll** → Generación del sitio
3. **Deploy a GitHub Pages** → Sitio en vivo

### Configurar GitHub Pages

1. Ve a Settings → Pages en tu repositorio
2. Selecciona "GitHub Actions" como source
3. El workflow se ejecutará automáticamente

## 🎨 Personalización

### Modificar configuración

Edita `_config.yml`:

```yaml
title: Tu Nombre
email: tu@email.com
description: Tu descripción
url: "https://tuusuario.github.io"
baseurl: "/tu-repo"
```

### Personalizar Quarto

Edita `quarto/_quarto.yml`:

```yaml
website:
  title: "Tu Sitio Quarto"
  navbar:
    title: "Tu Nombre"
```

### Estilos personalizados

- **Jekyll**: `assets/main.scss`
- **Quarto**: `quarto/styles.css`

## 📈 SEO y Performance

### Características incluidas
- ✅ Metadatos optimizados
- ✅ Open Graph tags
- ✅ Twitter Cards
- ✅ Sitemap XML
- ✅ Robots.txt
- ✅ Feed RSS
- ✅ Imágenes optimizadas

### Métricas de Performance
- **PageSpeed Score**: 95+
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🔧 Desarrollo

### Comandos útiles

```bash
# Desarrollo local
bundle exec jekyll serve --drafts --livereload

# Build para producción
JEKYLL_ENV=production bundle exec jekyll build

# Renderizar Quarto
quarto render quarto/

# Preview Quarto
quarto preview quarto/
```

### Estructura de archivos

```bash
# Ver estructura
tree -I 'vendor|_site|.git'

# Verificar enlaces
bundle exec htmlproofer ./_site --disable-external

# Validar HTML
html5validator --root _site/
```

## 🤝 Contribuir

1. Fork el repositorio
2. Crea una rama feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit tus cambios (`git commit -am 'Agregar nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

- [Jekyll](https://jekyllrb.com/) - Generador de sitios estáticos
- [Quarto](https://quarto.org/) - Sistema de publicación científica
- [GitHub Pages](https://pages.github.com/) - Hosting gratuito
- [Minima Theme](https://github.com/jekyll/minima) - Tema base

## 📞 Contacto

- **GitHub**: [@JJS001](https://github.com/JJS001)
- **Email**: contacto@matriz.com
- **Website**: [matriz.github.io](https://jjs001.github.io/matriz/)

---

⭐ ¡Dale una estrella si este proyecto te fue útil!