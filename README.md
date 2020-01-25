# Wedding

## Setup

[Hugo Quick Start](https://gohugo.io/getting-started/quick-start/)

[Hosting on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/#github-user-or-organization-pages)

`git submodule add -b master git@github.com:karolina-bartek/karolina-bartek.github.io.git public`

### Common Problems

[Unable to build the site using the theme](https://github.com/alex-shpak/hugo-book/issues/19)
Install [hugo_extended](https://github.com/gohugoio/hugo/releases)

## Release

`hugo --minify -D`

This will generate code to `public/` directory which is the root of `karolina-bartek.github.io` repository.

## Development

`hugo server --minify`
