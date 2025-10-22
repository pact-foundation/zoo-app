source 'https://rubygems.org'

group :development, :test do
  gem 'rspec'
  if ENV['X_PACT_DEVELOPMENT']
    gem 'pact', path: '../pact-ruby'
  else
    gem 'pact'
  end
  gem 'combustion'
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]  
  gem 'pact_broker-client'
  gem 'pry'
end

gem 'rake'
gem 'rack'
gem 'httparty'
