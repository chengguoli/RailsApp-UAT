source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.3', :patchlevel=>'183'

gem 'bigdecimal', '1.3.5'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~>6.0.4.8'
# Boot rails apps faster
gem 'bootsnap', '~> 1.7', '>= 1.7.7'
# Use Passenger as the app server
#gem 'passenger', '>= 5.3.2', require: 'phusion_passenger/rack_handler'
# Use SCSS for stylesheets
gem 'sass-rails'
# Uglifier minifies JavaScript files by wrapping UglifyJS to be accessible in Ruby
gem 'uglifier', '~> 4.2'
# CoffeeScript adapter for the Rails asset pipeline.
gem 'coffee-rails', '4.2.2'
# This gem provides jQuery and the jQuery-ujs driver for your Rails 4+ application
gem 'jquery-rails'

gem 'nprogress-rails', '~> 0.2.0.2'

# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
gem 'jquery-turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'
gem 'sdoc', '~> 2.2.0',          group: :doc
# Easy upload management for ActiveRecord
gem 'paperclip', '~> 6.1'
# AWS Cloud Service, Seems that it isn't used in this website
# gem 'fog-aws', '~> 3.10'
# gem 'aws-sdk', '~> 1.36.1'
# Flexible authentication solution for Rails with Warden
gem 'devise', '~> 4.8'

gem 'bootstrap-sass', '~> 3.4.1'
gem 'sassc-rails', '>= 2.1.0'

gem 'autoprefixer-rails'
gem 'rails_admin', '~> 2.2', '>= 2.2.1'

gem 'cancancan','3.2.2'
gem 'figaro'
gem 'ckeditor','5.1.0'
gem 'friendly_id', '~> 5.4.2'
# Phrasing is a gem for live editing phrases (copy) on websites.
gem 'phrasing', '~> 4.3', '>= 4.3.2'
gem 'nokogiri','~>1.13.6'
gem 'mysql2', '~> 0.5.0'
gem 'jquery-fileupload-rails', '~> 0.4.7'
# gem 'globalize', '~> 4.0.2'
gem 'ransack','~>3.0.1'
gem 'whenever', :require => false

gem 'kaminari'
gem 'acts-as-taggable-on', '5.0.0'
gem 'mini_racer', '~> 0.4.0'

gem 'omniauth'
gem 'omniauth-rails_csrf_protection'
gem 'omniauth-oauth2', '~> 1.7'
gem 'omniauth-facebook'
gem 'omniauth-weibo-oauth2'


group :development, :test do
  gem 'sqlite3', '1.4.2'
  gem 'rspec-rails', '~> 3.5.0'
  gem 'rb-fsevent', :require => false if RUBY_PLATFORM =~ /darvin/i
  gem 'launchy'
#  gem 'bullet',require: true
  # gem 'sunspot_solr' ###SOLR
  gem 'capybara', '3.14.0'
  gem 'guard-rspec', require: false

end
gem 'state_machine'
gem 'rails_admin_state'

group :development do

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  # gem 'pg'
  gem 'guard-livereload', require: false
  gem 'i18n-tasks', '~> 0.7.11'

end
gem 'seed_dump'
gem 'bootstrap-datepicker-rails'



