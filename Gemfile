# frozen_string_literal: true

gem 'dotenv', require: 'dotenv/load', groups: %i[development test]

ruby '2.6.6'

source 'https://rubygems.org'

gem 'activesupport', '>= 6.0.3.2'
gem 'graphql'
gem 'osso', git: 'git@github.com:enterprise-oss/osso-rb.git', branch: 'sbauch/remove-single-table-inheritance'
gem 'pg'
gem 'rack', '>= 2.1.4'
gem 'rake'
gem 'sinatra'
gem 'sinatra-cors'

group :test do
  gem 'database_cleaner-active_record'
  gem 'factory_bot'
  gem 'faker'
  gem 'rack-test'
  gem 'rspec', '~> 3.2'
  gem 'webmock', '~> 3.0'
end

group :development, :test do
  gem 'pry'
  gem 'rubocop'
  gem 'sinatra-contrib'
end
