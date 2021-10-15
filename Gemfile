# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.5'
# Use mysql as the database for Active Record
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
# gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS)
# making cross-origin AJAX possible
# gem 'rack-cors'

group :development, :test do
  # 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '~> 10.0.2', platforms: %i[mri mingw x64_mingw]

  gem 'factory_bot_rails', '~> 4.8.2'
  gem 'rspec-rails', '~> 3.7'
  gem 'rubocop', '~> 0.55.0'
  gem 'rubocop-rspec', '~> 1.25.1'
  gem 'simplecov', '~> 0.17.1'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development
  # keeping your application running in the background.
  # Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.0.2'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'seed_dump', '~> 3.3.1'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', '~> 1.2.5', platforms: %i[mingw mswin x64_mingw jruby]

# user add gems
## ENV
gem 'dotenv-rails', '~> 2.4.0'
## DB
gem 'activerecord-import', '~> 0.23.0'
## validation
gem 'committee', '~> 2.1.0'
