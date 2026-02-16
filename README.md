# DevAgency - Landing Page Profesional

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

Landing page profesional con estética "Dark Developer" diseñada para agencias de desarrollo. Incluye páginas dedicadas para cada servicio con contenido extenso y diseño premium.

## 🎨 Características

- **Diseño Modern Dark**: Paleta de colores profesional con azul VS Code (#007acc)
- **Totalmente Responsive**: Optimizado para móviles, tablets y desktop
- **Páginas Separadas**: 4 páginas de servicios con contenido detallado
- **Animaciones Suaves**: Efectos parallax, fade-in y scroll-based
- **SEO Optimizado**: Estructura semántica y meta tags
- **Performance**: Carga rápida con CSS optimizado y lazy effects

## 📁 Estructura del Proyecto

```
landing/
├── index.html              # Página principal
├── rifas.html             # Página de Sistemas de Rifas
├── landings.html          # Página de Landing Pages
├── invitaciones.html      # Página de Invitaciones Digitales
├── catalogos.html         # Página de Catálogos Virtuales
├── style.css              # Estilos globales
├── script.js              # JavaScript con animaciones
└── README.md              # Este archivo
```

## 🚀 Servicios Incluidos

### 1. Sistemas de Rifas
Plataforma completa para gestionar rifas y sorteos con:
- Gestión de participantes
- Sistema de sorteos verificable
- Panel de control con analytics
- Pasarelas de pago integradas

### 2. Landing Pages Premium
Páginas de aterrizaje optimizadas con:
- Diseño personalizado
- Integración con redes sociales
- Google Maps
- Analytics avanzado

### 3. Invitaciones Digitales
Tarjetas interactivas para eventos con:
- Countdown timer
- Confirmación RSVP por WhatsApp
- Galería multimedia
- Geolocalización

### 4. Catálogos Virtuales
E-commerce simplificado con:
- Gestión de productos
- Carrito dinámico
- Control de stock
- Integración WhatsApp/ERP

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Flexbox, Grid, Animaciones
- **JavaScript (Vanilla)**: Sin dependencias
- **Font Awesome 6.4.0**: Iconografía
- **Google Fonts**: Inter y JetBrains Mono

## 📦 Instalación y Uso

### Opción 1: Uso Local

1. Clona o descarga el repositorio
2. Abre `index.html` en tu navegador favorito
3. ¡Listo! No requiere servidor ni compilación

### Opción 2: Deploy en Hosting

1. Sube todos los archivos a tu hosting (cPanel, FTP, etc.)
2. Asegúrate de que `index.html` esté en la raíz
3. Configura tu dominio

### Opción 3: Deploy en Vercel/Netlify

```bash
# Netlify
netlify deploy --prod

# Vercel
vercel --prod
```

## ⚙️ Personalización

### Cambiar Colores

Edita las variables CSS en `style.css`:

```css
:root {
    --bg-color: #0d1117;
    --accent-primary: #007acc;  /* Color principal */
    --accent-secondary: #4fc3f7; /* Color secundario */
}
```

### Cambiar Contenido

- **Textos**: Edita directamente en los archivos HTML
- **Servicios**: Modifica las secciones en cada página dedicada
- **Enlaces WhatsApp**: Busca `https://wa.me/yournumber` y reemplaza con tu número

### Agregar Google Analytics

Añade antes del cierre de `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=TU-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'TU-ID');
</script>
```

## 🎯 Secciones de la Página Principal

1. **Hero**: Título impactante con CTAs
2. **Estadísticas**: Números clave del negocio
3. **Servicios**: 4 tarjetas linkradas a páginas dedicadas
4. **Proceso**: Metodología en 4 pasos
5. **Tech Stack**: Tecnologías que dominas
6. **Footer**: Enlaces, redes sociales y newsletter

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 481px - 768px
- **Mobile**: < 480px

## ✨ Efectos y Animaciones

- **Floating Shapes**: Formas animadas en el fondo
- **Parallax Scroll**: Movimiento basado en scroll
- **Fade-in Cards**: Aparición progresiva al hacer scroll
- **Counter Animation**: Contadores animados en estadísticas
- **Hover Effects**: Transformaciones suaves en interacciones

## 🔧 Personalizar Enlaces de Contacto

Busca y reemplaza en todos los archivos:

- `yournumber` → Tu número de WhatsApp (formato: 521234567890)
- Redes sociales en el footer (Instagram, LinkedIn)

## 📈 SEO Tips

1. Actualiza el `<title>` en cada página
2. Añade meta descriptions únicas
3. Optimiza las imágenes (si agregas)
4. Genera un sitemap.xml
5. Configura robots.txt

## 🌐 Compatibilidad de Navegadores

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 📝 To-Do / Mejoras Futuras

- [ ] Agregar modo claro/oscuro toggle
- [ ] Implementar blog section
- [ ] Agregar testimonios de clientes
- [ ] Formulario de contacto con backend
- [ ] Traducción multi-idioma
- [ ] PWA (Progressive Web App)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usarlo y modificarlo.

## 👨‍💻 Créditos

Desarrollado por **DevAgency** - Soluciones Digitales Profesionales

---

## 🤝 Soporte y Contacto

- **WhatsApp**: [Contactar por WhatsApp](https://wa.me/yournumber)
- **Instagram**: [@devagency](#)
- **LinkedIn**: [DevAgency](#)

---

**⭐ Si te gustó este proyecto, dale una estrella!**
