source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#

# Specify Jekyll version
gem 'jekyll', '~> 4.3.2' # Use the latest stable version of Jekyll
gem 'webrick', '~> 1.7'  # Required for Ruby 3.x

# Add logger and csv to silence warnings
gem 'logger'
gem 'csv'
gem 'base64'

# If you have any plugins, put them here!
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem "sass-embedded", ">= 1.69.0"
group :jekyll_plugins do
    gem 'jekyll-feed'
    gem 'jekyll-sitemap'
    gem 'jekyll-paginate'
    gem 'jekyll-seo-tag'
    gem 'jekyll-archives'
    gem 'kramdown'
    gem 'rouge'
    gem "jekyll-redirect-from"
end