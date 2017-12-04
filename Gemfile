source 'https://rubygems.org'
ruby '2.4.2'
#ruby-gemset=railstutorial_rails_5_0

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.1.4'
# Use sqlite3 as the database for Active Record
group :development do
  gem 'sqlite3'
  gem 'listen'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
group :doc do
  gem 'sdoc', '0.3.20', require: false
end