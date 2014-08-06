source 'https://rubygems.org'

gem 'rake'
gem 'pry'
gem 'settingslogic'
gem 'sinatra'
gem 'sinatra-contrib'
gem 'code_notes'
gem 'colored'
gem 'eventmachine'
gem 'json'
gem 'webrick'

gem 'sqlite3', group: :sqlite
gem 'mysql2', group: :mysql

group :development do
  gem 'rspec'
  gem 'fakefs'
end

# This evals a Gemfile_local file that you can put dependencies for your
# RubyServ plugins.
local_gemfile = File.expand_path('../Gemfile_local', __FILE__)

eval File.read(local_gemfile) if File.exists?(local_gemfile)
