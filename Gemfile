source "https://rubygems.org"

# Use latest stable Jekyll 4.x
gem "jekyll", "~> 4.4"
gem "jekyll-sitemap"
gem "jekyll-seo-tag"

# Plugins
group :jekyll_plugins do
#   gem "jekyll-paginate-v2", "~> 3.0"
  gem 'jekyll-paginate-v2', git: 'https://github.com/mohkale/jekyll-paginate-v2.git', branch: 'liquid-cache-bypass'
end
# gem 'jekyll-paginate-v2', git: 'https://github.com/mohkale/jekyll-paginate-v2.git', branch: 'liquid-cache-bypass'

# Required for Ruby 3.4+ compatibility
# Jekyll 4.4+ has some of these as dependencies, but explicit inclusion
# ensures stability with older plugins like jekyll-paginate-v2.
gem "webrick"
gem "csv"
gem "base64"
gem "logger"
