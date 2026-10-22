# erozak.github.io

GitHub Pages site for [erozak](https://github.com/erozak).

## Setup

- Published from the `master` branch via GitHub Pages.
- The custom domain is set by the [`CNAME`](../CNAME) file. Don't delete it, or the domain will be dropped on the next deploy.

## Status

No pages are published yet. This README lives in `.github/` on purpose: GitHub Pages would publish a root `README.md` as the site's home page, while Jekyll ignores dot-directories. GitHub still shows it on the repo page. Keep it here until a real site exists.

To publish a page, add an `index.html` (or a static site generator's output) at the repo root.

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## References

- [GitHub Pages documentation](https://docs.github.com/en/pages)
- [Managing a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)
