source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'bootstrap-sass', '~> 2.3.0'
gem 'bootswatch-rails'
gem 'faker', '1.0.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'kaminari'

gem 'pg'
gem 'devise'
gem 'omniauth-twitter'
gem 'carrierwave'
gem "fog", "~> 1.3"
gem "mini_magick", "~> 3.5.0"
gem 'textacular', '~> 3.0', require: 'textacular/rails'
gem "jquery-rails"
gem 'acts-as-taggable-on', github: 'rubymonsters/acts-as-taggable-on'
gem 'auto_html', github: 'dejan/auto_html'
gem 'mandrill-api'

group :development do
  gem "letter_opener"
  gem "quiet_assets" # mutes asset pipeline log messages
  gem "puma" # better ruby webserver no error messages: "Could not determine content-length of response body."
  # start with: rails s Puma
end

group :development, :test do
  gem 'capybara', '~> 2.0.2'
end

group :test do
  gem 'factory_girl_rails', '4.1.0'
end


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
