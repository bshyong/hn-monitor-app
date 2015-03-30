source 'https://rubygems.org'

ruby '2.1.5'

gem 'rails', '4.1.6'
gem 'pg'

gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'sass-rails', '>= 3.2'
gem 'bootstrap-sass', '~> 3.3.1'
gem 'sprockets-rails', :require => 'sprockets/railtie'
gem 'jquery-rails'
gem 'jquery-ui-rails', '~> 5.0.2'
gem 'showdown-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'autoprefixer-rails'


# Bundler >= 1.7.0 is required for rails-assets.
gem 'bundler', '>= 1.7.0'
source 'https://rails-assets.org' do
  gem 'rails-assets-bootstrap-tokenfield'
  gem 'rails-assets-typeahead.js'
end

gem 'sidekiq'


gem 'hackernews_ruby', :git => 'https://github.com/allcentury/hackernews_ruby'

# Authentication
gem 'devise'

# Server
gem 'puma'


group :development, :test do
  gem 'byebug'
  gem 'web-console'
  gem 'spring'
end

group :test do
  gem 'rspec-rails', '~> 3.0.0'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'shoulda-matchers', require: false
  #gem 'faker'
end

group :production do
  gem 'rails_12factor'
end
