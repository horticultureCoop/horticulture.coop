The [horticulture.coop](https://horticulture.coop) website.

This site is built with the [Hugo](https://gohugo.io) static site generator.
Currently, we are using the [Agency theme](http://themes.gohugo.io/agency/).

## Install

Install Hugo. For macOS, just

    brew install hugo

Then clone this repository.

## Build

    cd horticulture.coop
    hugo

To see all the options Hugo gives you,

    hugo --help

## Deploy

    deploy.sh

## Tour

For now, all of the site info is in `config.toml` at the project root.
Modifications to the theme are in `static/css` and `static/img`.
See `static/css/palette.css` for the working color palette.

Themes live in `themes`, and are checked out as git submodules.
