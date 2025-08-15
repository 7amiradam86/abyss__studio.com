# Abyss Studio — Editorial Portfolio (Next.js + Tailwind)

Minimal, image-led portfolio structured like a refined architecture monograph.

## Dev
```bash
npm install
npm run dev
```
Visit http://localhost:3000

## Deploy (Free on Vercel)
1. Commit to a GitHub repo.
2. Go to https://vercel.com → New Project → Import your repo.
3. Framework Preset: **Next.js** (auto-detected). No special env vars.
4. Click **Deploy**. Your site will be live at a free `.vercel.app` URL.

## Customize
- Edit content in `lib/data.js`.
- Pages in `/app`: `page.js`, `projects/page.js`, `author/page.js`, `studio/page.js`, `contact/page.js`, `careers/page.js`, `news/page.js`.
- Global styles in `app/globals.css`.

## Notes
- Uses remote Unsplash images. Replace with your own in `lib/data.js` or `/public`.
- Neutral monochrome UI; let photographs carry color.
