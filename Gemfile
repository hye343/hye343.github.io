source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "jekyll-remote-theme"
gem "jekyll-feed"
gem "jekyll-sitemap"
gem "jekyll-paginate"

# Windows/JRuby 환경에서 타임존 데이터가 필요할 수 있음
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?
