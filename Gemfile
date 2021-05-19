# A sample Gemfile
source "https://rubygems.org"

gem 'sinatra'
gem 'thin'
gem 'require_all'

#access to the magical database mapping and association powers
gem 'activerecord', '5.2'
#quickly create files and folders, and automate tasks such as database creation
gem 'rake'
#access to some awesome Rake tasks
gem 'sinatra-activerecord'

#won't use either of these in production / won't get installed on our server when we deploy our application
group :development do 
	gem 'shotgun'
	gem 'pry'
	#database adapter gem - allows our Ruby application to communicate with a SQL database
	gem 'sqlite3', '~> 1.3.6'
	#interactive console that pre-loads our database and ActiveRecord relationships
	gem 'tux'
end