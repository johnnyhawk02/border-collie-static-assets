# Border Collie World Static Assets

This repository contains static assets (images, etc.) for the Border Collie World website.

## Directory Structure

- `/images` - Optimized images in WebP format

## Usage

These assets are meant to be served from a static asset host (subdomain) such as `assets.bordercollie.world` or similar.

In the main application, reference these assets using the full URL:

```jsx
<Image 
  src="https://assets.bordercollie.world/images/beach-day.webp"
  alt="Beach Day" 
  width={800} 
  height={600}
/>
```

## Benefits

- Reduced main application bundle size
- Better caching for static assets
- Avoids Cloudflare Pages file size limits 