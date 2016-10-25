# Jekyll Quick Starter template / scaffold (for use with [quikstart](https://github.com/quikstart))

## Features

* 2 columns
* sass boilerplate 1-7
* normalize v.5.0.0
* mobile first (flexbox)
* toggle aside without JS
* pagination
* sitemap

## Usage

Use like:

```
$ quik new sz-jekyll-flex
```

This will download and run the sz-jekyll-flex.rb quik starter script.

Resulting in:

```
sz-jekyll-flex
├── assets
│   └── css
│       └── style.scss
├── _includes
│   ├── aside
│   │   ├── nav.html
│   │   └── title.html
│   ├── pagination
│   │   ├── pages.html
│   │   └── posts.html
│   ├── burguer.html
│   ├── disqus_comments.html
│   ├── footer.html
│   ├── google-analytics.html
│   └── head.html
├── _layouts
│   ├── default.html
│   ├── page.html
│   └── post.html
├── _posts
│   ├── 2016-05-20-my-example-post.md
│   ├── 2016-05-20-super-long-article.md
│   ├── 2016-05-20-this-post-demonstrates-post-content-styles.md
│   ├── 2016-10-19-welcome-to-jekyll.markdown
│   └── 2016-10-25-small-post.md
├── _sass
│   ├── abstracts
│   │   ├── _functions.scss
│   │   ├── _mixins.scss
│   │   └── _variables.scss
│   ├── base
│   │   ├── _base.scss
│   │   ├── _fonts.scss
│   │   ├── _helpers.scss
│   │   └── _typography.scss
│   ├── components
│   │   ├── _button.scss
│   │   └── _icon.scss
│   ├── layout
│   │   └── _main.scss
│   ├── pages
│   │   └── _home.scss
│   ├── themes
│   │   └── _default.scss
│   ├── vendor
│   │   ├── _normalize.scss
│   │   └── _syntax-highlighting.scss
│   └── style.scss
├── _site
│   ├── about
│   │   └── index.html
│   ├── assets
│   │   └── css
│   │       └── style.css
│   ├── blog
│   │   ├── page2
│   │   │   └── index.html
│   │   └── posts
│   │       ├── my-example-post.html
│   │       ├── small-post.html
│   │       ├── super-long-article.html
│   │       ├── this-post-demonstrates-post-content-styles.html
│   │       └── welcome-to-jekyll.html
│   ├── feed.xml
│   ├── feed.xslt.xml
│   ├── index.html
│   └── sitemap.xml
├── about.md
├── _config.yml
├── Gemfile
├── Gemfile.lock
├── index.html
├── LICENSE.txt
└── README.md
```

That's it.
