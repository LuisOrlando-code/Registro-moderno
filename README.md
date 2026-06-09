# 📋 Formulario de Registro

Interfaz de registro de usuarios con diseño moderno, construida con HTML y CSS puro.

## 🖼️ Vista previa

Tarjeta de registro centrada con fondo animado, campos de entrada estilizados y botón de envío.

## 📁 Estructura del proyecto

```
/
├── index.html       # Estructura principal
└── estilo.css       # Estilos y animaciones
```

## ✨ Características

- Diseño tipo tarjeta con efecto de círculo decorativo animado
- Animación de rotación de tono de color (`hue-rotate`)
- Inputs con bordes redondeados y transiciones suaves
- Totalmente responsivo para pantallas mayores a 500px
- Tipografía Ubuntu vía Google Fonts
- Íconos con Boxicons

## 🚀 Uso

1. Clona o descarga el repositorio
2. Abre `index.html` en tu navegador

```bash
git clone https://github.com/tu-usuario/formulario-registro.git
cd formulario-registro
```

No requiere instalación ni dependencias adicionales.

## 🛠️ Tecnologías

| Tecnología | Versión |
|---|---|
| HTML | 5 |
| CSS | 3 |
| Google Fonts (Ubuntu) | — |
| Boxicons | 2.1.4 |

## 📐 Estructura del CSS

| Selector | Descripción |
|---|---|
| `.circulo` | Forma orgánica decorativa en la esquina superior izquierda |
| `.circulo::after` | Segunda forma decorativa en la esquina inferior derecha |
| `.tarjeta` | Contenedor principal de la tarjeta |
| `.tarjeta::before` | Semicírculo azul en la parte superior de la tarjeta |
| `.tarjeta .logo` | Ícono circular centrado en la tarjeta |
| `.formulario` | Grid con los campos y botón de registro |
| `@keyframes rotar` | Animación de cambio de tono en el fondo |

## 📱 Responsividad

- **< 500px**: tarjeta ocupa el ancho disponible con padding lateral
- **≥ 500px**: tarjeta fija en 360px centrada en pantalla

## 🌐 Pagina
https://registro-moderno.vercel.app/