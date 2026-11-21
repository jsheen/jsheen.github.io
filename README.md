# jsheen.github.io

Personal blog of Justin Sheen, built with Jekyll and served by GitHub Pages.

## Writing a post

1. Add a file to `_posts/` named `YYYY-MM-DD-title-with-dashes.md`.
2. Start it with:

   ```
   ---
   layout: post
   title: "Your title"
   tags: [causal-inference]
   math: true   # optional, enables LaTeX via MathJax
   ---
   ```
3. Write in Markdown below that, commit, and push. The site rebuilds in about a minute.

Images (e.g. cartoons) go in `assets/img/` and are embedded with `![caption](/assets/img/file.png)`.

## Structure

- `index.html`: blog home (post list)
- `about.md`: About page
- `_layouts/`: page templates
- `assets/css/style.css`: styling
- `_config.yml`: site settings and links
