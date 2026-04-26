# Yan Wang's GitHub Homepage

Personal homepage for Yan Wang, built with Hugo and deployed through GitHub Pages.

## Local Development

Install Hugo `0.123.7` or a compatible extended version, then run:

```sh
hugo server --bind 127.0.0.1 --port 1313 --baseURL http://127.0.0.1:1313/
```

Build the production site with:

```sh
hugo --minify
```

The main homepage template lives in `layouts/index.html`, with styling in `static/css/home.css`.
