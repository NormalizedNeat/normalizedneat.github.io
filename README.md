# Yinuo Meng - Academic Homepage

This site uses Jekyll and the AcadHomepage layout and is published with GitHub Pages.

## Editing

- Profile and sidebar links: `_config.yml`
- About: `_pages/includes/intro.md`
- News: `_pages/includes/news.md`
- Experience: `_pages/includes/experience.md`
- Education: `_pages/includes/education.md`
- Papers: `_pages/includes/papers.md`
- Homepage blog entry: `_pages/includes/blog.md`
- Full blog pages: `blog/`
- Homepage styles: `assets/css/main.scss`
- Blog styles: `assets/site.css`

## Local Preview

For a quick preview without installing Jekyll, open `index.html` directly. This
file is excluded from the GitHub Pages build; the deployed homepage is generated
from `_pages/about.md` and its included Markdown sections.

For live Markdown and SCSS updates, install Ruby, Bundler, and the project
dependencies, then run:

```bash
bundle install
./run_server.sh
```

The site will be available at `http://127.0.0.1:4000`.
