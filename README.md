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

The build writes the static site to `dist/` and packages Cloudflare Build Output in `.cloudflare/output/v0/`. Worker settings live in `cloudflare.config.ts`; `wrangler.config.ts` supplies the static asset directory.

Deploy production with `bun run build && bun run deploy`. For a branch preview, use `bun run build:preview && bun run deploy:preview`. Cloudflare Builds uses these preview commands for this branch.
