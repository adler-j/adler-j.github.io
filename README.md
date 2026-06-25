# jonasadler.com

Source for [jonasadler.com](https://jonasadler.com), a [Hugo](https://gohugo.io) site
using the [Congo](https://github.com/jpanther/congo) theme (loaded as a Hugo Module).

## Local development

```sh
hugo server
```

Requires Hugo **extended** and Go (for Hugo Modules).

## Deployment

Pushes to `main` are built and published to GitHub Pages automatically via
`.github/workflows/hugo.yml`. The custom domain is set by `static/CNAME`.
