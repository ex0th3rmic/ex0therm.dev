# ex0therm.dev

The landing page. One HTML file in `public/`, no build step, served as a Cloudflare Workers static
site on the apex domain.

```sh
bun install
bun run dev      # http://localhost:8791
bun run deploy   # ex0therm.dev and www.ex0therm.dev
```
