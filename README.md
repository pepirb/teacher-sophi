# Teacher Sophi

App web para que Sophia lleve el control de sus clases particulares.

Una sola página en React + Tailwind, todo embebido en `index.html` (sin build step). Los datos se guardan en `localStorage` del navegador.

## Funcionalidades

- Registrar clases por alumno (fecha, hora, tarifa por hora, invitadas).
- Total acumulado del mes y por alumno.
- Generar reportes para cobrar (texto o imagen tipo recibo).
- Cerrar mes y archivar pagos en historial.

## Cómo correrla localmente

Abrí el `index.html` en cualquier navegador. No hace falta instalar nada.

```bash
open index.html
```

## Deploy

El sitio se puede desplegar como sitio estático en Vercel, Netlify o cualquier hosting. No hay build — se sube tal cual.

### Vercel
```bash
npx vercel --prod
```

### Historial previo
La versión vieja está en Netlify: https://stellar-cupcake-f297c7.netlify.app/
