# Dojo Kazoku — Design v1 (Astro)

Sitio web del Salón Kazoku: Karate Do Ken Shin Kan y Pilates.

## Requisitos

- Node.js 18+
- npm

## Comandos

```bash
# Desarrollo (servidor local con recarga en caliente)
npm run dev

# Construcción para producción (genera carpeta dist/)
npm run build

# Vista previa de la versión de producción
npm run preview
```

## Estructura

```
src/
├── components/   # Componentes Astro (Nav, Hero, Servicios, etc.)
├── layouts/      # Layout base con header HTML
├── pages/        # Página principal index.astro
└── styles/       # CSS global con tokens de diseño
```

## Despliegue

La carpeta `dist/` contiene los archivos estáticos listos para subir a cualquier
hosting (Netlify, Vercel, Cloudflare Pages, servidor Apache/Nginx).
