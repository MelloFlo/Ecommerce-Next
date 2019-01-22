# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

File.read('./.ruby-version')

gem 'bootsnap', '>= 1.1.0', require: false
gem 'bootstrap', '~> 4.2', '>= 4.2.1'
gem 'coffee-rails', '~> 4.2'
gem 'figaro', '~> 1.1', '>= 1.1.1'
gem 'jbuilder', '~> 2.5'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.2'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 4.11', '>= 4.11.1'
  gem 'faker', '~> 1.9', '>= 1.9.1'
  gem 'rspec-rails', '~> 3.8', '>= 3.8.2'
  gem 'sandi_meter', '~> 1.2'
end

group :development do
  gem 'annotate', '~> 2.7', '>= 2.7.4'
  gem 'husky', '~> 0.5.15'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop', '~> 0.63.0'
  gem 'rubocop-rspec', '~> 1.31'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'database_cleaner', '~> 1.7'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.2'
  gem 'simplecov', '~> 0.16.1'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
