source 'http://rubygems.org'

#source 'https://rubygems.org'

ruby '2.1.2'

gem 'rails', '4.2.0'
gem 'unicorn'
gem 'pg'
gem 'pghero'
gem 'sidekiq'
gem 'dalli'
gem 'arel'

gem 'sinatra', require: nil # for Sidekiq Web

# Assets
gem 'sass-rails', '~> 5.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'uglifier', '>= 1.3.0'
gem 'sass-mediaqueries-rails'
gem 'jquery-rails'
gem 'foundation-rails'
gem 'turbolinks'
gem 'ejs'
gem 'bourbon', '3.2.3' # remove once https://github.com/thoughtbot/bourbon/pull/616 is accepted and released in 4.2.0

# Admin
gem 'activeadmin', github: 'gregbell/active_admin'

# Analytics
gem 'mixpanel-ruby'

# Authorization and Authentication
gem 'responders', '~> 2.0' # required by Devise and we use it internally
gem 'devise'
gem 'omniauth'
gem 'omniauth-facebook'
gem 'fb_graph'
gem 'faraday', '~> 0.8.6'

# Error Reporting
gem 'bugsnag'

# Cloud Services
gem 'carrierwave'
gem 'fog'
gem 'urbanairship'

# cron
gem 'parse-cron'
gem 'clockwork'

# Images
gem 'chunky_png'
gem 'barby'
gem 'mini_magick'             # required for carrierwave
gem 'rmagick', require: false # required for carrierwave

# Phone Numbers
gem 'phony_rails'
gem 'twilio-ruby'

# Pagination
gem 'kaminari'

# Payments
gem 'activemerchant'
gem 'balanced'

# Templating Systems
gem 'rabl-rails'
gem 'redcarpet'

# Third Party Services
gem 'google-api-client'
gem 'google_drive'
gem 'geocoder'
gem 'hipchat'
gem 'mailchimp-api', require: 'mailchimp'

gem 'premailer-rails'
gem 'rack-cors', require: 'rack/cors'

# Eventing
gem 'celluloid-io'
gem 'websocket-rails'

group :production, :staging do
  gem 'rails_12factor'
  gem 'newrelic_rpm'
end

group :development, :test do
  gem 'factory_girl'
  gem 'spring'
  gem 'pry'
  gem 'guard-livereload'
  gem 'rspec-rails'
  gem 'spring-commands-rspec'
  gem 'guard-rspec', require: false
end

group :development do
  gem 'letter_opener'
  gem 'rack-mini-profiler'
  gem 'web-console', '~> 2.0'
end

group :test do
  gem 'shoulda-matchers', require: false
  gem 'json_expressions'
  gem 'dotenv-rails'
end

group :profile do
  gem 'ruby-prof'
end
