source "https://rubygems.org"

# Github Pages用のJekyll設定
gem "github-pages", group: :jekyll_plugins

# Windows用設定
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# Jekyll plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
end

# Ruby 3.0以降での互換性
gem "webrick", "~> 1.7" 