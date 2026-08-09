# David Dacruz — Engineering Field Notes

A dependency-free GitHub Pages site with original field notes on AI workflow operations, technical SEO, product engineering, and 42 campus launches.

## Local preview

```sh
python3 -m http.server 8080
```

Open `http://127.0.0.1:8080/`.

## Publishing

This repository is intended to be published as the GitHub user site `david-dacruz.github.io`. GitHub Pages should serve the `main` branch from the repository root.

The site links contextually to the canonical long-form material on [daviddacruz.dev](https://daviddacruz.dev/). It is designed as a useful standalone publication, not a redirect or doorway page.

Each indexable page includes a connected Schema.org JSON-LD graph. The homepage identifies the author, website, collection, note list, and visible FAQ. Every field note identifies its WebPage, TechArticle, breadcrumb trail, author relationship, subject matter, and visible FAQ. `llms.txt`, RSS, the XML sitemap, canonical links, and crawler directives provide complementary discovery paths.
