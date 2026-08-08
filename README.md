# QR-Code

Strict Version 1 (21×21) QR code generator, alphanumeric-optimized.

Single-file static app (`index.html`) — no build step required. The QR
generation library is embedded directly in the page (built from the
`qrcode` npm package's source), so it has no runtime dependency on any
external QR-code CDN. Tailwind CSS is still loaded from its CDN for styling.

## Run locally

Just open `index.html` in a browser, or serve the folder with any static
file server:

```bash
npx serve .
```

## Deploy

This is a zero-config static site — deploy as-is on Vercel, Netlify, GitHub
Pages, or any static host.
