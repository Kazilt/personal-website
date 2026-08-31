source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# github-pages gem pins very old jekyll/liquid versions incompatible with
# modern Ruby (removed String#tainted?); GitHub Pages builds server-side
# with its own pinned versions regardless, so use plain jekyll locally.
# gem "github-pages", group: :jekyll_plugins

gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem 'tzinfo-data'
gem 'csv'
gem 'bigdecimal'
gem 'logger'
gem 'base64'
# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  gem 'jekyll-paginate'
  gem 'jekyll-gist'
  gem 'jekyll-redirect-from'
  gem 'kramdown-parser-gfm'
  gem 'hawkins'
  gem "webrick", "~> 1.8"
end
