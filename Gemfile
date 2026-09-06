source 'https://rubygems.org'

# Specify your gem's dependencies in trailblazer.gemspec
gemspec

# `disposable` (via reform) requires `ostruct`, which is no longer a default gem
# since Ruby 4.0. disposable master already declares it, but 0.6.3 does not.
# Remove once a disposable release with the ostruct dependency is out.
gem "ostruct"
