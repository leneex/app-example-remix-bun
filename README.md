# Remix on Bun

Example [Remix](https://remix.run/) app running on [Bun](https://bun.sh/). Remix is a full-stack React framework that now continues as React Router in framework mode, which this example uses. Bun is a fast all-in-one JavaScript runtime and package manager compatible with Node.js.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Static site — Railpack build |
| Single-page application (SPA) | off |
| Project directory | `/` |
| Output directory | `/build/client` |
| Install command | leave empty |
| Build command | leave empty |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
bun install

# run in development mode
bun run dev

# build for production
bun run build
```
