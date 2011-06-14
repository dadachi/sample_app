source 'http://rubygems.org'

gem 'rails', '3.1.0.rc4'
gem "mysql2", "0.3.2"

gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'
gem 'gravatar_image_tag', '0.1.0'
gem 'kaminari'
gem 'transitions', :require => ['transitions', 'active_record/transitions']
gem 'haml', "~> 3.1.2"

# Rails 3.1 - Asset Pipeline
gem 'json'
gem 'sass'
gem 'coffee-script'
gem 'uglifier'
gem 'jquery-rails'

group :development do
  gem 'annotate-models', '1.0.4'
  gem 'faker', '0.3.1'
end

group :test do
  gem 'factory_girl_rails', '1.0'
end

group :development, :test do
  gem 'rspec-rails', :git => 'git://github.com/rspec/rspec-rails.git'
  gem 'capybara', :git => 'git://github.com/jnicklas/capybara.git'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'guard-rspec'
  gem 'guard-livereload'
  gem 'growl', :require => false if RUBY_PLATFORM =~ /darwin/i
  gem 'guard-spork'
end

# Rails 3.1 - Heroku
group :production do
  gem 'therubyracer-heroku', '0.8.1.pre3'
  gem 'pg'
end