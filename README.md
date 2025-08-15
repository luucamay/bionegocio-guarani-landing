# Bionegocio Guarani Landing Page

Una landing page moderna y responsiva para el proyecto Bionegocio Guarani, que muestra el recorrido por lo construido en el Bosque Guarayos a través de bionegocios sostenibles.

## 🌟 Características

- **Diseño Mobile-First**: Optimizado para dispositivos móviles con responsive design
- **Navegación Suave**: Scroll suave entre secciones y navegación móvil intuitiva
- **Animaciones Modernas**: Efectos de entrada y hover para mejorar la experiencia del usuario
- **SEO Optimizado**: Meta tags y estructura semántica para mejor posicionamiento
- **Accesibilidad**: Navegación por teclado y etiquetas ARIA
- **Performance**: Código optimizado y carga eficiente

## 📱 Secciones Incluidas

1. **Hero Section** - Título principal y llamada a la acción
2. **Presentación del Proyecto** - Objetivo, financiamiento y ejecución
3. **Resultados Alcanzados** - Impactos y estadísticas del proyecto
4. **El Bosque que Habitamos** - Información de municipios y reservas naturales
5. **Proceso Integral** - Timeline del proceso de implementación
6. **Bionegocios Sostenibles** - Tipos de negocios y historias de éxito
7. **Emprendimientos por Sector** - Frutas, artesanías y cosmética
8. **Contacto** - Formulario de contacto e información de contacto

## 🚀 Instalación y Uso

### Requisitos

- Navegador web moderno
- Servidor web local (opcional para desarrollo)

### Pasos de Instalación

1. **Clonar o descargar** el proyecto en tu directorio local
2. **Abrir** el archivo `index.html` en tu navegador
3. **Personalizar** el contenido según tus necesidades

### Desarrollo Local

Para desarrollo local, puedes usar un servidor web simple:

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (si tienes http-server instalado)
npx http-server

# Con PHP
php -S localhost:8000
```

Luego abre `http://localhost:8000` en tu navegador.

## 🎨 Personalización

### Colores y Estilos

Los colores principales están definidos en `styles.css`:

```css
:root {
  --primary-color: #2d5a27; /* Verde oscuro */
  --secondary-color: #4caf50; /* Verde claro */
  --accent-color: #f8f9fa; /* Gris claro */
  --text-color: #333; /* Texto principal */
}
```

### Contenido

Edita el archivo `index.html` para personalizar:

- **Títulos y subtítulos** de cada sección
- **Texto descriptivo** del proyecto
- **Estadísticas** y números
- **Información de contacto**
- **Enlaces** a redes sociales

### Imágenes y Multimedia

Reemplaza los placeholders con contenido real:

1. **Fotografías del proyecto** - Reemplaza los divs con clase `media-placeholder`
2. **Videos** - Agrega iframes de YouTube o Vimeo
3. **Mapas** - Integra Google Maps o mapas personalizados
4. **Logos** - Agrega logos de instituciones participantes

### Ejemplo de Reemplazo de Imagen:

```html
<!-- Antes (placeholder) -->
<div class="media-placeholder">
  <i class="fas fa-image"></i>
  <span>Fotografías del Proyecto</span>
</div>

<!-- Después (imagen real) -->
<img
  src="images/proyecto-foto.jpg"
  alt="Fotografía del proyecto de reforestación"
  class="media-image"
/>
```

## 📊 Datos a Personalizar

### Estadísticas del Proyecto

- Número de árboles plantados
- Familias beneficiadas
- Ingresos generados
- Áreas reforestadas

### Información de Municipios

- Datos demográficos de Ascensión de Guarayos
- Información de reservas naturales
- Patrimonio cultural
- Otros municipios involucrados

### Bionegocios

- Tipos de productos maderables
- Productos no maderables
- Historias de éxito específicas
- Sectores de emprendimientos

## 🔧 Funcionalidades JavaScript

### Navegación Móvil

- Menú hamburguesa animado
- Navegación táctil optimizada
- Cierre automático al seleccionar opción

### Animaciones

- Efectos de entrada al hacer scroll
- Animación de números en estadísticas
- Efectos hover en tarjetas
- Efecto de escritura en el título principal

### Formulario de Contacto

- Validación de campos
- Simulación de envío
- Mensajes de confirmación

## 📱 Responsive Breakpoints

- **Mobile**: < 768px (diseño de una columna)
- **Tablet**: 768px - 1023px (diseño de dos columnas)
- **Desktop**: ≥ 1024px (diseño completo)

## 🌐 Compatibilidad de Navegadores

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Internet Explorer 11+ (con limitaciones)

## 📁 Estructura del Proyecto

```
bionegocio-guarani-landing/
├── index.html          # Archivo principal HTML
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
├── README.md           # Documentación
└── images/             # Carpeta para imágenes (crear)
    ├── hero-bg.jpg
    ├── proyecto-fotos/
    ├── bosque-fotos/
    └── emprendimientos/
```

## 🚀 Despliegue

### Hosting Estático

- **Netlify**: Arrastra la carpeta del proyecto
- **Vercel**: Conecta tu repositorio Git
- **GitHub Pages**: Activa en configuración del repositorio
- **Firebase Hosting**: Usa Firebase CLI

### Servidor Web

- **Apache**: Copia archivos a `/var/www/html/`
- **Nginx**: Configura el directorio raíz
- **IIS**: Publica en directorio web

## 📞 Soporte y Contacto

Para soporte técnico o personalización adicional:

- **Email**: [tu-email@ejemplo.com]
- **Documentación**: [enlace-a-docs]
- **Issues**: [enlace-al-repositorio]

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature
3. Commit tus cambios
4. Push a la rama
5. Abre un Pull Request

---

**Bionegocio Guarani** - Transformando y dejando huella en el Bosque Guarayos 🌱
