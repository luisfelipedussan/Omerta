# Luis Felipe Dussán - Personal Website

## Deploy

### Option 1: GitHub Pages (Free)

1. Push to GitHub
2. Enable GitHub Pages in repo Settings → Pages → Source: "Deploy from a branch" → gh-pages
3. Workflow will auto-deploy on push to main

### Option 2: Netlify (Free + Custom Domain)

1. Push to GitHub
2. Go to [netlify.com](https://netlify.com)
3. "Add new site" → "Import from Git"
4. Select this repo
5. Build command: `npm run build`
6. Publish directory: `dist/felipe-web`
7. Add custom domain in Site Settings

### Option 3: Vercel (Free + Custom Domain)

1. Push to GitHub
2. Go to [vercel.com](https://vercel.com)
3. "New Project" → Import from GitHub
4. Select this repo
5. Framework: Angular (or Other)
6. Deploy

## Local Development

```bash
npm install
npm start
```

## Build

```bash
npm run build
```
