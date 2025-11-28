ruby "3.4.7"
source "https://rubygems.org"

# Core framework
gem "rails", "7.1.5.2"

# Bundle edge Rails instead:
# gem "rails", :git => "git://github.com/rails/rails.git"

# Assets pipeline
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem "sass-rails",   "~> 6.0.0"
  gem "coffee-rails", "~> 5.0.0"

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem "therubyracer", :platforms => :ruby

  gem "uglifier", ">= 1.0.3"
  gem "bootstrap-sass", "~> 3.4.1"
  gem "bootswatch-rails"
end

# jQuery integration
gem "jquery-rails"

# Databases
group :development do
  # SQLite for development and test
  gem "sqlite3"
end

group :production do
  # PostgreSQL for production
  gem "pg", "0.12.2"
end

# Authentication
gem "devise", "~> 4.9"
gem "devise_invitable", "~> 2.0.9"

# Forms
gem "simple_form"

# Development tools
gem "nifty-generators", :group => :development
gem "rename"

# To use ActiveModel has_secure_password
# gem "bcrypt-ruby", "~> 3.0.0"

# To use Jbuilder templates for JSON
# gem "jbuilder"

# Use unicorn as the app server
# gem "unicorn"

# Deploy with Capistrano
# gem "capistrano"

# To use debugger
# gem "debugger"

# Testing
gem "mocha", :group => :test
