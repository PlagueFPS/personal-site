# Angel Pichardo

Personal site built with Astro. The homepage is [`src/pages/index.astro`](src/pages/index.astro); static assets live in `public/`.

## Local development

```sh
bun install
bun run dev
```

Open http://localhost:4321. Astro reloads the page when you edit the source.

## Production preview

```sh
bun run build
bun run preview
```

The build writes the static site to `dist/`. Cloudflare is configured to serve that directory; run the build before deploying.
