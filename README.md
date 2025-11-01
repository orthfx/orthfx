# orthfx

The official website for orthfx, an organization dedicated to building Orthodox Christian digital tools and resources.

This site is built with **Next.js** and [Nextra](https://nextra.vercel.app/), featuring:

- Automatically configured to handle Markdown/MDX
- Generates an RSS feed based on posts
- A beautiful theme included out of the box
- Easily categorize posts with tags
- Fast, optimized web font loading

## About orthfx

orthfx develops open-source applications that help people engage with scripture, prayer, and Orthodox Christian content. Our projects range from Bible reading apps and Discord bots to multi-tenant platforms and subscription services, all built with modern web technologies like Next.js, React, and TypeScript.

## Projects

This website showcases five main projects:

1. **Orthodox Reader** - A mobile-first Bible reading PWA with continuous scroll and audio narration
2. **Orthodox NKJV** - A Node.js module with the complete NKJV Bible text in multiple formats
3. **Pledge** - A subscription payments starter kit for SaaS applications
4. **Orthobot** - A Discord bot that posts Bible passages when referenced
5. **Sites** - A multi-tenant platform starter kit with custom domain support

## Development

Install dependencies:

```bash
npm install
# or
yarn
```

Run the development server:

```bash
npm run dev
# or
yarn dev
```

Visit `http://localhost:3000` to view the site.

## Build

```bash
npm run build
# or
yarn build
```

## Configuration

1. Update organization info in `theme.config.js`
2. Update site URL for the RSS feed in `scripts/gen-rss.js`
3. Update meta tags in `pages/_document.js`
4. Update posts inside `pages/posts/*.md` with your content

## Deploy

Deploy with [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

## Contact

- GitHub: [ortho-fox](https://github.com/ortho-fox)
- Email: orthofox@proton.me

## License

MIT
