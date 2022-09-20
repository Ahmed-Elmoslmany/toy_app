source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem 'sass-rails' #new
gem "turbo-rails"
gem 'turbolinks' # new
# gem 'webpacker' #new
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

### new 


group :development, :test do
  gem 'sqlite3', "~> 1.4"
  gem 'byebug', '11.0.1', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console','4.0.1'
  gem 'listen'
  gem 'spring','2.1.0'
  gem 'spring-watcher-listen'

  
end

group :test do
  
  gem 'capybara','3.28.0'
gem 'selenium-webdriver', '3.142.4'
gem 'webdrivers','4.1.2'
end

group :production do
gem 'pg'
end
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
