# Emmanuelle Lejeail - Personal Portfolio & Blog

A personal portfolio and blog built with Astro, Tailwind CSS, and TypeScript. This site showcases my professional experience, technical writing, and thoughts on AI security and software engineering.

## 🚀 Live Site

Visit the live site at: [your-domain.com] (update with your actual domain)

## 📌 Features

- 🏠 Personal portfolio homepage
- 👤 About Me section with professional experience
- 📝 Blog functionality with categories and tags
- 📄 Publications/Writing section
- 🔍 Search functionality
- 🌑 Dark mode support
- 📱 Fully responsive design
- 💬 Disqus comments on blog posts
- 🔳 Syntax highlighting for code blocks

## 🛠️ Tech Stack

- **Framework:** Astro 5.15+
- **Styling:** Tailwind CSS 4+
- **Language:** TypeScript
- **Content:** Markdown/MDX
- **Deployment:** Ready for Netlify/Vercel

## 📄 Site Structure

- 🏠 **Homepage** - Personal introduction and tech stack showcase
- 👤 **About Me** - Professional experience, skills, and education
- 📝 **Blog** - Technical articles and thoughts
- 📄 **Writing** - Published articles and publications
- 📞 **Contact** - Get in touch
- 🏷️ **Categories/Tags** - Organized content discovery
- 🔍 **Search** - Site-wide content search

## 🚀 Getting Started

### Prerequisites

- Node.js v20.10+
- Yarn v1.22+

### Installation

```bash
# Clone the repository
git clone https://github.com/emmlejeail/portfolio-blog.git

# Navigate to the project directory
cd portfolio-blog

# Install dependencies
yarn install
```

### Development

```bash
# Start the development server
yarn run dev
```

The site will be available at `http://localhost:4321`

### Build for Production

```bash
# Build the site
yarn run build

# Preview the build
yarn run preview
```

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
├── content/            # Markdown content
│   ├── blog/           # Blog posts
│   ├── about/          # About page content
│   ├── contact/        # Contact page content
│   └── publications/   # Publications content
├── layouts/            # Page layouts and partials
├── pages/              # Astro pages and API routes
├── styles/             # Global CSS and Tailwind config
└── config/             # Site configuration files
```

## 🎨 Customization

### Site Configuration

Update `src/config/config.json` with your personal information:

```json
{
  "site": {
    "title": "Your Name",
    "base_url": "https://your-domain.com",
    "description": "Your site description"
  },
  "metadata": {
    "author": "Your Name"
  }
}
```

### Navigation

Modify the navigation menu in `src/config/menu.json`.

### Styling

The site uses Tailwind CSS with a custom color scheme. Modify `src/styles/theme.json` to customize colors and theme settings.

## 📝 Adding Content

### Blog Posts

Create new blog posts in `src/content/blog/` using Markdown or MDX format:

```markdown
---
title: "Your Post Title"
description: "Post description"
date: 2025-01-01
categories: ["Technology"]
tags: ["astro", "web-development"]
---

Your content here...
```

### Publications

Add publications to `src/content/publications/` or update the data directly in `src/pages/publications.astro`.

## 🚀 Deployment

The site is configured for easy deployment to various platforms:

### Netlify

1. Connect your GitHub repository to Netlify
2. Use these build settings:
   - Build command: `yarn run build`
   - Publish directory: `dist`

### Vercel

1. Import your GitHub repository
2. Vercel will automatically detect Astro and configure build settings

## 📧 Contact

- **Email:** emmanuelle.lejeail@gmail.com
- **LinkedIn:** [emmanuelle-lejeail](https://www.linkedin.com/in/emmanuelle-lejeail/)
- **GitHub:** [emmlejeail](https://github.com/emmlejeail)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ using Astro, Tailwind CSS, and TypeScript.