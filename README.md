<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-confd/brand/main/social/go-ruby-confd.png" alt="go-ruby-confd/go-ruby-confd.github.io" width="720"></p>

# go-ruby-confd.github.io

The organization's institutional landing page, served at
<https://go-ruby-confd.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-confd/docs](https://github.com/go-ruby-confd/docs), served at
<https://go-ruby-confd.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
