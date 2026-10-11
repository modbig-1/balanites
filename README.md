# Balanites Lounge Catalogue

Elegant digital catalogue for **Balanites Lounge** — featuring event posters, product tiles, brand partners, photo gallery, and reservation system.

## Live Demo

Once deployed on Vercel, your site will be available at:
`https://your-project-name.vercel.app`

## Project Structure

```
balanites-lounge/
├── index.html          # Main single-page application
├── catalogue_imgs/     # Catalogue product images (89 images)
├── gallery_imgs/       # Gallery photos
├── README.md
└── .gitignore
```

## Features

- Dark / Light theme toggle
- Interactive product catalogue with filters
- Event posters section
- Photo gallery
- Shopping cart (client-side)
- Reservation / booking UI
- Age gate
- Fully responsive design
- Smooth animations & modern UI

## Local Development

Simply open `index.html` in any modern browser, or use a local server:

```bash
# Using Python
python -m http.server 3000

# Using Node (if you have it)
npx serve .
```

Then visit `http://localhost:3000`

## Deploy to Vercel

### Option 1: GitHub + Vercel (Recommended)

1. Push this repository to GitHub
2. Go to [vercel.com](https://vercel.com) and sign in with GitHub
3. Click **Add New Project** → Import this repository
4. Leave settings as default and click **Deploy**

Every future `git push` will automatically redeploy the site.

### Option 2: Vercel CLI

```bash
npm i -g vercel
vercel
```

## Tech Stack

- Pure HTML / CSS / JavaScript (no build step required)
- Self-contained single page
- Optimized for static hosting (Vercel, Netlify, GitHub Pages, etc.)

## License

Private – All rights reserved © Balanites Lounge
