source 'https://rubygems.org'
ruby '2.1.2'

gem 'rails', '~> 4.1.0'
gem 'sass-rails', '~> 4.0.3'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'factory_girl_rails'
end

group :development do
  gem 'capistrano-rails'
  gem 'byebug'
end

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'spork-rails'
  gem 'guard-spork'
  gem 'childprocess'
#  gem 'spring'
#  gem 'spring-commands-rspec'
#  gem 'rb-fsevent' if `uname` =~ /Darwin/
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'guard-bundler'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end