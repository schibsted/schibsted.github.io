# [schibsted.github.io](schibsted.github.io) [![Build Status](https://travis-ci.org/schibsted/schibsted.github.io.svg)](https://travis-ci.org/schibsted/schibsted.github.io)

Developers at Schibsted blogging about tech.
You can also find us on Twitter [@SchibstedEng](https://twitter.com/SchibstedEng).

## Quick start

We are testing Jekyll. Read more about it [here](http://jekyllrb.com/).
You need Ruby to run the project. It will work out of the box on Mac.
If you are on another platform check out the [installation](http://jekyllrb.com/docs/installation/).

```sh
$ gem install bundler # only needed once
$ bundle install
$ bundle exec jekyll serve -w
```

Open <http://localhost:4000> in your browser, and voilà.

If you want to preview drafts run with the '--drafts' flag

## Want to write a post or help
Check out [CONTRIBUTING](CONTRIBUTING.md).

## Testing
If you want to test locally run

```bash
bundle exec htmlproof ./_site
```