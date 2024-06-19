source "https://rubygems.org"
#
# Welcome to LYDDE Group Website system
# Version : 1.0.0
#
# To install & execute this website run:
#     bundle exec jekyll serve

# Define Jekyll version requested
gem "jekyll"

# This is the default theme for our Jekyll sites.
gem "jekyll-theme-lydde"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-github-metadata"
  gem "jekyll-relative-links"
  gem "jekyll-redirect-from"
  gem "jekyll-remote-theme"
  gem "faraday-retry"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]