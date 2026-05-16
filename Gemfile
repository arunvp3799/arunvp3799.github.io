source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "minimal-mistakes-jekyll"

group :jekyll_plugins do
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-gist"
  gem "jekyll-feed"
  gem "jekyll-include-cache"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?
gem "http_parser.rb", "~> 0.6.0", :install_if => Gem.win_platform?
