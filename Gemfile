source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.0"

gem "importmap-rails"
gem "jbuilder"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "rails", "~> 7.0.4", ">= 7.0.4.2"
gem "redis", "~> 4.0"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
# gem "bcrypt", "~> 3.1.7"
gem "bootsnap", require: false
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
# gem "sassc-rails"
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'awesome_print'
  gem 'dotenv-rails'
  gem 'letter_opener_web', '~> 2.0'
  gem 'pry'
  gem 'pry-rails'
  gem 'rubocop-performance', '~> 1.16'
  gem 'rubocop-rails', '~> 2.17', '>= 2.17.4'
  gem 'web-console'
end
