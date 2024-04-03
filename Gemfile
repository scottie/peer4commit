source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 7.0.8', '>= 7.0.8.1'

# Databases
gem 'sqlite3', group: :development
gem 'mysql2', group: :mysql
gem 'pg', group: :postgresql

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.8'
gem 'haml-rails', '>= 0.6.0'
gem "less-rails", ">= 2.5.0"

gem 'twitter-bootstrap-rails', github: 'seyhunak/twitter-bootstrap-rails', branch: 'bootstrap3'

gem 'kaminari', '>= 0.15.1'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.2.2'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.0.1'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '>= 2.2.1'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', '>= 1.0.0', require: false
end

gem 'devise', '>= 4.7.0'
gem 'omniauth', '>= 1.3.1'
gem 'omniauth-github', github: 'alexandrz/omniauth-github', branch: 'provide_emails'
gem 'cancancan'

gem 'octokit'

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use debugger
# gem 'debugger', group: [:development, :test]

group :development do
  gem 'capistrano', '~> 3.0'
  gem 'capistrano-rvm', github: 'capistrano/rvm'
  gem 'capistrano-bundler', '>= 1.1.0'
  gem 'capistrano-rails'
  gem 'quiet_assets', '>= 1.0.3'
end

gem 'airbrake'
gem 'httparty'
gem 'whenever'
gem 'rqrcode-rails3'
gem 'exception_notification', '>= 4.1.0'
gem 'rack-canonical-host', '>= 0.2.1'
gem 'bootstrap_form', github: 'sigmike/rails-bootstrap-forms', branch: 'removed_for_on_radio_label'
gem 'html_pipeline_rails'
gem 'rails_autolink', '>= 1.1.6'

group :test do
  gem 'cucumber-rails', '>= 1.4.3', :require => false
  # database_cleaner is not required, but highly recommended
  gem 'database_cleaner'
  gem 'rspec-rails', '>= 2.14.2'
  gem 'factory_girl_rails', '>= 4.5.0'
end
