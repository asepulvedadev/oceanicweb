# OceanicWeb - Landing Page

Landing page moderna y profesional para OceanicWeb, desarrollada con Astro y Tailwind CSS.

## 🚀 Características

- Diseño moderno y responsivo
- Modo oscuro por defecto
- Optimizado para SEO
- Componentes reutilizables
- Animaciones suaves
- Formulario de contacto
- Integración con redes sociales

## 🛠️ Tecnologías Utilizadas

- [Astro](https://astro.build) - Framework web moderno
- [Tailwind CSS](https://tailwindcss.com) - Framework CSS utilitario
- [TypeScript](https://www.typescriptlang.org) - Superset de JavaScript tipado
- [Bun](https://bun.sh) - Empaquetador y runtime de JavaScript

## 📦 Requisitos Previos

- Node.js 18 o superior
- Bun 1.0 o superior

## 🚀 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/oceanicweb.git
cd oceanicweb
```

2. Instala las dependencias:
```bash
bun install
```

3. Inicia el servidor de desarrollo:
```bash
bun run dev
```

4. Abre [http://localhost:4321](http://localhost:4321) en tu navegador.

## 🏗️ Estructura del Proyecto

```
oceanicweb/
├── public/
│   ├── casos/
│   └── testimonios/
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Servicios.astro
│   │   ├── Tecnologias.astro
│   │   ├── CasosExito.astro
│   │   ├── Testimonios.astro
│   │   ├── Contacto.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── tailwind.config.mjs
├── tsconfig.json
└── package.json
```

## 🎨 Personalización

### Colores
La paleta de colores se puede modificar en `tailwind.config.mjs`:

```js
colors: {
  'oceanic-blue': '#1E3A8A',
  'tech-green': '#10B981',
  'deep-black': '#0A0A0A',
}
```

### Contenido
El contenido de cada sección se puede modificar en los respectivos componentes en la carpeta `src/components/`.

## 📱 Responsive Design

La landing page está optimizada para:
- Móviles (320px y superior)
- Tablets (768px y superior)
- Escritorio (1024px y superior)

## 🚀 Deployment

El proyecto está configurado para ser desplegado en Netlify. Para desplegar:

1. Conecta tu repositorio a Netlify
2. Configura las variables de entorno si es necesario
3. Netlify detectará automáticamente que es un proyecto Astro y lo desplegará

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue primero para discutir los cambios que te gustaría hacer.

## 📧 Contacto

Para cualquier consulta, contáctanos en contacto@oceanicweb.com
