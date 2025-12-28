# SvelteKit + bknd Blog

A full-featured blog application built with SvelteKit, Svelte and bknd backend.

## Features

- Posts & Pages with Admin Panel
- Comments with Moderation
- Anti-spam (honeypot + rate limiting)
- Authentication
- Dark Mode
- SEO, RSS, Sitemap

## Stack

- **SvelteKit** + **Svelte**
- **bknd** - backend (auth, database, API)
- **shadcn-svelte** + **Tailwind CSS**
- **Turso / libsql** - database

## Quick Start

```bash
bun install
npx bknd sync
bun run copy-assets
bun run dev
```

- Blog: http://localhost:5173
- Admin: http://localhost:5173/admin

## Warnings

> **Early Adopter Stack** - bknd 0.20.0-rc.2

> **Experimental** - SvelteKit remote functions, Svelte 5 async

> **Node.js 22.13+** required

## License

MIT
