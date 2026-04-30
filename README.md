# Kondominia — Landing Page

Landing page pública de [Kondominia](https://kondominia.com), plataforma de gestión condominial para administradoras en Latinoamérica y el Caribe.

## Stack

- HTML estático puro
- [Tailwind CSS](https://tailwindcss.com) vía CDN
- Google Fonts (Quicksand)
- JavaScript vanilla (sin build step)

## Estructura

```
index.html          # Página principal (todo en un solo archivo)
kondominia-1-2.png  # Logo horizontal (nav)
kondominia-5-3.png  # Isotipo (hero y footer)
```

## Deploy

El sitio se despliega automáticamente en **Vercel** con cada push a `main`.

- Framework: `Other` (sitio estático)
- Output directory: `.` (raíz)
- Build command: ninguno

## Funcionalidades del landing

- Hero con texto rotativo animado
- Secciones: Funcionalidades, Cuotas y Cobros, Gas, Visitas, Planes, Testimonios
- Toggle de facturación mensual/anual (−15%)
- Formulario de contacto con webhook a Make (sin exponer emails)
- Widget flotante de WhatsApp e Instagram
- Menú hamburger responsivo
- Modal "Próximamente" en botones de login/registro

## Contacto

- Instagram: [@kondominia](https://instagram.com/kondominia)
- WhatsApp: +1 809 224 4502
