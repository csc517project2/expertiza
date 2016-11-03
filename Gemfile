java_home = '/usr/lib/jvm/java-7-openjdk-amd64'
ENV['JAVA_HOME'] = java_home if Dir.exist?(java_home)

gem 'capistrano', '~> 3.0', require: false, group: :development
group :development do
  gem 'capistrano-rails',   '~> 1.1', require: false
  gem 'capistrano-bundler', '~> 1.1', require: false
end

source 'http://rubygems.org'

gem 'rails', '~> 4.2.6'

gem 'aspell-heroku'

## Gems in Alphabetical Order

gem 'activerecord-session_store'
gem 'airbrake'
gem 'awesome_nested_set'
gem 'bind-it'

gem 'coveralls', require: false
gem 'delayed_job_active_record'
gem 'dynamic_form'
gem 'edavis10-ruby-web-search'
gem 'engtagger'
gem 'expertiza-authlogic', github: 'expertiza/authlogic', require: 'authlogic'
gem 'fastercsv'
gem 'ffi-aspell'
gem 'font-awesome-rails'
gem 'gchartrb', require: 'google_chart'
gem "googlecharts", require: "gchart"
gem 'gdata', require: false
gem 'haml-rails'
gem 'jquery-rails'
gem 'jquery-ui-sass-rails'
gem 'jquery-datetimepicker-rails'
gem 'json', '~> 1.8', '>= 1.8.3'
gem 'lingua'
gem 'mysql2'
gem 'nokogiri', '~> 1.6.8'
gem 'omniauth-google-oauth2', '~> 0.2.6'
gem 'open-uri-cached'
gem 'paper_trail'
gem 'pg', group: :production
gem 'protected_attributes'
gem 'rails4-autocomplete'
gem 'rake'
gem 'rb-readline'
gem 'rest-client', '~> 1.8'
gem 'RedCloth'
gem 'rgl', require: 'rgl/adjacency'
gem 'rjb'
gem 'rubyzip'
gem 'rwordnet', '0.1.3'
gem 'scrypt'
gem 'sass-rails', '5.0.3'
gem 'seer'
gem 'sprockets'
gem 'stanford-core-nlp'
gem 'superfish-rails'
gem 'therubyracer'
gem 'thin'
gem 'uglifier'
gem 'will_paginate'
gem 'zip-zip'
gem 'react-rails', '~> 1.0'
gem 'jquery-tablesorter'

group :development do
  gem 'daemons'
  gem 'pry'
  gem 'pry-remote'
  gem 'pry-nav'
  gem 'rubocop'
  gem 'selenium-webdriver'
  gem 'quiet_assets'
  gem "factory_girl_rails", "~> 4.0"
end

group :test do
  gem 'database_cleaner'
  gem 'gherkin'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'launchy'
  gem 'rspec-rails'
  gem 'shoulda'
  gem 'test-unit'
end

group :assets do
  gem 'coffee-rails'
end

group :development, :test do
  gem 'capybara'
  gem 'simplecov', require: false
end
