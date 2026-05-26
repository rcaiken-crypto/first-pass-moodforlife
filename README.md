# Mood for Life — Astro/Vercel Starter Site

This is a starter static site for moodforlife.com using Astro. It is designed to be simple to maintain: pages are mostly `.astro` files and essays/books can be added as Markdown files later.

## Local preview

```bash
npm install
npm run dev
```

Then open the local URL shown in the terminal.

## Build

```bash
npm run build
```

## Deploy to Vercel

1. Create a new GitHub repository.
2. Upload this folder's contents to that repository.
3. In Vercel, choose **Add New Project**.
4. Import the GitHub repository.
5. Vercel should detect Astro automatically.
6. Build command: `npm run build`
7. Output directory: `dist`
8. After previewing, connect the domain `moodforlife.com` in Vercel.

## Images

Place images in:

```text
public/images/
```

Then reference them as:

```html
<img src="/images/your-image.jpg" alt="Description" />
```

Suggested files to add later:

- `/public/images/richard-aiken.jpg`
- `/public/images/clinical-presence-cover.jpg`
- `/public/images/mood-for-life-diagram.jpg`
- `/public/images/book-covers/` if you want a separate folder

## Hidden technical section

The page at `/technical/math-in-psychiatry/` is intentionally not listed in the main navigation and includes a `noindex` tag.
