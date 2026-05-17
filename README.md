# My Cloud Website

Un sitio web multi-página creado con HTML, CSS y alojado en GitHub Pages.

## 📁 Estructura del Proyecto

```
├── index.html      # Página de inicio (Home)
├── about.html      # Página de presentación personal
├── contact.html    # Página de contacto
├── style.css       # Estilos de la página web
└── README.md       # Este archivo
```

## 📋 Información Personal

- **Nombre:** Angel
- **Roll Number:** 2417098
- **Email:** raisoniya211@gmail.com
- **Phone:** 010 2941 1881
- **University:** Kyungdong University

## 🚀 Cómo Usar GitHub Pages

### Paso 1: Crear un repositorio en GitHub

1. Ve a [GitHub](https://github.com)
2. Crea un nuevo repositorio con el nombre: `mywebsite`
3. NO inicialices con README (lo haremos nosotros)

### Paso 2: Subir los archivos

Opción A - Usando Git (Terminal):
```bash
# Clona el repositorio
git clone https://github.com/TU_USUARIO/mywebsite.git
cd mywebsite

# Copia los archivos HTML y CSS aquí
# Luego:
git add .
git commit -m "Initial commit: Add website files"
git push origin main
```

Opción B - Directamente en GitHub:
1. Abre tu repositorio en GitHub
2. Click en "Add file" → "Upload files"
3. Selecciona todos los archivos (.html y .css)
4. Click en "Commit changes"

### Paso 3: Habilitar GitHub Pages

1. Ve a **Settings** de tu repositorio
2. En el menú izquierdo, busca **Pages**
3. En "Source", selecciona **main** branch
4. Click en **Save**

### Paso 4: Acceder al sitio

Tu sitio estará disponible en:
```
https://TU_USUARIO.github.io/mywebsite
```

Ejemplo:
```
https://angel2024.github.io/mywebsite
```

## 🎨 Características del Sitio

- **Navegación responsive:** Funciona en desktop, tablet y móvil
- **Diseño moderno:** Gradientes y sombras profesionales
- **3 páginas:**
  - **Home:** Página de bienvenida
  - **About:** Información personal
  - **Contact:** Detalles de contacto

## ✏️ Personalización

### Cambiar la imagen de perfil

1. Descarga tu foto (recomendado: cuadrada, 500x500px)
2. Renómbrala como `profile.jpg`
3. Sube el archivo al mismo repositorio
4. En `about.html` cambia esta línea:
```html
<img src="profile.jpg" alt="Profile Picture" class="profile-pic">
```

### Cambiar colores

En `style.css`, busca estas líneas y cambia los colores hexadecimales:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
/* Cambia #667eea y #764ba2 por tus colores preferidos */
```

### Cambiar el texto

Edita el contenido directamente en los archivos .html

## 📱 Responsive Design

El sitio web es completamente responsive y se adapta a:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Móvil (menos de 768px)

## ✅ Checklist antes de entregar

- [ ] Los 3 archivos HTML están subidos
- [ ] El archivo style.css está subido
- [ ] GitHub Pages está habilitado
- [ ] El sitio es accesible en `https://TU_USUARIO.github.io/mywebsite`
- [ ] Todas las páginas cargan correctamente
- [ ] Los links de navegación funcionan
- [ ] Los estilos CSS se aplican correctamente
- [ ] El teléfono y email son correctos

## 🔗 Recursos útiles

- [GitHub Pages Documentation](https://pages.github.com)
- [HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

**Creado para Cloud Computing Lab - Kyungdong University**
