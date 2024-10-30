# Modern Normalize Mejorado

[![Licencia: MIT](https://img.shields.io/badge/Licencia-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![SCSS](https://img.shields.io/badge/SCSS-v3.0.3-pink.svg)]()
[![Mantenimiento](https://img.shields.io/badge/Mantenido%3F-si-green.svg)]()

Una versión moderna y mejorada en SCSS de [modern-normalize](https://github.com/sindresorhus/modern-normalize) que hace que los navegadores rendericen los elementos de manera más consistente mientras se adhiere a los estándares web modernos.

## 🚀 Características

- Escrito en SCSS para mejor mantenibilidad y personalización
- Elimina prefijos de proveedores obsoletos y propiedades no estándar
- Características de accesibilidad mejoradas
- Normalización mejorada de elementos de formulario
- Mejor manejo de elementos multimedia
- Gestión moderna del foco
- Consideraciones de diseño responsivo incorporadas

## 📦 Instalación

```bash
# Usando npm
npm install modern-normalize-enhanced

# Usando yarn
yarn add modern-normalize-enhanced

# Usando pnpm
pnpm add modern-normalize-enhanced
```

## 🔧 Uso

### SCSS

```scss
@import "modern-normalize-enhanced";
```

### CSS

```html
<link rel="stylesheet" href="modern-normalize-enhanced.css" />
```

## 🆚 Diferencias Clave con el Original

### 1. Arquitectura y Organización

- **Original:** CSS plano con organización básica
- **Mejorado:**
  - Arquitectura basada en SCSS
  - Estructura modular con variables y mixins
  - Mejor organización del código con agrupación lógica

### 2. Propiedades Modernas

- **Original:** Incluye prefijos de proveedores y algunas propiedades no estándar
- **Mejorado:**
  - Eliminado `-webkit-appearance` obsoleto
  - Usa la propiedad moderna `appearance`
  - Propiedades de renderizado de texto actualizadas
  - Gestión moderna del foco con `:focus-visible`

### 3. Características Añadidas

- Manejo responsivo de medios
- Características de accesibilidad mejoradas
- Estilos modernos de selección
- Normalización mejorada de elementos de formulario
- Mejores valores predeterminados para tablas
- Normalización del comportamiento de desplazamiento
- Manejo de estados ARIA

### 4. Variables y Personalización

- **Original:** Variables CSS limitadas
- **Mejorado:**

```scss
$system-fonts: system-ui, -apple-system, "Segoe UI"...;
$monospace-fonts: ui-monospace, SFMono-Regular...;
$base-line-height: 1.15;
```

## 🎯 Compatibilidad con Navegadores

- Chrome ≥ 60
- Firefox ≥ 60
- Safari ≥ 12
- Edge ≥ 79

## 📚 Documentación

### Reset Base

```scss
*,
::before,
::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  border: 0;
}
```

### Tipografía

- Conjunto mejorado de fuentes para sistema y monoespaciadas
- Mejor renderizado de texto
- Manejo mejorado de sub/sup

### Formularios

- Normalización moderna de elementos de formulario
- Estilos de botones mejorados
- Mejor manejo de inputs
- Elementos de formulario accesibles

### Medios

- Manejo responsivo de imágenes
- Mejores valores predeterminados para video e iframe
- Normalización de elementos de audio

## 🤝 Contribuir

1. Haz un fork del proyecto
2. Crea tu rama de característica (`git checkout -b feature/caracteristica-increible`)
3. Haz commit de tus cambios (`git commit -m 'Añadir característica increíble'`)
4. Sube la rama (`git push origin feature/caracteristica-increible`)
5. Abre un Pull Request

## 📝 Buenas Prácticas

1. **Propiedades Personalizadas**

```scss
// Usa variables para valores consistentes
$base-line-height: 1.15;
```

2. **Elementos Multimedia**

```scss
// Siempre incluye valores predeterminados responsivos
img {
  max-width: 100%;
  height: auto;
}
```

3. **Accesibilidad**

```scss
// Incluye manejo de estados ARIA
[aria-disabled="true"] {
  cursor: not-allowed;
}
```

## 🔍 Pruebas

```bash
# Ejecutar pruebas
npm test

# Ejecutar linting
npm run lint

# Verificar formato
npm run format
```

## 📋 Pendientes

- [ ] Añadir soporte RTL
- [ ] Mejorar compatibilidad con modo oscuro
- [ ] Añadir normalización de CSS Grid
- [ ] Mejorar estilos de impresión

## 🎯 Plan de Desarrollo

- **v3.1.0** - Añadir normalización de CSS Grid
- **v3.2.0** - Soporte mejorado para modo oscuro
- **v3.3.0** - Soporte RTL
- **v4.0.0** - Modernización completa de todas las propiedades

## 📜 Licencia

Este proyecto está basado en [modern-normalize](https://github.com/sindresorhus/modern-normalize) de Sindre Sorhus.
Licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles

## 🙏 Agradecimientos

- [Sindre Sorhus](https://github.com/sindresorhus) por el modern-normalize original
- [Nicolas Gallagher](https://github.com/necolas) por Normalize.css
- Todos los contribuidores que han ayudado a mejorar este proyecto

---

## 💡 Consejos de Uso

### Orden de Importación

```scss
// 1. Modern Normalize Mejorado
@import "modern-normalize-enhanced";

// 2. Tus variables
@import "variables";

// 3. Tus estilos
@import "styles";
```

### Personalización

```scss
// Sobrescribe las variables predeterminadas
$base-line-height: 1.6;
$system-fonts: "Tu Stack de Fuentes Personalizado";
```

---

Hecho con ❤️ por Johannes Rosenkranz
