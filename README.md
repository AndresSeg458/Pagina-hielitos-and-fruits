# Página Web Estática para "Hielitos and Fruit"

Una página web moderna y responsiva para una heladería, cafetería y comidas rápidas, diseñada para mostrar el menú, información de contacto, ubicación y crear una experiencia amigable para los clientes.

## 🌟 Características

- **Diseño Responsivo**: Se adapta perfectamente a dispositivos móviles, tablets y escritorio
- **Navegación Intuitiva**: Menú de navegación fijo con scroll suave
- **Menú Interactivo**: Sistema de categorías para organizar helados, bebidas & café, y comidas rápidas
- **Formulario de Contacto**: Con validación y sistema de notificaciones
- **Animaciones Suaves**: Efectos visuales que mejoran la experiencia del usuario
- **Optimizado para SEO**: Estructura HTML semántica y meta tags apropiados

## 📁 Estructura del Proyecto

```
pagina-web-negocio/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript interactivo
└── README.md           # Documentación
```

## 🚀 Cómo Usar

1. **Abrir la página**: Simplemente abre el archivo `index.html` en tu navegador web
2. **Personalizar contenido**: Edita el archivo HTML para cambiar:
   - Nombre del negocio
   - Elementos del menú y precios (helados, bebidas, comidas)
   - Información de contacto
   - Dirección y ubicación
3. **Modificar estilos**: Ajusta los colores y diseño en `styles.css`
4. **Agregar funcionalidades**: Extiende las características en `script.js`

## 🎨 Personalización

### Cambiar Colores
Los colores principales se pueden modificar en `styles.css`:
- **Color principal**: `#ff6b9d` (rosa vibrante)
- **Color secundario**: `#2c3e50` (azul oscuro)
- **Gradiente hero**: `#74b9ff` a `#fd79a8` (azul a rosa)

### Modificar el Menú
En `index.html`, busca las secciones:
- `#helados` - Helados artesanales
- `#bebidas` - Bebidas & Café
- `#comidas` - Comidas rápidas

### Actualizar Información de Contacto
Modifica los datos en la sección `#contacto`:
- Teléfonos
- Email
- Dirección
- Horarios de atención

## 📱 Características Responsivas

- **Desktop**: Diseño completo con todas las características
- **Tablet**: Adaptación de grid y espaciados
- **Mobile**: Menú hamburguesa y diseño vertical optimizado

## 🔧 Funcionalidades JavaScript

- **Menú móvil**: Hamburguesa animada
- **Filtros de menú**: Cambio entre categorías
- **Scroll suave**: Navegación fluida entre secciones
- **Formulario**: Validación y envío simulado
- **Animaciones**: Efectos al hacer scroll
- **Notificaciones**: Sistema de mensajes para el usuario

## 🌐 Integración de Mapas

El proyecto incluye un placeholder para integrar Google Maps. Para activarlo:

1. Obtén una API key de Google Maps
2. Reemplaza el contenido de `.map-placeholder` con el iframe de Google Maps
3. Actualiza las coordenadas con la ubicación real del negocio

## 📞 Integración de WhatsApp

Para agregar un botón de WhatsApp flotante para pedidos de helados, agrega este código antes del cierre de `</body>`:

```html
<a href="https://wa.me/573012345678" class="whatsapp-float" target="_blank">
    <i class="fab fa-whatsapp"></i>
</a>
```

## 🎯 Próximas Mejoras Sugeridas

- [ ] Integración con Google Maps real
- [ ] Galería de fotos de helados y productos
- [ ] Sistema de reservas online
- [ ] Blog o sección de noticias
- [ ] Integración con redes sociales
- [ ] Sistema de pedidos online
- [ ] Múltiples idiomas

## 📧 Soporte

Para modificaciones o soporte técnico, contacta al desarrollador.

## 📄 Licencia

Este proyecto es de uso libre para fines comerciales y educativos.

---

**Desarrollado con ❤️ para Hielitos and Fruit** 🍦
