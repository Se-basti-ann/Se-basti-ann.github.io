# 🚀 Portfolio Sebastian Rodriguez

Portafolio web moderno y minimalista con diseño cyberpunk/tech.

## ✨ Características

- ⚡ Diseño moderno con animaciones fluidas
- 📱 Completamente responsive
- 🎨 Paleta de colores tech (verde neón + azul)
- 🔥 Efectos visuales y micro-interacciones
- 📊 Sección de proyectos con enlaces a GitHub
- 🛠️ Stack tecnológico visible
- 📧 Sección de contacto con redes sociales

## 🚀 Deploy Rápido en GitHub Pages

### Opción 1: Usando este repositorio (Recomendado - 2 minutos)

1. **Crea un nuevo repositorio en GitHub:**
   - Ve a https://github.com/new
   - Nombre: `Se-basti-ann.github.io` (importante: debe ser exactamente tu usuario + .github.io)
   - Público
   - NO inicialices con README

2. **Sube el archivo:**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/Se-basti-ann/Se-basti-ann.github.io.git
   git push -u origin main
   ```

3. **Activa GitHub Pages:**
   - Ve a Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` / `root`
   - Save

4. **¡Listo!** Tu portafolio estará en: `https://Se-basti-ann.github.io`

### Opción 2: Usando un repositorio existente

1. Crea un nuevo repo (puede tener cualquier nombre, ej: `portfolio`)
2. Sube el `index.html`
3. Ve a Settings → Pages
4. Selecciona la rama y carpeta
5. Tu sitio estará en: `https://Se-basti-ann.github.io/portfolio`

## 📝 Personalización

### Actualizar proyectos

Edita las tarjetas de proyecto en el HTML (busca `<!-- Project 1 -->`, etc.):

```html
<div class="project-card">
    <span class="project-number">01</span>
    <h3 class="project-title">TU PROYECTO</h3>
    <p class="project-description">Descripción del proyecto...</p>
    <div class="project-tech">
        <span class="tech-tag">Tech1</span>
        <span class="tech-tag">Tech2</span>
    </div>
    <div class="project-links">
        <a href="URL_GITHUB" class="project-link">GitHub →</a>
        <a href="URL_DEMO" class="project-link">Demo →</a>
    </div>
</div>
```

### Cambiar colores

En la sección `:root` del CSS:

```css
:root {
    --primary: #00ff88;    /* Verde neón */
    --secondary: #0066ff;  /* Azul */
    --accent: #ff3366;     /* Rosa/Rojo */
    --dark: #0a0a0a;       /* Fondo oscuro */
}
```

### Agregar más skills

En la sección `<section class="skills">`, añade categorías o items:

```html
<div class="skill-category">
    <h3>Nueva Categoría</h3>
    <ul class="skill-list">
        <li>Skill 1</li>
        <li>Skill 2</li>
    </ul>
</div>
```

## 🎨 Características de Diseño

- **Tipografía:** Archivo Black (títulos) + JetBrains Mono (código/tech)
- **Animaciones:** Grid animado de fondo, efectos hover, fade-in scroll
- **Colores:** Paleta cyberpunk con gradientes
- **Formas:** Clip-paths para botones con estilo futurista
- **Responsive:** Optimizado para móvil, tablet y desktop

## 📦 Alternativas de Deploy

### Vercel (muy rápido)
1. Ve a https://vercel.com
2. "Import project" → conecta GitHub
3. Selecciona el repo
4. Deploy automático

### Netlify
1. Arrastra el archivo `index.html` a https://app.netlify.com/drop
2. Listo en segundos

## 🛠️ Próximas mejoras sugeridas

- [ ] Agregar un blog/artículos
- [ ] Integrar formulario de contacto funcional
- [ ] Agregar tema claro/oscuro toggle
- [ ] Sección de certificaciones
- [ ] Animaciones más complejas con GSAP
- [ ] Integración con GitHub API para mostrar repos dinámicamente

## 📞 Contacto

- GitHub: [@Se-basti-ann](https://github.com/Se-basti-ann)
- LinkedIn: [Sebastian Rodriguez Poveda](https://www.linkedin.com/in/sebastian-rodriguez-poveda-64a202157)

---

**¡Creado con 💚 y mucho ☕!**
