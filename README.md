# ex0therm.dev

The developer portfolio. One HTML file in `public/`, no build step, served as a Cloudflare Workers
static site on the apex domain. Project cards render local fallback content, then sync public repository
metadata from the GitHub API; no token, commit data, or contributor data is requested.

```sh
bun install
bun run dev      # http://localhost:8791
bun run deploy   # ex0therm.dev and www.ex0therm.dev
```
