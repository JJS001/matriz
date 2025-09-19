# Matriz

Un sitio web moderno construido con Jekyll para mostrar proyectos, demos y recursos técnicos.

## Setup Local

Las siguientes instrucciones son para desarrollo local en tu máquina. Aquí está el proceso exacto paso a paso:

### Prerequisites

Primero, asegúrate de tener instalado en tu máquina local:

- Ruby 3.0+ (verifica con `ruby --version`)
- Git (verifica con `git --version`)

### Proceso de Setup Paso a Paso

1. **Clona el repositorio a tu máquina local:**

```bash
git clone https://github.com/JJS001/matriz.git
cd matriz
```

2. **Instala las dependencias de Ruby:**

```bash
bundle install
```

Esto instala Jekyll y todas las gemas requeridas listadas en el Gemfile.

3. **Inicia el servidor de desarrollo local:**

```bash
bundle exec jekyll serve
```

4. **Ve tu sitio:**
Abre tu navegador y ve a http://localhost:4000

El sitio se reconstruirá automáticamente cuando hagas cambios a los archivos. Usa Ctrl+C para detener el servidor.

### Alternativa: GitHub Codespaces

Si prefieres no configurar localmente, puedes usar GitHub Codespaces:

1. Ve a tu repositorio en GitHub
2. Haz clic en el botón verde "Code"
3. Selecciona la pestaña "Codespaces"
4. Haz clic en "Create codespace on main"

Esto te da un entorno de desarrollo basado en la nube con todo preconfigurado.

### Deployment

El deployment a GitHub Pages ocurre automáticamente cuando pusheas cambios a la rama main - no se requiere configuración local para esa parte.