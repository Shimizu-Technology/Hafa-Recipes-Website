# Håfa Recipes Website

Marketing, support, and privacy-policy site for Håfa Recipes.

## Development

```bash
npm install
npm run dev
```

## Checks

```bash
npm run gate
```

Use the Node.js version declared in `.nvmrc` so local verification matches CI.

## Deployment

The site is deployed on Netlify. `netlify.toml` configures the Vite build, SPA fallback routing, and security headers.
