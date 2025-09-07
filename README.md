# Gatsby Creative Portfolio

[![Gatsby](https://img.shields.io/badge/Gatsby-663399?style=for-the-badge&logo=gatsby&logoColor=white)](https://www.gatsbyjs.org/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![DatoCMS](https://img.shields.io/badge/DatoCMS-FF7751?style=for-the-badge&logo=datocms&logoColor=white)](https://www.datocms.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

A modern portfolio website built with Gatsby and DatoCMS. Features responsive design, image optimization, and content management.

**[Live Demo](https://cranky-edison-12166d.netlify.com/)** | **[Documentation](https://www.datocms.com/docs/static-generators/gatsbyjs)**

## Features

- Responsive design with smooth animations
- Static site generation for optimal performance
- SEO optimized with React Helmet
- Image optimization and lazy loading
- Content management through DatoCMS
- Interactive components (masonry layouts, carousels)
- Sass styling with modular architecture

## Tech Stack

- **Gatsby** - Static site generator
- **React** - UI library
- **DatoCMS** - Headless CMS
- **Sass** - CSS preprocessor
- **React Slick** - Carousel component
- **React Masonry** - Masonry layout

## Quick Start

### Prerequisites
- Node.js (v14+)
- Yarn
- DatoCMS account ([sign up](https://dashboard.datocms.com/signup))

### Setup

1. **Clone and install:**
```bash
git clone https://github.com/your-username/gatsby-portfolio.git
cd gatsby-portfolio
yarn install
```

2. **Set up DatoCMS:**
   - [Deploy with DatoCMS](https://dashboard.datocms.com/projects/new-from-template/static-website/gatsby-portfolio) (recommended)
   - Or manually: Create project → Copy API token → Add to `.env`:
```bash
echo 'DATO_API_TOKEN=your_token_here' >> .env
```

3. **Start development:**
```bash
yarn develop
```

## Scripts

```bash
yarn develop    # Start development server
yarn build      # Build for production
yarn format     # Format code with Prettier
```

## Project Structure

```
src/
├── components/     # React components
├── pages/         # Gatsby pages (auto-routed)
├── styles/        # Sass stylesheets
└── templates/     # Page templates
```

## Deployment

Deploy to any static hosting service:
- **Netlify** - Connect GitHub repo
- **Vercel** - Zero-config deployment
- **GitHub Pages** - Use GitHub Actions
