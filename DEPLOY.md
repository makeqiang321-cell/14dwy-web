# 14 Days With You — Deployment Checklist

## Before uploading, replace ALL instances of:
- `YOUR-DOMAIN.com` → your actual domain

### Files to update:
- `index.html` — canonical, og:url, og:image, JSON-LD image
- `robots.txt` — Sitemap URL
- `sitemap.xml` — All URLs

## Upload everything in this folder to your web server root.

## Folder structure:
```
/
├── index.html          Landing page
├── favicon.svg         Site icon (red heart)
├── robots.txt          Crawler rules
├── sitemap.xml         SEO sitemap
├── netlify.toml        Netlify config (upload if using Netlify)
├── images/14dwy/       Screenshots & header (12 files)
└── 14dwy-web/          Game files (7 files, 137 MB)
```

## Important notes:
- The game requires a web server — cannot run from `file://`
- `14dwy-web/game.zip` is 119 MB, ensure your host allows large files
- For best performance, enable Cloudflare CDN or similar
