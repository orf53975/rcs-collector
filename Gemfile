source "http://rubygems.org"
# Add dependencies required to use your gem here.

gem "rcs-common", ">= 8.0.0", :path => "../rcs-common"

gem 'eventmachine', ">= 1.0.0.beta.4"
git "git://github.com/alor/evma_httpserver.git", :branch => "master" do
  gem 'eventmachine_httpserver', ">= 0.2.2"
end
gem 'sqlite3'
gem 'uuidtools'

# Add dependencies to develop your gem here.
# Include everything needed to run rake, tests, features, etc.
group :development do
  gem "bundler", "~> 1.0.0"
  gem "jeweler", "~> 1.5.2"
  gem 'simplecov'
  gem 'test-unit'

  #git "git@rcs-dev:rcs-common.git", :branch => "devel" do
  #  gem "rcs-common"
  #end
end
