# jbeck-blog
Professional software engineering blog at https://jbeck.me, built with Astro.

## Requirements
- Node.js 22.23.4 or newer (see `engines` in `package.json`)

## Local Development
- `npm install` installs dependencies
- `npm run dev` starts the dev server at http://localhost:4321
- `npm run build` builds the static site into `dist/`
- `npm run preview` serves the built site locally

## Content
- Posts live in `src/content/blog/` as Markdown or MDX
- The file name is the URL slug, in kebab-case: `my-post.md` becomes `/blog/my-post`
- Frontmatter: `title`, `description`, `pubDate`, `updatedDate` (optional), `heroImage` (optional)
