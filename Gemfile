source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use SCSS for stylesheets
gem 'sass-rails', '4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '~> 2.1.2'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '4.0.0'

# Use jquery as the JavaScript library
gem 'jquery-rails', '~> 3.0.4'
gem "jquery-fileupload-rails"
gem 'jquery-ui-rails', '~> 4.1.1'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
#gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.0.1'

# Use the Twitter typeahead.js library
gem 'twitter-typeahead-rails', '~> 0.9.3'

# Our own fork of a gem for interacting with Gnip's Rules API
gem 'gnip-rules', '~> 1.1.7'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', '~> 0.3.20', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use debugger
# gem 'debugger', group: [:development, :test]

gem 'haml-rails', '0.4.0'
gem 'therubyracer', '~> 0.12.0'
gem 'less-rails', '2.3.3' #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem 'twitter-bootstrap-rails', '~> 2.2.8'
gem 'bootstrap_forms', '~> 4.0.1'
gem 'delayed_job_active_record', '4.0.0'
gem 'daemons', '~> 1.1.9'
gem 'hipchat', '~> 0.11.0'
gem 'exception_notification', '~> 4.0.1'
gem 'figaro', '~> 0.7.0'
gem 'whenever', '~> 0.8.4', :require => false
gem 'parse-cron', '~> 0.1.2', :github => 'siebertm/parse-cron'
gem 'state_machine', '~> 1.2.0'
gem 'activerecord-redshift-adapter'
gem 'pg', '~> 0.17.1' # force newer version to avoid signal trapping regression in 0.16
gem 'crypt_keeper', '~> 0.13.1'
gem 'friendly_id', '5.0.0.beta4'
gem 'devise', '3.1.1'
gem 'authority', '~> 2.7.0'
gem 'rolify', '~> 3.3.0.rc4'
gem 'user_impersonate'
gem 'paranoia', '2.0.0'
gem 'rack-mini-profiler', '0.1.29'
gem 'aws-sdk', '1.23.0' #, '~> 1.23.0'
gem 'parallel', '~> 0.8'
gem 'ancestry', '~> 2.0.0'
gem 'savon', '2.3.0'
gem 'multipart-post', '~> 1.2.0'

gem 'puma', '~> 2.7.1'

# https://github.com/smartinez87/exception_notification/issues/155
#gem 'exception_notification', :require => 'exception_notifier'
gem 'best_in_place', '~> 2.1.0', github:'bernat/best_in_place'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'
gem 'rubyzip', '~> 1.1.0'
gem 'net-ssh', '~> 2.6.8'
gem 'google_drive', '0.3.6'
gem 'net-sftp', '~> 2.1.2'
gem 'terminal-table', '~> 1.4.5'

group :development do
  gem 'binding_of_caller', '~> 0.7.2'
  gem 'better_errors', '~> 1.0.1'
  gem 'capistrano', '~> 2.15.5'
  gem 'thor', '~> 0.18.1'
  gem 'letter_opener', '~> 1.1.2'
  gem 'quiet_assets', '~> 1.0.2'
  gem 'colored', '~> 1.2.0'
end

group :development, :test do
  gem 'rspec-rails', '2.14.0'
  gem 'factory_girl_rails', '~> 4.2.1'
  gem 'sqlite3', '~> 1.3.8'
  gem 'pry-rails', '0.3.2'
  gem 'pry-debugger', '~> 0.2.2'
end

group :test do
  gem 'database_cleaner', '~> 1.0.1'
  gem 'capybara', '~> 2.1.0'
  gem 'poltergeist', '~> 1.4.1'
  gem 'metric_fu', '4.4.1'
  gem 'simplecov', '~> 0.7.1', require: false
  gem 'brakeman', '2.1.1', require: false
  gem 'vcr', '~> 2.6.0'
  gem 'webmock', '1.11.0'
end

group :production do
  gem 'mysql2', '0.3.13' #rds
end
