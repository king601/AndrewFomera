source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.1'

gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', github: 'turbolinks/turbolinks-classic' # Turbolinks 5 upgrade soon..
gem 'jbuilder', '~> 2.6'

group :development do
  gem 'capistrano', '~> 3.4.0'
  gem 'capistrano-bundler', '~> 1.1.4'
  gem 'capistrano-rails', '~> 1.1.2'
  gem 'capistrano-rvm', '~> 0.1.2'

  gem 'puma', '~> 3'

  gem 'web-console'
end


group :development, :test do
  gem 'byebug', platform: :mri
  gem 'listen', '~> 3.1'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'minitest-focus', '~> 1.1', '>= 1.1.2'
  gem 'minitest-rails', '~> 3.0'
  gem 'minitest-rails-capybara', '~> 3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'font-awesome-rails'
gem 'will_paginate', '~> 3.1.5'
gem 'pygments.rb', '~> 1.0'
gem 'redcarpet', '~> 3.3.4'
gem 'friendly_id', '~> 5.2.0'
gem 'mail_form', github: "king601/mail_form"
gem 'devise', '~> 4.2'
gem 'refile', github: 'refile/refile', require: 'refile/rails'
gem 'refile-mini_magick', github: 'refile/refile-mini_magick'
gem 'sinatra', github: 'sinatra/sinatra', branch: 'master'

gem 'jquery-turbolinks'
