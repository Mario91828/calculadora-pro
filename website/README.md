# 🔢 Calculadora Científica Profesional - Sitio Web

Sitio web oficial para descargar la Calculadora Científica Profesional.

## 📁 Estructura del Proyecto

```
website/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript interactivo
├── downloads/          # Archivos de descarga
│   └── CalculadoraProfesional.exe
└── README.md          # Este archivo
```

## 🚀 Cómo usar

### Opción 1: Abrir localmente
1. Abre el archivo `index.html` en tu navegador
2. La página funcionará completamente sin necesidad de servidor

### Opción 2: Con servidor local (recomendado para desarrollo)
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes http-server instalado)
npx http-server

# Con PHP
php -S localhost:8000
```

Luego abre: `http://localhost:8000`

## ✨ Características del Sitio

- ✅ **Diseño moderno y responsivo** - Se adapta a móviles, tablets y desktop
- ✅ **Detección automática de SO** - Resalta la descarga para tu sistema
- ✅ **Animaciones suaves** - Transiciones y efectos visuales
- ✅ **Sistema de notificaciones** - Feedback visual al descargar
- ✅ **Scroll suave** - Navegación fluida entre secciones
- ✅ **Tema oscuro** - Diseño profesional con colores modernos

## 🎨 Personalización

### Cambiar colores
Edita las variables CSS en `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... más colores */
}
```

### Agregar más sistemas operativos
1. Duplica una tarjeta de descarga en `index.html`
2. Actualiza el icono, nombre y requisitos
3. Crea la función de descarga en `script.js`

## 📦 Despliegue

### GitHub Pages
1. Sube la carpeta `website` a un repositorio de GitHub
2. Ve a Settings > Pages
3. Selecciona la rama y carpeta
4. Tu sitio estará en: `https://tuusuario.github.io/repositorio`

### Netlify
1. Arrastra la carpeta `website` a netlify.com/drop
2. Tu sitio estará listo en segundos

### Vercel
```bash
npm i -g vercel
cd website
vercel
```

## 🔧 Mantenimiento

### Actualizar el ejecutable
1. Copia el nuevo `.exe` a `website/downloads/`
2. Actualiza la versión y tamaño en `index.html`

### Agregar capturas de pantalla
1. Coloca las imágenes en una carpeta `website/images/`
2. Reemplaza los placeholders en `index.html`:
```html
<img src="images/screenshot1.png" alt="Calculadora Principal">
```

## 📊 Analytics (Opcional)

Para rastrear descargas, agrega Google Analytics:

1. Crea una cuenta en Google Analytics
2. Agrega el código de seguimiento en `index.html` antes de `</head>`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=TU-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TU-ID');
</script>
```

## 🌐 SEO

El sitio ya incluye:
- ✅ Meta tags optimizados
- ✅ Estructura semántica HTML5
- ✅ Títulos y descripciones
- ✅ URLs amigables

Para mejorar el SEO:
1. Agrega un `sitemap.xml`
2. Crea un `robots.txt`
3. Agrega meta tags Open Graph para redes sociales

## 📱 Responsivo

El sitio se adapta a:
- 📱 Móviles (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop (1024px+)
- 🖥️ Pantallas grandes (1920px+)

## 🐛 Solución de Problemas

**La descarga no funciona:**
- Verifica que el archivo esté en `website/downloads/`
- Comprueba la ruta en `script.js`
- Abre la consola del navegador (F12) para ver errores

**Las animaciones no funcionan:**
- Asegúrate de que JavaScript esté habilitado
- Verifica que `script.js` esté cargando correctamente

## 📄 Licencia

Este sitio web es parte del proyecto Calculadora Científica Profesional.

## 👨‍💻 Autor

Creado con ❤️ para el proyecto Calculadora Pro

---

**¿Necesitas ayuda?** Abre un issue o contacta al desarrollador.
