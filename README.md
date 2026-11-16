# Landing Nexuit

Landing page de Nexuit construida con Astro y Tailwind CSS.

## Desarrollo

```sh
npm install
npm run dev
```

## Scripts

- `npm run dev`: inicia el servidor local.
- `npm run build`: genera la versión estática en `dist/`.
- `npm run preview`: sirve el build localmente.

## Despliegue en Cloudflare

Este proyecto ya puede desplegarse desde Cloudflare Pages conectado al repositorio GitHub `ramonqui/Landing-nexuit`.

Usa esta configuración al crear el proyecto en Cloudflare:

- Framework preset: `Astro`
- Production branch: `main`
- Build command: `npm run build`
- Build output directory: `dist`

Pasos:

1. En Cloudflare Dashboard entra a `Workers & Pages` > `Create application` > `Pages`.
2. Elige `Connect to Git`.
3. Conecta GitHub y selecciona el repo `ramonqui/Landing-nexuit`.
4. Confirma la configuración anterior y crea el proyecto.
5. Cada push a `main` disparará un nuevo despliegue automáticamente.

## Acceso anticipado

- `PUBLIC_EARLY_ACCESS_ENDPOINT` habilita el envío. En una publicación autorizada usar `https://api.nexuit.app/public/early-access`. Sin esta variable el formulario muestra que aún no está disponible. Para probar en local usar un endpoint local o simulado.
- `PUBLIC_EARLY_ACCESS_PRIVACY_URL` usa `https://nexuit.app/privacidad` para producción. En local usa `/privacidad` de forma predeterminada.
- `PUBLIC_EARLY_ACCESS_PRIVACY_VERSION=1.0` debe coincidir exactamente con `EARLY_ACCESS_PRIVACY_VERSION=1.0` del API. La landing usa `1.0` de forma predeterminada.
