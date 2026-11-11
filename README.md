# Pedal Verde — Axel Velásquez
Sitio académico con Astro 7 y Tailwind 4. El teléfono es el ejemplo de la consigna.

Sitio publicado: https://pedal-verde-axel.vercel.app

Repositorio: https://github.com/Axel-2k/pedal-verde

## Ejecutar
Instala Node.js 22.23 o superior. En esta carpeta:
```powershell
npm ci
npm run dev
```
Abre http://localhost:4321. Para generar el sitio: npm run build.

## Publicar en Vercel o Netlify
Importa la carpeta o su repositorio. Comando: npm run build. Directorio de salida: dist.
El ZIP de entrega excluye node_modules, dist y .env.

## Cambiar WhatsApp
Edita whatsapp (formato internacional sin +) y telefonoVisible en src/data/negocio.ts.
Guarda, comprueba ambos botones, ejecuta npm run build y vuelve a desplegar.
La URL publicada debe mostrar el cambio: verifica y recarga también desde el celular.

## Estructura
src/pages/index.astro compone la landing. Servicios.astro convierte las cuatro tarjetas del wireframe en una sección reutilizable. Bicicleta.astro contiene la ilustración SVG original.
Tailwind 4 se configura con @tailwindcss/vite en astro.config.mjs y @import en global.css; no necesita tailwind.config.js.
El wireframe adjunto se creó antes del código; es un esquema digital SVG. Si el docente exige específicamente Figma/Penpot o papel, reprodúcelo allí y entrega la captura o fotografía real.
No hay precios, dirección exacta ni disponibilidad inventados.

Documentación: https://docs.astro.build/en/guides/styling/ y https://tailwindcss.com/docs/installation/framework-guides/astro
