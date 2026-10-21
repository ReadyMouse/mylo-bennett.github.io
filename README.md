# mylo-bennett.github.io

Personal website for Mylo Bennett, built with Jekyll and served by GitHub Pages
at https://readymouse.github.io/mylo-bennett.github.io/.

Right now the site is a placeholder: the homepage redirects to
[linkedin.com/in/mylo-mbennett](https://www.linkedin.com/in/mylo-mbennett/).
The redirect target lives in the `linkedin` key in `_config.yml`.

## Local development

```sh
bundle install
bundle exec jekyll serve
```

Then open http://127.0.0.1:4000.

## Replacing the redirect with a real site

Delete the redirect markup in `index.html` and replace it with normal Jekyll
front matter plus content, e.g.

```
---
layout: home
title: Mylo Bennett
---
```

No theme is configured yet. Add one by setting `theme: minima` (or another
GitHub Pages supported theme) in `_config.yml`, or write your own layouts under
`_layouts/`.
