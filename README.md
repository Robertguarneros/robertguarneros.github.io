# Astro Starter Kit: Minimal

```sh
pnpm create astro@latest -- --template minimal
```

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |

```bash
robertguarneros.github.io/
├── 📁 .github/workflows/          # GitHub Actions automation
│   ├── deploy.yml                 # Deploys your Astro site
│   └── metrics.yml                # Updates GitHub stats daily
│
├── 📁 public/                     # Static files (served as-is)
│   ├── CNAME                      # Your custom domain
│   ├── CV_README.md               # Instructions for CV PDF
│   └── *.svg                      # Your GitHub stats images
│
├── 📁 src/                        # Source code (processed by Astro)
│   ├── 📁 content/                # Content collections (blog posts)
│   │   ├── blog/welcome.md        # Sample blog post
│   │   └── config.ts              # Defines blog schema
│   │
│   ├── 📁 layouts/                # Reusable page templates
│   │   └── BaseLayout.astro       # Main layout with nav & theme
│   │
│   └── 📁 pages/                  # Routes (file = URL path)
│       ├── index.astro            # / (About Me)
│       ├── stats.astro            # /stats
│       ├── cv.astro               # /cv
│       └── blog/
│           ├── index.astro        # /blog (list of posts)
│           └── [slug].astro       # /blog/{post-name}
│
├── astro.config.mjs               # Astro configuration
├── package.json                   # Dependencies & scripts
└── tsconfig.json                  # TypeScript configuration
```