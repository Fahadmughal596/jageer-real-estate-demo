# Jageer Real Estate & Marketing — Independent Website Concept

A responsive React/Vite design concept for pitching a website to the Gujranwala business.

## IMPORTANT
This is an UNOFFICIAL demonstration, not a website endorsed by or affiliated with Jageer Real Estate & Marketing. Property listing names, images, bedroom counts and descriptions are sample concepts, not actual inventory. The provided business phone number and office address are public listing details; verify with the business before any official use.

## Run locally
Install Node.js 20.19+ or 22.12+.

```bash
npm install
npm run dev
```

Open the localhost URL shown by Vite.

## Deploy on Vercel (quickest)
1. Extract the ZIP.
2. Create a new GitHub repository and upload the project contents (not the outer ZIP).
3. In Vercel choose Add New > Project > Import Git Repository.
4. Framework preset: Vite. Build command: `npm run build`. Output directory: `dist`.
5. Deploy. The site is a static frontend, no database required.

Alternative: use Vercel CLI after `npm install`: `npx vercel`.

## Features
- Premium responsive landing page
- Search by property type, area, and keywords
- Interactive conceptual property cards and saved heart toggles
- Property detail modal
- Gujranwala neighborhood selectors
- Click-to-call, WhatsApp inquiry, Maps links
- Clear unofficial demo disclaimer and sample-property labels

## Customization
- Contact number: `CONTACT` near top of `src/main.jsx`
- Property objects: `properties` array in `src/main.jsx`
- Images: `assets` in `src/main.jsx`; currently remotely served stock-like images from Unsplash and require internet.
- Colors/styles: `src/style.css`
- Branding & SEO: `index.html`

## Before selling/publishing an official website
Get permission for brand usage, use real authorized property photographs and verified details, agree on an actual property data update workflow, and confirm property availability and fees. Avoid representing this demo as officially operated by the business.
