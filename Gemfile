source 'https://rubygems.org'

gem 'rails', '4.0.12'
gem 'bootstrap-sass'
gem 'bcrypt-ruby'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'jquery-rails', '3.1.2'

group :development, :test do
  gem 'sqlite3', '1.3.10'
  gem 'rspec-rails', '3.1.0'
  gem 'guard-rspec'
  gem 'guard-spork'
  gem 'childprocess'
  gem 'spork'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '5.0.0'
  gem 'coffee-rails', '4.1.0'
  gem 'uglifier', '2.6.1'
end

group :test do
  gem 'capybara', '2.4.4'
  gem 'factory_girl_rails'
  gem 'cucumber-rails', :require => false
  gem 'database_cleaner'
  # gem 'launchy', '2.1.0'
  # gem 'rb-fsevent', '0.9.1', :require => false
  # gem 'growl', '1.0.3'
end

group :production do
  gem 'pg', '0.17.1'
end