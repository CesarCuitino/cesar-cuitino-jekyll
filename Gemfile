source "https://rubygems.org"

# Si usas GitHub Pages, usar "github-pages"
gem "github-pages", group: :jekyll_plugins

# Este es el tema por defecto
gem "jekyll-theme-cayman"

# Plugins de Jekyll
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Soporte para Windows y JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Mejora de rendimiento en Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Compatibilidad con JRuby
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
