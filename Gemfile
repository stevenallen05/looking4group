# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'activeresource'
gem 'bootsnap', require: false
gem 'dotenv-rails'
gem 'dry-validation'
gem 'httparty'
gem 'jbuilder', '~> 2.7'
gem 'pg'
gem 'puma'
gem 'rails'
gem 'rails-observers'
gem 'redis'
gem 'redis-namespace'
gem 'redis-rails'
gem 'rswag-api'
gem 'rswag-ui'
gem 'sass-rails', '>= 6'
gem 'sidekiq'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 4.0'

group :development, :test do
  gem 'brakeman'
  gem 'bundler-audit'
  gem 'factory_bot_rails'
  gem 'fasterer'
  gem 'ffaker'
  gem 'pry-rails'
  gem 'rails_best_practices'
  gem 'rspec-rails'
  gem 'rubocop'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'rubocop-rspec'
end

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  gem 'coveralls'
  gem 'database_cleaner'
  gem 'rspec-sidekiq'
  gem 'rswag-specs'
  gem 'shoulda-matchers'
  gem 'simplecov'
  gem 'timecop'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
