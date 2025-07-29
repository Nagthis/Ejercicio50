# Proyecto Bootstrap 5 - Tarea ABP-AE5

## Descripción

Proyecto web responsive desarrollado con Bootstrap 5 como framework CSS principal, implementando las mejores prácticas de Mobile First y componentes interactivos.

## Características Implementadas

### ✅ Framework y Estructura

- **Bootstrap 5.3.7** integrado via CDN
- **Sass/SCSS** para estilos personalizados
- **Layout responsive** con sistema de grillas
- **Mobile First** approach

### ✅ Componentes Bootstrap

- **Navbar responsive** con menú hamburguesa
- **Carousel** de imágenes con controles automáticos
- **Cards** de productos con diseño uniforme
- **Modal** de confirmación interactivo
- **Formulario** con validación HTML5
- **Alerts** y notificaciones

### ✅ Funcionalidades

- Navegación colapsible para móviles/tablets
- Carousel automático con 4 imágenes (5s intervalo)
- Formulario con modal de éxito y animación de carga
- 6 productos en cards responsivas con hover effects
- Diseño adaptativo para diferentes dispositivos

## Estructura del Proyecto

```
├── dist/
│   ├── index.html          # Página principal
│   ├── main.css           # CSS compilado de Sass
│   └── img/               # Imágenes del carousel y productos
├── src/
│   └── custom.scss        # Estilos personalizados en Sass
├── node_modules/          # Dependencias (Bootstrap)
├── package.json          # Configuración del proyecto
└── README.md             # Documentación
```

## Tecnologías Utilizadas

- **HTML5** con semántica moderna
- **Bootstrap 5.3.7** para componentes y layout
- **Sass/SCSS** para estilos personalizados
- **JavaScript** vanilla para interacciones
- **CSS Grid/Flexbox** via Bootstrap

## Instalación y Uso

1. **Instalar dependencias:**

   ```bash
   npm install
   ```

2. **Compilar Sass:**

   ```bash
   sass src/custom.scss dist/main.css --watch
   ```

3. **Abrir en navegador:**
   Abrir `dist/index.html` en cualquier navegador moderno

## Responsive Design

- **Desktop:** Layout de 3 columnas para productos
- **Tablet:** Layout de 2 columnas
- **Mobile:** Layout de 1 columna con menú hamburguesa

## Características Técnicas

- **Carousel:** Imágenes uniformes 800x500px
- **Cards:** Altura uniforme con flex-grow
- **Modal:** Centrado con animaciones suaves
- **Formulario:** Validación nativa HTML5
- **Performance:** CSS optimizado y minificado
