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

## Estructura SASS Modular

```
src/
├── scss/
│   ├── _variables.scss         # Variables globales
│   ├── mixins/
│   │   ├── _index.scss         # Índice de mixins
│   │   ├── _common.scss        # Mixins comunes
│   │   ├── _responsive.scss    # Mixins para responsividad
│   │   └── _neon-effects.scss  # Efectos neón
│   └── components/
│       ├── _index.scss         # Índice de componentes
│       ├── _bootstrap-custom.scss # Personalización Bootstrap
│       └── _buttons.scss       # Botones personalizados
└── custom.scss                 # Archivo principal
```

## Características Técnicas SASS

### Variables Globales

- **Colores:** Sistema de colores consistente
- **Tipografía:** Tamaños y pesos de fuente
- **Espaciado:** Sistema de spacing escalable
- **Breakpoints:** Puntos de quiebre responsive

### Mixins Implementados

- **spacing():** Márgenes y padding
- **transition():** Transiciones personalizables
- **flex-center():** Centrado con flexbox
- **button-variant():** Variantes de botones
- **card-variant():** Estilos de tarjetas
- **hover-lift():** Efectos de elevación
- **responsive-font():** Tipografía fluida
- **media-breakpoint-up/down():** Media queries

### Responsive Design

- **Desktop:** Layout de 3 columnas para productos
- **Tablet:** Layout de 2 columnas
- **Mobile:** Layout de 1 columna con menú hamburguesa
- **Tipografía fluida:** Tamaños adaptativos según viewport

### Personalización Bootstrap

- **Botones:** Estilos personalizados con efectos
- **Cards:** Animaciones y sombras mejoradas
- **Navbar:** Comportamiento responsive optimizado
- **Modal:** Estilos y animaciones personalizadas
- **Formularios:** Validación visual mejorada

## Cambios Implementados - ABPRO5

### ✅ Uso de SASS para Modularización

**Variables Globales (\_variables.scss):**

- Sistema completo de colores (primarios, secundarios, grises)
- Variables de tipografía (tamaños, pesos, line-height)
- Sistema de espaciado escalable
- Breakpoints y contenedores responsive
- Variables para componentes específicos

**Mixins Reutilizables:**

- **\_common.scss:** Mixins para spacing, transiciones, flexbox, posicionamiento
- **\_responsive.scss:** Mixins para responsividad y tipografía fluida
- **\_neon-effects.scss:** Efectos neón personalizados

**Personalización Bootstrap:**

- Componentes Bootstrap personalizados sin perder flexibilidad
- Estilos para botones, cards, navbar, modal, formularios
- Integración perfecta con el sistema de Bootstrap

### ✅ Responsividad y Personalización

**Sistema Responsive Completo:**

- Mixins específicos para diferentes breakpoints
- Tipografía fluida que se adapta al viewport
- Grid system personalizado con CSS Grid
- Carousel responsive con diferentes alturas por dispositivo
- Navbar completamente adaptativa

**Código Limpio y Profesional:**

- Eliminación de comentarios innecesarios
- Estructura modular y escalable
- Variables semánticas y reutilizables
- Mixins optimizados para rendimiento
