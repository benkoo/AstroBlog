# Astro Blog Project

A blog website built with Astro, featuring a responsive layout, navigation, and blog post functionality.

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Footer.astro
│   │   ├── Hamburger.astro
│   │   ├── Header.astro
│   │   ├── Navigation.astro
│   │   └── Social.astro
│   ├── layouts/
│   │   ├── BaseLayout.astro
│   │   └── MarkdownPostLayout.astro
│   ├── pages/
│   │   ├── about.astro
│   │   ├── blog.astro
│   │   ├── index.astro
│   │   └── posts/
│   ├── scripts/
│   │   └── menu.js
│   └── styles/
│       └── global.css
└── package.json
```

### Key Features

- **Layouts**: Reusable page layouts with `BaseLayout.astro` and `MarkdownPostLayout.astro`
- **Components**: Modular components for Header, Footer, Navigation, and Social links
- **Responsive Design**: Mobile-friendly navigation with hamburger menu
- **Blog Support**: Dedicated blog section with markdown post support
- **Styling**: Global CSS and component-specific styles

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [Astro documentation](https://docs.astro.build) or join the [Astro Discord server](https://astro.build/chat).
