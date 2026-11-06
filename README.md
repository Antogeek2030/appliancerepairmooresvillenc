# Appliance Repair Mooresville NC

Production-ready Astro website for a local appliance repair business.

## Tech Stack
- Astro 7
- Tailwind CSS 4 (via @tailwindcss/vite)
- @astrojs/sitemap
- Web3Forms for contact form

## Development
```bash
npm install
npm run dev
```

## Build (Cloudflare Pages)
```bash
npm run build
```
Output: `dist/`

### Cloudflare Pages Settings
- Build command: `npm run build`
- Build output directory: `dist`
- Node version: 22 or higher

## Contact Form
Replace `YOUR_WEB3FORMS_ACCESS_KEY` in `src/pages/contact.astro` with your Web3Forms access key from https://web3forms.com

## Project Structure
- `src/pages/` — routes
- `src/components/` — Header, Footer, Seo
- `src/layouts/` — BaseLayout
- `src/data/site.ts` — business data, services, areas
- `public/` — robots.txt, llms.txt, favicon
