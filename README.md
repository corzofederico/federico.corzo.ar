# Portfolio – Federico Corzo

Sitio web personal construido con **Astro** y **Tailwind CSS**.

## Stack

- [Astro](https://astro.build/) — framework estático con component islands
- [Tailwind CSS](https://tailwindcss.com/) — estilos utilitarios

## Estructura del proyecto

```
portfolio/
├── public/
│   ├── yo.jpg               ← foto de perfil
│   └── cv-federico-corzo.pdf ← CV
│   └── signature.svg ← web icon
├── src/
│   ├── components/
│   │   ├── Navbar.astro
│   │   ├── Hero.astro
│   │   ├── Projects.astro
│   │   ├── Skills.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       ├── index.astro
│       └── 404.astro
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## Cómo usar

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo
npm run dev

# Build para producción
npm run build

# Preview del build
npm run preview
```

## Deploy

### Cloudflare Pages / Vercel / Netlify
Simplemente conectás el repositorio y configurás:
- Build command: `npm run build`
- Output directory: `dist`
