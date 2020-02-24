source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.0.3'

# Databases
gem 'sqlite3', group: :development
gem 'mysql2', group: :mysql
gem 'pg', group: :postgresql

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.1'
gem 'haml-rails', '>= 0.5.3'
gem "less-rails"

gem 'twitter-bootstrap-rails', github: 'seyhunak/twitter-bootstrap-rails', branch: 'bootstrap3'

gem 'kaminari'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.1'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 3.0.4'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '>= 2.2.0'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

gem 'devise', '>= 3.2.2'
gem 'omniauth'
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
  gem 'capistrano', '~> 3.0', '>= 3.0.1'
  gem 'capistrano-rvm', github: 'capistrano/rvm'
  gem 'capistrano-bundler', '>= 1.1.1'
  gem 'capistrano-rails', '>= 1.1.0'
  gem 'quiet_assets', '>= 1.0.2'
end

gem 'airbrake'
gem 'httparty'
gem 'whenever'
gem 'rqrcode-rails3'
gem 'exception_notification'
gem 'rack-canonical-host'
gem 'bootstrap_form', github: 'sigmike/rails-bootstrap-forms', branch: 'removed_for_on_radio_label'
gem 'html_pipeline_rails'
gem 'rails_autolink', '>= 1.1.5'

group :test do
  gem 'cucumber-rails', '>= 1.4.0', :require => false
  # database_cleaner is not required, but highly recommended
  gem 'database_cleaner'
  gem 'rspec-rails', '>= 2.14.1'
  gem 'factory_girl_rails', '>= 4.4.1'
end
