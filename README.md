# Neil McClelland's Blog

Welcome to the source code of my personal blog! This is where I share my thoughts on frontend engineering, web development, and building great user experiences. Built with Next.js and Nextra, it's designed to be fast, accessible, and easy to maintain.

## Live Website

Check out the live version here: [https://neil-mcclelland.com/](https://neil-mcclelland.com/)

## Features

- **Fast & Responsive:** Built with Next.js for optimal performance on all devices
- **Blog Posts:** Technical writing on frontend development, best practices, and engineering philosophy
- **MDX Support:** Write content in Markdown with React components
- **RSS Feed:** Auto-generated RSS feed for blog subscribers
- **Dark Mode Ready:** Clean, modern design with excellent readability

## Technologies Used

- **[Next.js](https://nextjs.org/)** – React framework for production
- **[Nextra](https://nextra.site/)** – Blog theme built on Next.js
- **TypeScript** – Type-safe JavaScript
- **MDX** – Markdown with JSX components
- **RSS** – Auto-generated feed for posts
- **Vercel** – Deployment platform

## Setup and Installation

To run this blog locally, follow these steps:

1. **Clone the repository**
```bash
git clone https://github.com/neil-mcc/blog.git
cd blog
```

2. **Install dependencies**
```bash
npm install
```

3. **Start the development server**
```bash
npm run dev
```

Your blog should now be running on [http://localhost:3000](http://localhost:3000).

4. **Build for production**
```bash
npm run build
npm start
```

## Project Structure

```
my-blog/
├── pages/
│   ├── posts/           # Blog posts (MDX/MD files)
│   ├── _app.tsx         # Custom App component
│   ├── _document.tsx    # Custom Document
│   └── index.mdx        # Home page
├── public/
│   ├── images/          # Static images
│   └── feed.xml         # Auto-generated RSS feed
├── scripts/
│   └── gen-rss.js       # RSS feed generator
├── styles/
│   └── main.css         # Global styles
├── theme.config.js      # Nextra theme configuration
└── next.config.js       # Next.js configuration
```

## Writing a New Blog Post

1. Create a new `.md` or `.mdx` file in `pages/posts/`
2. Add frontmatter with metadata:
```markdown
---
title: Your Post Title
date: 2025/10/24
description: A brief description of your post
tag: frontend development
author: Neil McClelland
---

# Your Post Title

Your content here...
```

3. The post will automatically appear in your blog's post listing
4. Build the project to regenerate the RSS feed

## RSS Feed

The RSS feed is automatically generated during the build process. It includes all blog posts with their titles, descriptions, dates, and tags.

## Contact

- **Email:** neilmcclelland1@gmail.com
- **LinkedIn:** [neil-mcclelland-118a06107](https://www.linkedin.com/in/neil-mcclelland-118a06107/)
- **GitHub:** [@neil-mcc](https://github.com/neil-mcc)
- **X (Twitter):** [@NeilMcclel5056](https://x.com/NeilMcclel5056)

## License

This project is open source and available for reference. Feel free to fork and adapt for your own blog!