# LandedClean - Static Landing Page

A pure static HTML landing page for showcasing AI.com domain names with a premium lava video background.

## Structure

```
/
├── index.html              # Main landing page
├── backgrounds/
│   └── lava.mp4           # Background video
└── README.md              # This file
```

## Vercel Deployment

This is a pure static site with no build process required.

### Vercel Project Settings

1. **Framework Preset**: Other
2. **Build Command**: (leave empty)
3. **Output Directory**: (leave empty)
4. **Install Command**: (leave empty)

### Deploy

Push to your connected Git repository and Vercel will automatically deploy.

The site will be served directly from the repository root, with `index.html` as the homepage.

## Local Development

Simply open `index.html` in a browser, or use any static file server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
```

## Customization

Edit the `names` array in the `<script>` section of `index.html` to update the AI.com domain list.
