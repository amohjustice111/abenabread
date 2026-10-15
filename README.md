# Sister Abena Paano Tea Bread

A responsive Next.js bakery website for Sister Abena Paano Tea Bread in Sefwi Elluokrom, Western North Region, Ghana.

## Features
- Mobile-friendly bakery homepage
- Temporary bread photo (replace with the owner's photo when available)
- WhatsApp order links for +233 594 842 730
- Google Maps link supplied by the bakery: https://maps.app.goo.gl/kMGcnmHuSaQVdSkR9
- Bakery address and nearby landmarks
- SEO metadata

## Run locally
Requires Node.js 20.9 or newer.

```bash
npm install
npm run dev
```
Open http://localhost:3000.

## Deploy to Vercel
Import this repository in Vercel and keep the default Next.js settings. No environment variables are required for the current version.

## Add the real bakery photo later
Replace the temporary remote image URL in `app/page.js` with `/bakery-photo.jpg`, then add the real photo to the `public` folder with that filename.
