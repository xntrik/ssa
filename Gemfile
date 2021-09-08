source 'https://rubygems.org'

gem 'rails', '4.1.0'
gem 'protected_attributes'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'thin'
gem 'asset_sync', '>= 1.0.0'
#gem 'mongoid', '~> 2.4'
#gem 'bson_ext', '~> 1.5'
gem 'devise'


# Gems used only for assets and not required
# in production environments by default.
# group :assets do
  gem 'sass-rails', '~> 4.0.3'
  gem 'coffee-rails'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platform => :ruby

  gem 'uglifier', '>= 1.0.3'
# end

gem 'jquery-rails'

# Gems just for development, currently this is just used to split the DB requirements
group :development, :test do
	#gem 'pg'
	gem 'sqlite3'
end

# For Prod, we're recommending Postgresql
group :production do
	gem 'pg'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
