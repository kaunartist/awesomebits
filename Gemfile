source 'http://rubygems.org'

gem 'rails', '3.2.17'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

gem 'country_select'
gem 'pg', '~> 0.13.2'
gem 'texticle', '~> 2.0', :require => 'texticle/rails'
gem 'jquery-rails'
gem 'clearance', '~> 0.16.2'
gem 'thin'
gem 'sass'
gem 'high_voltage'
gem 'paperclip', '~> 3.0.3'
gem 'fog'
gem 'formtastic'
gem 'flutie'
gem 'bourbon', '~> 1.4.0'
gem 'copycopter_client'
gem "simple_form", :git => "https://github.com/plataformatec/simple_form.git"
gem 'nokogiri'
gem "will_paginate", "~> 3.0.3"
gem "friendly_id", "~> 4.0.9"
gem 'redcarpet'
gem 'honeypot-captcha'

group :development, :test do
  gem "rspec-rails"
  gem "ruby-debug19"
  gem "sham_rack"
  gem "tddium"
  gem "evergreen", :require => "evergreen/rails"
  gem "pry"
  gem "pry-nav"
end

group :test do
  gem "turnip"
  gem "capybara"
  gem "database_cleaner"
  gem "capybara-webkit", "0.9.0"
  gem "factory_girl_rails"
  gem "bourne"
  gem "timecop"
  gem "shoulda-matchers"
  gem "launchy"
  gem "email_spec"
end

group :staging, :production do
  gem 'newrelic_rpm'
  gem 'sprockets-redirect'
  gem 'unicorn'
  gem 'rails_12factor'
end
