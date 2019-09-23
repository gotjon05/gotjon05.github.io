source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# gem "github-pages", group: :jekyll_plugins

# To upgrade, run `bundle update`.

#A simple Ruby Gem to bootstrap dependencies for setting up and maintaining a local Jekyll environment in sync with GitHub Pages.
gem "github-pages", group: :jekyll_plugins
#time zone: https://github.com/tzinfo/tzinfo-data
gem "tzinfo-data"
#auto-regeneration feature that watches your source folder for changes and then re-builds your site. 
gem "wdm", "~> 0.1.0" if Gem.win_platform?



gem "jekyll"
gem "minimal-mistakes-jekyll"

# The following plugins are automatically loaded by the theme-gem:
#   gem "jekyll-paginate"
#   gem "jekyll-sitemap"
#   gem "jekyll-gist"
#   gem "jekyll-feed"
#   gem "jekyll-include-cache"
#
# ------------------------------------------ If you have any other plugins, put them here! -------------------------------------------
group :jekyll_plugins do
#makes site available for webcrawling: https://github.com/jekyll/jekyll-sitemap
  gem "jekyll-sitemap"
#Liquid tag for displaying GitHub Gists in Jekyll sites: {% gist %}: https://github.com/jekyll/jekyll-gist
  gem "jekyll-gist"
#Atom (RSS-like) feed of your Jekyll posts https://github.com/jekyll/jekyll-feed
  gem "jekyll-feed"
#GitHub-flavored Emoji plugin for Jekyll https://github.com/jekyll/jemoji
  gem "jemoji"
#A Jekyll plugin to cache the rendering of Liquid includes https://github.com/benbalter/jekyll-include-cache
  gem "jekyll-include-cache"
#Add fast and relevant search to your Jekyll site.  https://github.com/algolia/jekyll-algolia
  gem "jekyll-algolia"
end

