source "http://rubygems.org"

group :test do
  gem 'faker'
  gem 'rspec-rails', '~> 2.8.1'
  gem 'factory_girl_rails', '~> 1.7.0'
  gem 'guard-rspec'
  gem 'sqlite3'

  if RUBY_PLATFORM.downcase.include? "darwin"
    gem 'rb-fsevent'
    gem 'growl'
  end
end

gem 'spree', '~> 1.2.0'
gem 'spree_auth_devise', :git => 'git://github.com/spree/spree_auth_devise'

gemspec