# Isabella Álvarez — Portafolio de Arquitectura

Portafolio profesional de arquitectura desplegado con GitHub Pages.

🌐 **Live:** `https://TU-USUARIO.github.io/TU-REPO/`

---

## 🚀 Cómo hacer el deploy en GitHub Pages

### Paso 1 — Crear el repositorio

1. Ve a [github.com](https://github.com) e inicia sesión
2. Haz clic en **"New repository"** (botón verde, esquina superior derecha)
3. Ponle el nombre que quieras, por ejemplo: `portfolio` o `isabella-portfolio`
4. Déjalo en **Public**
5. **NO** marques "Add a README file" (ya viene uno aquí)
6. Haz clic en **"Create repository"**

---

### Paso 2 — Subir los archivos

**Opción A — Desde el navegador (más fácil):**

1. En tu repositorio vacío, haz clic en **"uploading an existing file"**
2. Arrastra todos estos archivos:
   - `index.html`
   - `README.md`
   - `.nojekyll`
3. Escribe un mensaje de commit, por ejemplo: `Initial commit - portfolio`
4. Haz clic en **"Commit changes"**

**Opción B — Con Git (terminal):**

```bash
git init
git add .
git commit -m "Initial commit - portfolio"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main
```

---

### Paso 3 — Activar GitHub Pages

1. En tu repositorio, ve a **Settings** (pestaña superior)
2. En el menú izquierdo, haz clic en **Pages**
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. En **"Branch"**, selecciona `main` y carpeta `/ (root)`
5. Haz clic en **Save**
6. Espera 1-2 minutos y tu sitio estará en:
   ```
   https://TU-USUARIO.github.io/TU-REPO/
   ```

---

## 📁 Estructura de archivos

```
isabella-portfolio/
├── index.html      ← El portafolio completo
├── README.md       ← Este archivo
└── .nojekyll       ← Le dice a GitHub que no procese Jekyll
```

---

## ✏️ Cómo actualizar el contenido

Edita directamente el archivo `index.html`:

| Qué cambiar | Dónde buscarlo en el HTML |
|---|---|
| Tu nombre / descripción | Sección `<!-- ═══ HERO ═══ -->` |
| Email / teléfono / Instagram | Sección `<!-- ═══ CONTACT ═══ -->` |
| Proyectos | Sección `<!-- ═══ PROJECTS ═══ -->` |
| Skills y niveles | Clase `.skills-grid` en About |
| Colores | Variables CSS en `:root { }` |

Después de editar, vuelve a subir el archivo a GitHub y los cambios se reflejan en ~1 minuto.

---

## 🎨 Personalización rápida de colores

En `index.html`, busca el bloque `:root` al inicio del CSS:

```css
:root {
  --cream: #F5F0E8;       /* texto principal */
  --dark: #1A1712;        /* fondo oscuro */
  --accent: #C4914A;      /* dorado / color de énfasis */
  --accent-light: #E8C99A;/* dorado claro (cursiva) */
  --warm-gray: #8A8178;   /* texto secundario */
}
```

Cambia `--accent` a cualquier color para un look completamente diferente.

---

Hecho con ❤️ para Isabella Álvarez · [@isas.space](https://instagram.com/isas.space)
