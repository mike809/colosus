source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.0'
# # bundle exec rake doc:rails generates the API under doc/api.
# gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
group :development do
  gem 'spring'
  gem 'mailcatcher'
end

gem "font-awesome-rails"
gem 'formtastic-bootstrap', '2.1.3'
gem 'formtastic', '2.2.1'
gem 'cancan'
gem 'slim-rails'
gem 'devise'
gem 'devise_invitable'
gem 'devise-async'

group :test, :development do
  gem 'factory_girl_rails'
  gem 'awesome_print'
  gem 'byebug'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'sqlite3'
end

group :test do
  gem 'capybara'
  gem 'poltergeist'
  gem 'guard-spork'
  gem 'guard-rspec'
  gem 'timecop'
end

group :assets do
  gem 'sass-rails', '~> 4.0.3'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.0.0'
end

group :production do
    gem 'pg'
end
# Use ActiveModel has_secure_password
gem 'bcrypt'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development