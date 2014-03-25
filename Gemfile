source "http://rubygems.org"

gemspec

gem 'faraday_middleware', git: 'git@github.com:lostisland/faraday_middleware.git', branch: 'faraday-0.9'

group :development, :test do
  gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'growl', :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'growl_notify', :require => false if RUBY_PLATFORM =~ /darwin/i
end
