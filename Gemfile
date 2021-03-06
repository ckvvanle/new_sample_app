# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.4.4"

gem "rails", "~> 5.2.0"

gem "bcrypt", "3.1.12"
gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap-sass", "3.3.7"
gem "coffee-rails", "~> 4.2"
gem "config"
gem "duktape"
gem "jbuilder", "~> 2.5"
gem "jquery-rails", "~> 4.3", ">= 4.3.3"
gem "puma", "~> 3.11"
gem "sass-rails", "~> 5.0"

gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"
gem "figaro"

gem "bootstrap-will_paginate", "1.0.0"
gem "carrierwave", "1.2.2"
gem "faker", "1.7.3"
gem "mini_magick", "4.7.0"
gem "rails-controller-testing"
gem "rubocop", "~> 0.54.0", require: false
gem "will_paginate", "3.1.6"

group :development, :test do
  gem "byebug", platforms: %i(mri mingw x64_mingw)
  gem "sqlite3"
end

group :development do
  gem "listen"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15", "< 4.0"
  gem "chromedriver-helper"
  gem "selenium-webdriver"
end

group :production do
  gem "fog", "1.42"
  gem "pg", "0.20.0"
end
gem "tzinfo-data", platforms: %i(mingw mswin x64_mingw jruby)
