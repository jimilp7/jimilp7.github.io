source "https://rubygems.org"

gem "csv"
gem "logger"
gem "base64"
gem "bigdecimal"

gem "jekyll", "~> 4.3.2"
gem "minima", git: 'https://github.com/jekyll/minima'
gem "sass-embedded", "~> 1.69.5"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-sitemap", "~> 1.4"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby] 
gem "webrick", "~> 1.9"
