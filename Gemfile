source "https://rubygems.org"

# Specify your gem's dependencies in rubicure.gemspec
gemspec

if Gem::Version.create(RUBY_VERSION) < Gem::Version.create("2.3.0")
  gem "backport_dig"

  # i18n v1.5.1+ requires Ruby 2.3.0+
  gem "i18n", "< 1.5.1"
end
