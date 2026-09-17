# Lab Record Generator

A single-page, client-side tool that collects lab record details through a
step-by-step form and exports:

- A formatted Word (`.docx`) document — built in the browser, no server involved.
- Per-page pictures (`.png`, zipped) of the finished document.

Nothing is uploaded anywhere; everything runs locally in the browser.

## Deploy

This is a static site — one `index.html` file. Any static host works
(Vercel, Netlify, GitHub Pages). No build step is required.
