source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.2.0', github: 'rails/rails', branch: '5-2-stable'
gem 'webpacker', '~> 3.0'
gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.7'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'font-awesome-rails'
gem 'will_paginate', '~> 3.1.6'
gem 'pygments.rb', '~> 1.2'
gem 'redcarpet', '~> 3.4.0'
gem 'friendly_id', '~> 5.2.4'
gem 'mail_form'# , github: "king601/mail_form"
gem 'devise', '~> 4.4'
gem 'refile', github: 'refile/refile', require: 'refile/rails'
gem 'refile-mini_magick', github: 'refile/refile-mini_magick'
gem 'sinatra', github: 'sinatra/sinatra', branch: 'master'

gem 'hootstrap', github: 'ProctorU/hootstrap'
gem 'will_paginate-bootstrap4'

group :development do
  gem 'puma', '~> 3.11'
  gem 'web-console', '~> 3.6.2'
end

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 3.3'
  gem 'selenium-webdriver'
  gem 'listen', '~> 3.1'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'minitest-focus', '~> 1.1', '>= 1.1.2'
  gem 'minitest-rails', '~> 3.0'
end
