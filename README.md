# hjoliveira.github.io

Install Ruby:

```sh
brew install rbenv ruby-build
rbenv install 3.2.2            # or the latest stable version
rbenv global 3.2.2
```

Add the following to `~/.profile`:

```sh
eval "$(rbenv init -)"
```

Finally:

```sh
gem install bundler jekyll
bundle exec jekyll serve
```

See https://jekyllrb.com/.
