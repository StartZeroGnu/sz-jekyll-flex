

# Jekyll 3.3 [Qk/Quik Start][qk] :zap: Starter template / scaffold

:crystal_ball: Live [preview (gh-pages)][demo]

## Features

* 2 columns
* sass boilerplate 1-7
* normalize v.5.0.0
* flexbox layout (mobile first)
* toggle aside without JS

## Usage

* **GH-Pages**

  Fork repo, remove master branch and customize `config.yml` +
  `/assets/css/style.scss` with your site settings.

* **QK/Quik**

  Install QK/Quik gem:

  ```
  ~ $ gem install quik
  ```

  Use like:

  ```
  ~ $ quik new sz-jekyll-flex
  ```

  This will download and run the [*sz-jekyll-flex.rb*][script] quik starter script:

  ```
  starting new Quik script {}; lets go
  Hello from the sz-jekyll-flex template
  Q: Name of the template? [blog]:
  ```

  Type your project name or push `intro` to use default name "blog":

  ```
  handle install_template StartZeroGnu/sz-jekyll-flex, {}
  ```

  Resulting in:

  ```
  <project-name>
  ├── assets
  │   └── css
  │       └── style.scss
  ├── _includes
  │   ├── burguer.html
  │   ├── disqus_comments.html
  │   ├── footer.html
  │   ├── google-analytics.html
  │   ├── head.html
  │   ├── nav.html
  │   └── title.html
  ├── _layouts
  │   ├── default.html
  │   ├── page.html
  │   └── post.html
  ├── _posts
  │   └── YYYY-MM-DD-my-example-post.md
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
  ├── _config.yml
  ├── .gitignore
  ├── about.md
  ├── Gemfile
  ├── index.html
  ├── LICENSE.txt
  └── README.md
  ```

  Now run Jekyll serve for a quick view:

  ```
  ~ $ bundle exec jekyll s
  ```

  Dance :musical_note: and celebrate :tada:

## Credits and Thanks :clap:

* [Qk/Quik Start][qk] by [Gerald Bauer][geraldb]
* [Sass boilerplate][sass-boilerplate] by [Hugo Giraudel][hugogiraudel]
* [Normalize][normalize] by [Nicolas Gallagher][necolas]
* [Jekyll][jekyll] by [Tom Preston-Werner][mojombo]
* [Minima][minima] by [Parker Moore][parkr]

## Contributing

[Bug reports][issues] and pull requests are welcome.

## License

[Script][script] Public domain license · Template [MIT][mit] license.

[qk]: https://github.com/quikstart
[demo]: https://startzerognu.github.io/sz-jekyll-flex
[script]: https://github.com/quikstart/scripts/blob/master/sz-jekyll-flex.rb
[geraldb]: https://github.com/geraldb
[sass-boilerplate]: https://github.com/HugoGiraudel/sass-boilerplate
[hugogiraudel]: https://github.com/HugoGiraudel
[normalize]: https://github.com/necolas/normalize.css
[necolas]: https://github.com/necolas
[jekyll]: http://jekyllrb.com
[mojombo]: https://github.com/mojombo
[minima]: https://github.com/jekyll/minima
[parkr]: https://github.com/parkr
[issues]: https://github.com/StartZeroGnu/sz-jekyll-flex/issues
[mit]: https://opensource.org/licenses/MIT
