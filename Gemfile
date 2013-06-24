source 'https://rubygems.org'

gem 'rails'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
end

# assetsでは使うが、
# 本番環境ではデフォルトで不要なGem
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end

gem 'jquery-rails'
gem 'nokogiri' , '~>1.5.9'


group :test do
  gem 'capybara', '1.1.2'
end

group :production do
  gem 'pg'
end