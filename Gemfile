source 'https://rubygems.org'

group :development, :test do
  gem 'rspec'
  if ENV['X_PACT_DEVELOPMENT']
    gem 'pact', path: '../pact-ruby'
  else
    gem 'pact'
  end

  gem 'pact_broker-client'
  gem 'pry'

  group :v2, optional: true do
    gem "pact-ffi", "~> 0.4.28"
    gem 'combustion'
    gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]  
  end
end

gem 'rake'
gem 'rack'
gem 'httparty'
