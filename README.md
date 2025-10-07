# Whiteprint

A portfolio website for Rati Dolidze showcasing commercial work, projects, and creative endeavors. Built with Astro and deployed on Cloudflare.

## About

Whiteprint is a minimalist portfolio website featuring:

- Commercial Work: Advertising campaigns and commercial projects
- Personal Projects: Creative and artistic endeavors
- Interactive Gallery: High-quality image galleries with hover effects
- Video Integration: Embedded videos from Vimeo, YouTube, and Facebook
- Responsive Design: Mobile-first approach with clean typography

## Tech Stack

- [Astro](https://astro.build/) - Modern static site generator
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Cloudflare](https://cloudflare.com/) - Hosting and CDN
- TypeScript - Type safety and better development experience

## Project Structure

```
/
├── public/
│   └── images/           # All portfolio images (48+ images)
├── src/
│   ├── components/
│   │   └── ProjectPage.astro    # Reusable project page component
│   ├── layouts/
│   │   └── Layout.astro         # Main site layout with navigation
│   ├── pages/
│   │   ├── index.astro         # Homepage with featured projects
│   │   ├── about.astro         # About page
│   │   ├── commercials.astro  # Commercial work gallery
│   │   ├── others.astro       # Other projects
│   │   └── projects/           # Individual project pages
│   │       ├── agribusiness.astro
│   │       ├── banksy.astro
│   │       ├── discover-gori.astro
│   │       ├── fullbright.astro
│   │       ├── ideatheka.astro
│   │       ├── jpg-culture-of-printing.astro
│   │       ├── man-and-space.astro
│   │       ├── now.astro
│   │       ├── optimo.astro
│   │       ├── stem-olympics.astro
│   │       └── thamar-de-letay.astro
│   └── styles/
│       └── global.css          # Global styles
├── astro.config.mjs           # Astro configuration
├── package.json               # Dependencies and scripts
└── tsconfig.json             # TypeScript configuration
```

## Development

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd whiteprint

# Install dependencies
npm install

# Start development server
npm run dev
```

### Available Scripts

| Command           | Action                   |
| ----------------- | ------------------------ |
| `npm run dev`     | Start development server |
| `npm run build`   | Build for production     |
| `npm run preview` | Preview production build |
| `npm run astro`   | Run Astro CLI commands   |

## Features

### Image Optimization

- All images are served from `/public/images/` for optimal performance
- Responsive image galleries with aspect ratio preservation
- Hover effects and smooth transitions

### Video Integration

- Support for Vimeo, YouTube, and Facebook video embeds
- Responsive video players with proper aspect ratios
- Optimized loading and performance

### Navigation

- Clean, minimalist navigation design
- Mobile-responsive hamburger menu
- Active page indicators

### Typography

- Custom font styling with proper hierarchy
- Uppercase tracking for headings
- Consistent spacing and readability

## Responsive Design

The website is fully responsive with:

- Mobile-first approach
- Breakpoints for tablet and desktop
- Optimized image galleries for all screen sizes
- Touch-friendly navigation

## Deployment

The site is configured for deployment on Cloudflare Pages:

1. Build Command: `npm run build`
2. Output Directory: `dist`
3. Node Version: 18+

### Environment Variables

No environment variables required for basic deployment.

## Image Management

All portfolio images are stored in `/public/images/` and referenced with absolute paths (`/images/filename.jpeg`). This ensures:

- Consistent loading across development and production
- Optimal performance on Cloudflare CDN
- Easy image management and updates

## Project Structure

Each project page includes:

- Title and Description: Detailed project information
- Image Gallery: High-quality project images
- Video Integration: Embedded videos when available
- Consistent Layout: Reusable `ProjectPage.astro` component

## Contact

For inquiries about projects or collaboration:

- Email: Nikolas@whiteprint.com
- Website: [whiteprint.com](https://whiteprint.com)

## License

This project is private and proprietary to Rati Dolidze/Whiteprint.

---

Built with Astro and deployed on Cloudflare
