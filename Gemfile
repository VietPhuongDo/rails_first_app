source "https://rubygems.org"

ruby "3.2.2"
gem 'bootstrap', '~> 4.0.0.alpha4'
gem 'jquery-rails'
gem 'sassc-rails'
gem "rails", "~> 7.1.3"
gem "sprockets-rails"

gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri windows ]
  gem "sqlite3", "~> 1.4"
end

group :development do
  gem "web-console"
end

group :production do
  gem 'pg'
end
group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
