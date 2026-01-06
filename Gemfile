source "https://rubygems.org"

# Core Jekyll version
gem "jekyll", "~> 4.4.1"

# Default theme
gem "minima", "~> 2.5"

# WEBrick is required for Ruby 3.x
gem "webrick"

# If you want to use GitHub Pages, remove the "gem 'jekyll'" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby do not include zoneinfo files, so bundle the tzinfo-data gem
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb gem to v0.6.x on JRuby builds
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

