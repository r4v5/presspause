# Developing locally

You need ruby, probably version 2.5-ish, and a newish version of Bundler.
(If `bundle install` complains that it doesn't know what bundler is, `gem install bundler` first.)
`bundle install` within the repository should create a `vendor/` directory with all the stuff jekyll needs to make pages.
Now you can run `bundle exec jekyll serve` and any changes to things other than `_config.yaml` will be auto-reloaded.

# Publishing

Publishing happens on push to master.
