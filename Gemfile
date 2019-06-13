source "https://rubygems.org"

# hello! this is where you manage which jekyll version is used to run.
# when you want to use a different version, change it below, save the
# file and run `bundle install`. run jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# this will help ensure the proper jekyll version is running.
# happy jekylling!

gem 'github-pages', group: :jekyll_plugins

# if you want to use jekyll native, uncomment the line below.
# to upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?

#for jekyll-scholar
gem "citeproc-ruby"
gem "csl-styles"
gem "rake"
gem "rouge"
gem "jekyll"
gem "minimal-mistakes-jekyll"

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  # gem 'jekyll-sitemap'
  # gem 'hawkins'
  gem "jekyll-scholar"
  gem 'unicode_utils', require: false unless RUBY_VERSION >= '2.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

