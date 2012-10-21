source 'http://rubygems.org'

gem 'rails', '3.0.7'
gem 'gravatar_image_tag', '1.00.0.pre2'
gem 'will_paginate', '3.0.pre2'
gem 'faker', '0.3.1'

group :production do
  gem 'pg'
  gem 'unicorn'
end

group :development, :test do
  gem 'sqlite3-ruby', '1.3.2', :require => 'sqlite3'
end

group :development do
	gem 'rspec-rails', '2.5.0'
  gem 'capistrano'
	gem 'annotate' 
end

group :test do
	gem 'rspec', '2.5.0'
	gem 'webrat', '0.7.1'
	gem 'spork'
	gem 'factory_girl_rails'
	gem 'autotest'
	gem 'autotest-rails-pure'
	gem 'test_notifier'
end

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19', :require => 'ruby-debug'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
# group :development, :test do
#   gem 'webrat'
# end
