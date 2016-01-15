source 'https://rubygems.org'

gem 'sinatra'
gem 'tilt', '~> 1.4.1'
gem 'tilt-jbuilder', require: 'sinatra/jbuilder'

group :production do
  gem 'foreman'
  gem 'unicorn'
end

gem 'httparty'
gem 'honeybadger'

gem 'endpoint_base', github: 'flowlink/endpoint_base'

group :development, :test do
  gem 'shotgun'
  gem 'pry'
  gem 'pry-byebug'
  gem 'simplecov', require: false
  gem 'dotenv'
end

group :test do
  gem 'vcr'
  gem 'rspec'
  gem 'webmock'
  gem 'guard-rspec'
  gem 'terminal-notifier-guard'
  gem 'rb-fsevent', '~> 0.9.1'
  gem 'rack-test'
  gem 'timecop'
end
