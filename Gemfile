source "https://rubygems.org"

gem "jekyll", "~> 4.4"

# Theme
gem "just-the-docs"

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-include-cache"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-github-metadata", ">= 2.15"
end

# Required for Ruby 3.x
gem "webrick", "~> 1.8"

# Windows only
platforms :mingw, :x64_mingw, :mswin do
  gem "tzinfo"
  gem "tzinfo-data"
end