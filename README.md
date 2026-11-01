# skylands.ai

The landing page for [Skylands](https://github.com/skylands-ai/skylands): one
static page, no build step.

- `index.html` is the whole site. Styles and script are inline; the fonts
  come from Google Fonts.
- `favicon.svg` is the tab icon.
- `netlify.toml` tells Netlify to publish the repository root as it is.

## Publishing on Netlify

1. In Netlify, add a new site from this GitHub repository.
2. Leave the build command empty and the publish directory as `.`; the
   `netlify.toml` here sets both.
3. Every push to `main` deploys. Point the `skylands.ai` domain at the site
   from Netlify's domain settings.

To preview locally, open `index.html` in a browser, or run any static file
server in this directory.
