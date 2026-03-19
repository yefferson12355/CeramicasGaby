# Cerámicas Gabi Catalog Website

Sitio web moderno de catálogo para Cerámicas Gabi, construido con Astro y Tailwind CSS.

## 🚀 Descripción

Cerámicas Gabi es un sitio web elegante y responsivo diseñado para mostrar la amplia variedad de productos cerámicos de alta calidad. Construido con tecnologías modernas para garantizar el mejor rendimiento y experiencia de usuario.

## ✨ Características

- ⚡ Rendimiento ultra rápido con Astro
- 🎨 Diseño moderno con Tailwind CSS
- 📱 Completamente responsivo
- 🔍 Optimizado para SEO
- 🚀 Deploy listo en Bolt

## 📁 Estructura del Proyecto

```
├── public/                # Archivos estáticos públicos
│   ├── favicon.svg
│   └── [assets estáticos]
├── src/
│   ├── assets/           # Imágenes y recursos del proyecto
│   ├── components/       # Componentes reutilizables
│   │   ├── Header.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── Welcome.astro
│   │   └── Card.astro
│   ├── layouts/         # Layouts base
│   │   └── Layout.astro
│   └── pages/           # Páginas del sitio
│       └── index.astro
├── astro.config.mjs     # Configuración de Astro
├── tailwind.config.mjs  # Configuración de Tailwind CSS
├── tsconfig.json        # Configuración de TypeScript
├── package.json         # Dependencias del proyecto
└── README.md           # Este archivo
```

## 🛠️ Scripts Disponibles

| Comando | Acción |
|---------|--------|
| `npm install` | Instala las dependencias |
| `npm run dev` | Inicia el servidor de desarrollo en `localhost:3321` |
| `npm run build` | Construye el sitio para producción en `./dist/` |
| `npm run preview` | Vista previa local de la compilación de producción |
| `npm run astro -- --help` | Obtén ayuda sobre los comandos CLI de Astro |

## 🚀 Cómo Empezar

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Iniciar servidor de desarrollo:**
   ```bash
   npm run dev
   ```

3. **Abrir en navegador:**
   Visita `http://localhost:3321` en tu navegador

4. **Editar archivos:**
   Los cambios se reflejarán automáticamente en el navegador

## 🏗️ Construir para Producción

```bash
npm run build
```

Esto genera una carpeta `dist/` con el sitio compilado y listo para producción.

## 📝 Personalización

### Colores
Los colores se pueden personalizar en `tailwind.config.mjs` bajo la sección `theme.extend.colors`

### Contenido
- Edita [src/pages/index.astro](src/pages/index.astro) para modificar la página principal
- Añade nuevas páginas en `src/pages/`
- Personaliza componentes en `src/components/`

### Producto
Modifica la información del sitio en [astro.config.mjs](astro.config.mjs)

## 📚 Aprender más

- [Documentación de Astro](https://docs.astro.build)
- [Documentación de Tailwind CSS](https://tailwindcss.com/docs)
- [Discord de Astro](https://astro.build/chat)

## 📄 Licencia

Este proyecto es propiedad de Cerámicas Gabi. © 2026 Todos los derechos reservados.

## 📞 Contacto

Para más información sobre nuestros productos, contáctanos en:
- 📧 Email: info@ceramicasgabi.com
- 📱 Teléfono: +56 9 XXXX XXXX
