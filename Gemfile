source "https://rubygems.org"

# Happy Jekylling!
gem "jekyll", "~> 4.2.0"

# Default theme for new Jekyll sites.
gem "minima", "~> 2.0"

# If you want to use GitHub Pages, remove the above jekyll gem and uncomment the line below.
# gem "github-pages", group: :jekyll_plugins

# Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-sitemap"
end

# Additional dependencies
gem "rexml"
gem "pathutil", "~> 0.16.1"
gem "webrick"    # <-- Add this line

# Windows-specific gems (if applicable)
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance booster for Windows
gem "wdm", "~> 0.1.0", install_if: Gem.win_platform?

