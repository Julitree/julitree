# Julitree

Blog profesional de Juliana Gonzalez sobre desarrollo web, diseño de interfaces e inteligencia artificial.

## Estructura

- `dist/`: sitio web estático listo para publicar.
- `wrangler.jsonc`: configuración de Cloudflare Workers.

## Publicación en Cloudflare

Conecta este repositorio desde **Workers & Pages** y utiliza:

- Comando de compilación: déjalo vacío.
- Comando de despliegue: `npx wrangler deploy`.

El contenido público se encuentra en `dist/`.
