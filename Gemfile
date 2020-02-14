source 'https://rubygems.org'
gem 'rails', '4.1.8'
gem 'pg'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2.2'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development


group :development, :test do
  gem 'simplecov'                # local code coverage
  gem 'selenium-webdriver'       # integration tests

  gem "capybara"                 # integration tests
  gem "database_cleaner"         # capybara depends

  #gem "datum"
  gem "datum", :git => 'https://github.com/tyemill/datum.git', :branch => '2014_edge'
  #gem "datum", :path => '../datum' # localdev
end

