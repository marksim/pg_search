source "http://rubygems.org"

gemspec

gem 'pg', :platform => :ruby
gem "activerecord-jdbcpostgresql-adapter", :platform => :jruby

gem "activerecord", ENV["ACTIVE_RECORD_VERSION"] if ENV["ACTIVE_RECORD_VERSION"]

gem 'coveralls', :require => false, :platform => :mri_20

group :development do
  gem 'guard-rspec', :require => false
  gem 'rb-inotify', :require => false
  gem 'rb-fsevent', :require => false
  gem 'rb-fchange', :require => false
end
