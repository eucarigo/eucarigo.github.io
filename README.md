# Eucarigo Portfolio

Portfolio personal de desarrollador web full stack construido con HTML, CSS y JavaScript puro, hospedado en GitHub Pages.

## Características

- **Diseño Moderno**: Interfaz elegante y responsive usando TailwindCSS
- **Blog Dinámico**: Sistema de blog con gestión de contenido fácil
- **Proyectos**: Showcase de proyectos con descripciones detalladas
- **SEO Optimizado**: Meta etiquetas y estructura semántica
- **Rápido y Ligero**: Sin dependencias de frameworks pesados
- **Mobile-First**: Diseño adaptado para todos los dispositivos

## Estructura del Proyecto

```
/
  index.html              # Página principal
  projects.html           # Portfolio de proyectos
  blog.html               # Blog principal
  contact.html            # Formulario de contacto
  blog/
    index.html            # Listado de posts del blog
    post-1.html           # Ejemplo de post individual
  precita/                # Documentación del proyecto PreCita
    index.html
  e.png                   # Logo principal
  e.ico                   # Favicon principal
  precita.png             # Logo del proyecto PreCita
  precita.ico             # Favicon de PreCita
  README.md               # Este archivo
```

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica moderna
- **TailwindCSS**: Framework CSS utilitario (vía CDN)
- **JavaScript Vanilla**: Interactividad sin frameworks
- **Font Awesome**: Iconos y elementos visuales
- **GitHub Pages**: Hosting gratuito

## Configuración Local

### Requisitos

- Git instalado
- Editor de código (VS Code recomendado)
- Navegador web moderno

### Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/eucarigo/eucarigo.github.io.git
   cd eucarigo.github.io
   ```

2. **Iniciar servidor local (opcional)**
   ```bash
   # Usando Python
   python -m http.server 8000
   
   # O usando Node.js
   npx serve .
   
   # O usando VS Code Live Server
   ```

3. **Abrir en navegador**
   ```
   http://localhost:8000
   ```

## Personalización

### Colores y Estilos

Los colores principales están definidos en las clases CSS:
- **Púrpura principal**: `#667eea`
- **Púrpila secundario**: `#764ba2`
- **Gradiente**: Linear de 135deg entre ambos colores

Para cambiar colores, busca las clases `.gradient-text` y `.hero-gradient` en los archivos HTML.

### Información Personal

Edita los siguientes elementos en `index.html`:

1. **Nombre y título**: Hero section
2. **Descripción**: Biografía personal
3. **Proyectos**: Cards de proyectos
4. **Contacto**: Email y redes sociales

### Añadir Nuevos Proyectos

Para añadir un nuevo proyecto a la página principal:

1. **Duplica una card de proyecto existente**
2. **Actualiza la información**:
   - Título del proyecto
   - Descripción
   - Tecnologías usadas
   - Enlaces (demo/código)
3. **Añade iconos** apropiados usando Font Awesome

## SEO y Meta Datos

Cada página incluye meta etiquetas optimizadas:

```html
<meta name="description" content="Descripción de la página">
<meta name="keywords" content="palabras, clave, separadas, por, comas">
<meta name="author" content="Eucarigo">
```

### Open Graph para Redes Sociales

Las páginas incluyen etiquetas Open Graph para mejor compartición:

```html
<meta property="og:title" content="Título">
<meta property="og:description" content="Descripción">
<meta property="og:image" content="URL de imagen">
```

## Despliegue en GitHub Pages

### Configuración Automática

1. **Ve a tu repositorio en GitHub**
2. **Settings > Pages**
3. **Source**: Selecciona "Deploy from a branch"
4. **Branch**: `main` y `/ (root)`
5. **Save**

El sitio se desplegará automáticamente en: `https://username.github.io`

### Dominio Personalizado

Para usar un dominio personalizado:

1. **Crea archivo `CNAME`** en la raíz:
   ```
   tudominio.com
   ```

2. **Configura DNS** en tu proveedor de dominio:
   - Registro A: `185.199.108.153`
   - Registro A: `185.199.109.153`
   - Registro A: `185.199.110.153`
   - Registro A: `185.199.111.153`
   - Registro CNAME: `www` a `username.github.io`

## Rendimiento y Optimización

### Imágenes

- Usa formatos modernos (WebP, AVIF)
- Comprime imágenes antes de subirlas
- Atributos `alt` descriptivos para SEO

### JavaScript

- Código vanilla para mejor rendimiento
- Lazy loading de imágenes si es necesario
- Minificación para producción

### CSS

- TailwindCSS via CDN (optimizado)
- Classes utilitarias para mantenibilidad
- CSS crítico inline para mejor carga

## Mantenimiento

### Actualizaciones Regulares

1. **Contenido**: Añade nuevos posts y proyectos
2. **Dependencias**: Verifica versiones de CDN
3. **SEO**: Revisa meta etiquetas periódicamente
4. **Enlaces**: Verifica que todos funcionen

### Backup

- GitHub mantiene el historial completo
- Considera backup local de contenido importante
- Exporta posts si usas CMS externo

## Contribuciones

Las contribuciones son bienvenidas:

1. **Fork** el repositorio
2. **Crea una rama** para tu feature
3. **Commit** tus cambios
4. **Push** a la rama
5. **Crea Pull Request**

## Licencia

Este proyecto está bajo la Licencia MIT.

## Contacto

- **Email**: info@eucarigo.com / contact@eucarigo.com
- **GitHub**: https://github.com/eucarigo
- **Web**: https://eucarigo.com

---

## Guía Rápida de Publicación

### Nuevo Post en el Blog

1. **Usa `blog-generator.html`**
2. **Genera HTML del post**
3. **Crea archivo `blog/nuevo-post.html`**
4. **Actualiza `blog/index.html`**
5. **Push a GitHub**

### Nuevo Proyecto

1. **Edita `index.html`**
2. **Añade nueva card en sección proyectos**
3. **Crea subpágina si es necesario**
4. **Actualiza enlaces**
5. **Push a GitHub**

### Actualización General

1. **Haz cambios locales**
2. **Commit con mensaje descriptivo**
3. **Push a GitHub**
4. **Verifica despliegue automático**
