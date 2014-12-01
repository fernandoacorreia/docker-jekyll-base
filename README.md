# docker-jekyll-base

Minimalist Jekyll installation.

Project URL: https://github.com/fernandoacorreia/docker-jekyll-base

Repository URL: https://registry.hub.docker.com/u/fernandoacorreia/docker-jekyll-base/

## Purpose

Provides a minimal Jekyll installation that assumes nothing and can be used as base for other,
more specific images.

## Contents

* Debian Wheezy
* Ruby 1.9.3
* Node.js 0.10.33
* Jekyll 2.5.2

## Usage

```
$ alias jekyll='docker run --rm -v "$PWD:/src" -p 4000:4000 fernandoacorreia/docker-jekyll-base'
$ jekyll build
$ jekyll serve
```
