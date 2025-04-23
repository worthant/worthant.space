<div align="center">
  <a href="https://worthant.space">
    <h1 align="center">worthant.space</h1>
  </a>
  
  <p align="center">
    <a href="https://nextjs.org" target="_blank">
      <img src="https://img.shields.io/badge/Next.js-black?style=for-the-badge&logo=next.js" alt="Next.js" />
    </a>
    <a href="https://tailwindcss.com" target="_blank">
      <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
    </a>
    <a href="https://www.typescriptlang.org" target="_blank">
      <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
    </a>
    <a href="https://vercel.com" target="_blank">
      <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel" />
    </a>
  </p>
  
  <p align="center">
    My personal engineering space — portfolio, projects showcase, and digital playground
  </p>
  
</div>

<details open>
    <summary><b>built with a bunch of nonsense</b> (<i>modern frontend tools</i>)</summary>

- **[Next.js](https://nextjs.org/)** — React framework with _neat things_:
  `SSR`, `API routes`, `optimized build system`
- **[Tailwind CSS](https://tailwindcss.com/)** — Just a CSS framework <ins>I
  like</ins>. Makes CSS painless _sometimes_. I'm an engineer, <ins>not a
  coder</ins>.
- **[Upstash](https://upstash.com)** — Free Serverless Redis. Even tho i have
  home servers, _Free is always good_
- **[Contentlayer](https://www.contentlayer.dev/)** — Just some content SDK that
  transforms Markdown/MDX into type-safe JSON data. Provides structured content
  management with schema validation. Very neat tool actually.
- **[Vercel](https://vercel.com/)** — I like this platform for it's analytics,
  pleasant design, simplicity and strong free tier. However, doesn't really
  matter - github/gitlab/cloudflare/netlify/heroku, it's whatever.

</details>

## Running Locally

If you want to use it for some reason, here is how:

1. Clone repo:

```bash
git clone git@github.com:worthant/worthant.space.git
cd worthant.space
```

2. Set up environment (check
   [`.env.example`](https://github.com/worthant/worthant.space/blob/main/.env.example)
   for reference)

```bash
cp .env.example .env
```

3. Install deps and launch development server:

> [!TIP]  
> This project supports multiple package managers (npm, yarn, pnpm), but **bun**
> is recommended for _blazingly fast_ installation and development experience.  
> Install it with: `curl -fsSL https://bun.sh/install | bash`

```bash
bun install
bun dev
```

## Project Structure

> [!NOTE]  
> That's just an overview for curious people.  
> I'm not a gatekeeper, willing to share my knowledge.

```
.
├── app/                # Next.js app router
│   ├── components/     # Shared UI components
│   ├── projects/       # Projects section
│   └── contact/        # Contact page
├── content/            # MDX content (projects, articles)
├── public/             # Static assets
└── util/               # Utility functions
```

---

<p align="center">
    <i>Made with ❤️ (and many coding sessions) in Saint Petersburg, Russia</i>
</p>
