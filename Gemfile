source "https://rubygems.org"

gemspec

group :test do
  gem "rake"
  gem "rack-test", "~> 0.5"
  gem "mocha", :require => false
  gem "airbrake"
  gem "activesupport", "~> 3.0"
  gem "i18n"
  gem "minitest", "4.7.0"
end

platforms :rbx do
  # These are the ruby standard library
  # dependencies and transitive dependencies.
  gem 'rubysl-net-http'
  gem 'rubysl-socket'
  gem 'rubysl-logger'
  gem 'rubysl-cgi'
  gem 'rubysl-uri'
  gem 'rubysl-timeout'
  gem 'rubysl-zlib'
  gem 'rubysl-json'
  gem 'rubysl-stringio'
  gem 'rubysl-test-unit'
end
