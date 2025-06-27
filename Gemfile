source "https://rubygems.org"

# ruby RUBY_VERSION # Not specifying Ruby version for now, can be added if needed

gem "jekyll", "~> 3.8.5" # As per original Forty theme
gem "jekyll-feed", "~> 0.12"
gem "jekyll-gist", "~> 1.5"
gem "jekyll-paginate", "~> 1.1"
gem "jekyll-seo-tag", "~> 2.6"
gem "jekyll-sitemap", "~> 1.2"

# Theme-specific plugins (from original theme)
group :jekyll_plugins do
  gem "jekyll-autoprefixer"
  # gem "jekyll-brotli" # Brotli might require extra setup, keeping it simple for now
  gem "jekyll-environment-variables"
  gem "jekyll-minifier"
  gem "jemoji"
end

# Windows-specific gems from original theme (good for broad compatibility)
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem "wdm", "~> 0.1.0", platforms: [:mingw, :mswin, :x64_mingw]

# Other gems from original
# gem "maxmind-db" # Likely not needed for a simple book page
gem "rake"

# Note: Some gems from the original (html-proofer, jekyll-gzip, jekyll-offline, workbox2-jekyll-plugin)
# were commented out or noted as unmaintained in the original Gemfile's comments or are build tools.
# I've kept this Gemfile focused on what's needed to serve/build the theme.
# The user should refer to the original theme's Gemfile if they encounter issues or need full features.

gem "csv", "~> 3.3"

gem "base64", "~> 0.3.0"

gem "bigdecimal", "~> 3.2"
