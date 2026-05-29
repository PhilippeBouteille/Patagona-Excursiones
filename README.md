# Patagona Excursiones — Sitio Web

Rediseño completo del sitio web de [patagonaexcursiones.cl](https://patagonaexcursiones.cl). HTML estático, sin dependencias, sin build. Desplegado en Vercel.

## Páginas

| Archivo | URL | Descripción |
|---|---|---|
| `index.html` | `/` | Home — hero slider, servicios, excursiones destacadas, Carretera Austral, testimonios, contacto |
| `excursiones.html` | `/excursiones` | Catálogo completo con filtros por categoría |
| `nosotros.html` | `/nosotros` | Empresa, misión, compromisos ambientales, datos legales |
| `carretera-austral.html` | `/carretera-austral` | Landing del producto Carretera Austral a la Carta |
| `contacto.html` | `/contacto` | Formulario, canales, mapa Google |

## Stack

- HTML + CSS + JS vanilla — sin frameworks, sin npm
- Fuentes: Google Fonts (Cormorant Garamond + DM Sans)
- Imágenes: todas servidas desde el dominio original `patagonaexcursiones.cl`
- Deploy: Vercel (static)

## Deploy

1. Push a GitHub (rama `main`)
2. Vercel detecta automáticamente — no requiere configuración
3. URL producción: `patagona-excursiones.vercel.app` (o dominio custom)

## Pendiente para producción

- [ ] Conectar formulario de contacto (Formspree o EmailJS)
- [ ] Reemplazar testimonios con fotos reales de clientes
- [ ] Completar precios faltantes (ski, raquetas, navegación, cetáceos)
- [ ] Agregar versión en inglés de las páginas principales
- [ ] Configurar dominio custom en Vercel
- [ ] Google Analytics / Search Console

## Contacto cliente

**Patagona Excursiones** · Marcela Ríos · contacto@patagonaexcursiones.cl · +56 9 7268 2282
