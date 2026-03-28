# Dotaez - Sitio Web Profesional

Bienvenido a tu nuevo sitio web profesional para **dotaez.com**. Esta es una landing page moderna, responsiva y lista para publicar.

## 📁 Estructura del Proyecto

```
dotaez-website/
├── index.html              # Archivo principal HTML
├── css/
│   └── styles.css         # Estilos CSS
├── js/
│   └── script.js          # JavaScript interactivo
├── img/
│   ├── favicon.png        # Icono del sitio
│   ├── gallery1.jpg       # Imagen galería 1
│   ├── gallery2.jpg       # Imagen galería 2
│   ├── gallery3.jpg       # Imagen galería 3
│   └── gallery4.jpg       # Imagen galería 4
└── README.md              # Este archivo
```

## 🚀 Características

✅ **Diseño Responsivo** - Funciona perfecto en móvil, tablet y desktop
✅ **Navegación Sticky** - Barra de navegación que se queda en la parte superior
✅ **Formulario de Contacto** - Con validación integrada
✅ **Galería de Imágenes** - Con efectos hover
✅ **Redes Sociales** - Enlaces a tus redes
✅ **Términos y Privacidad** - Modales legales
✅ **SEO Optimizado** - Meta tags y estructura semántica
✅ **Rendimiento** - Código limpio y optimizado

## 🛠️ Cómo Usar

### 1. **Preparar Imágenes**
Reemplaza las siguientes imágenes en la carpeta `img/`:
- `favicon.png` - Icono de 32x32px (logo de tu empresa)
- `gallery1.jpg` - `gallery4.jpg` - Tus proyectos (recomendado 600x400px)

### 2. **Personalizar Contenido**
Edita `index.html` y actualiza:
- El nombre de la empresa (actualmente "Dotaez")
- Los links de redes sociales (busca `https://facebook.com`, etc.)
- Email de contacto: `info@dotaez.com`
- Teléfono: `+1 (000) 123-4567`
- Textos de acerca de, características, etc.

### 3. **Colores Personalizados**
En `css/styles.css`, modifica las variables de color (línea 1-10):
```css
--primary-color: #6366f1;        /* Color principal */
--secondary-color: #1a1a2e;      /* Color secundario */
--accent-color: #f97316;         /* Color acentuado */
```

### 4. **Abrir Localmente**
- Haz doble clic en `index.html`, o
- Haz clic derecho → "Abrir con" → Tu navegador preferido, o
- Usa una extensión como "Live Server" en VS Code

## 📧 Formulario de Contacto

El formulario incluye:
- Validación de campos requeridos
- Validación de email
- Mensaje de confirmación
- Los datos se guardan en la consola del navegador

**Para producción:** Necesitarás un servidor backend (PHP, Node.js, etc.) que maneje los emails. Opciones fáciles:
- Usar FormSubmit.co (gratuito, sin configuración)
- Usar Netlify Forms
- Usar un servidor propio

## 🌐 Publicar en Internet

### Opción 1: GitHub Pages (Gratis)
1. Crea un repositorio en GitHub
2. Sube los archivos
3. Ve a Settings → Pages → Branch: main
4. Tu sitio estará en `https://tu-usuario.github.io/dotaez-website`

### Opción 2: Hosting Tradicional
1. Contrata hosting con dominio en:
   - GoDaddy
   - Namecheap
   - Hostinger
   - SiteGround
2. Sube los archivos via FTP
3. Apunta tu dominio `dotaez.com` al servidor

### Opción 3: Netlify (Recomendado)
1. Sube el proyecto a GitHub
2. Conecta Netlify a tu repo
3. Deploy automático
4. Conecta tu dominio personalizado

## 💬 Formulario de Contacto en Producción

Actualmente, el formulario no envía emails. Para activarlo, tienes varias opciones:

### Con FormSubmit.co (Más fácil):
1. Ve a [formsubmit.co](https://formsubmit.co)
2. En `index.html`, cambia esto:
```html
<form id="contactForm" class="contact-form">
```
Por:
```html
<form action="https://formsubmit.co/tu-email@ejemplo.com" method="POST">
```
3. Quita el `id="contactForm"` del formulario

### Con Node.js/Express:
Si quieres backend más potente, crea un servidor que procese los formularios.

## 🎨 Personalización Avanzada

### Agregar Secciones Nuevas:
1. Copia una sección en HTML
2. Dale un `id` único (ej: `id="servicios"`)
3. Agrega el enlace en la navegación
4. Crea los estilos en CSS

### Cambiar Tipografía:
En `css/styles.css`, línea ~18:
```css
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
```

### Agregar Animaciones:
Usa las clases CSS que ya están: `@keyframes fadeInUp`, efectos hover, etc.

## 📱 Responsive Design

El sitio es 100% responsivo gracias a:
- CSS Grid y Flexbox
- Media Queries (768px y 480px)
- Imágenes adaptativas

## 🔒 Seguridad

Antes de publicar:
- ✅ Verifica que todos los enlaces funcionen
- ✅ Prueba el formulario de contacto
- ✅ Comprueba en múltiples navegadores y dispositivos
- ✅ Actualiza los links de redes sociales reales
- ✅ Cambia el email de contacto

## 🐛 Troubleshooting

**Las imágenes no aparecen:**
- Asegúrate de que estén en la carpeta `img/`
- Verifica que los nombres coincidan en HTML

**El menú hamburguesa no funciona:**
- Asegúrate de que `js/script.js` esté cargado
- Abre la consola del navegador (F12) para ver errores

**Los estilos no se aplican:**
- Limpia el caché del navegador (Ctrl+Shift+Delete)
- Verifica que `css/styles.css` existe

## 📚 Próximos Pasos

1. Personaliza el contenido y colores
2. Agrega tus imágenes de galería
3. Configura el formulario de contacto
4. Prueba en diferentes dispositivos
5. Publica en tu hosting
6. Apunta tu dominio a dotaez.com

## 📞 Soporte

Si necesitas ayuda con HTML, CSS o JavaScript, consulta:
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [W3Schools](https://www.w3schools.com/)

---

**¡Tu sitio web está listo para personalizar y publicar!** 🎉
