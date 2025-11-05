# Aprendiendo Tailwind CSS
Este proyecto es una guía práctica para aprender y experimentar con [Tailwind CSS](https://tailwindcss.com). Incluye ejemplos de componentes, animaciones, gradientes, integración de fuentes personalizadas y uso de iconos SVG. El objetivo es facilitar el aprendizaje de Tailwind CSS y sus utilidades modernas en proyectos web reales.

## Características

- **Tailwind CSS**: Configuración y ejemplos de clases utilitarias.
- **Animaciones personalizadas**: Integración con el plugin `@midudev/tailwind-animations`.
- **Fuentes personalizadas**: Uso de la fuente `Inter` con `@font-face`.
- **Variables CSS**: Definición de colores y breakpoints en el archivo `input.css`.
- **Botones sociales**: Componentes con estilos y colores oficiales de cada red.
- **SVG Icons**: Uso de sprites SVG para iconografía escalable.
- **Ejemplos de gradientes**: Aplicación de gradientes con colores corporativos.
- **Componentes responsive**: Uso de breakpoints y clases responsivas.


## Estructura del proyecto

```
aprendiendo-tailwind/
├── assets/
│   ├── fonts/
│   ├── sprite.svg
│   └── verified-icons.svg
├── input.css
├── output.css
├── index.html
└── tailwind.config.js
```

## Instalación y uso

1. **Instala las dependencias** (si usas npm o pnpm):
```
npm install
# o
pnpm install
```

2. **Compila Tailwind CSS**:
```
npx tailwindcss -i ./input.css -o ./assets/output.css --watch
```

3. Abre `index.html` en tu navegador para ver los ejemplos.

## Personalización

- Modifica `input.css` para agregar o cambiar variables, fuentes y utilidades.
- Añade tus propios componentes y experimenta con las clases de Tailwind.
- Los iconos SVG pueden personalizarse en `sprite.svg`.

## Recursos útiles

- [Documentación oficial de Tailwind CSS](https://tailwindcss.com/docs)
- [Playground de Tailwind CSS](https://play.tailwindcss.com)
- [Guía de animaciones Tailwind](https://tailwindcss.com/docs/animation)

**¡Diviértete aprendiendo Tailwind CSS!**

