source 'http://rubygems.org'

gem 'rails','~> 3.2.5'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'


# Gems used only for assets and not required
# in production environments by default.

gem 'jquery-rails'

gem 'spud_photos', :git => 'git://github.com/bernardogalindo/spud_photos.git'

#upload photos s3
gem 'paperclip'
gem 'aws-sdk'

gem 'sitemap_generator', :git => 'git://github.com/kjvarga/sitemap_generator.git'
gem 'fog'
group :assets do
 # Add these gems
 gem 'zurb-foundation'
 gem 'sass-rails'
 gem 'compass-rails'

 
 gem 'sprockets'
 gem 'coffee-rails'
 gem 'uglifier'
 gem 'bootstrap-sass'
 gem 'ejs'
 gem 'font-awesome-sass-rails'
end
# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :development do
	gem 'sqlite3'
end

group :test do
  # Pretty printed test output
  gem 'turn', '0.8.2', :require => false
	gem 'sqlite3'
end


group :production do
	gem 'pg'
end
