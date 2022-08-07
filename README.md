

# Welcome to My RSpec Expense Tracker Project!

Our API should faithfully save the expenses we record.

Using help from Rack::Test::Methods to get the data into and out of our app.
-post

## Tools
**Sinatra** - used for HTTP routing
**Ruby** - App main code
**Adapter** - Sequel
**Database** - SQLite


## RSpec Command Line Help

### Installation
*gem install bundler* ==> to install Bundler the same way you might install any Ruby gem
*bundle init* ==> initial project setup with Bundler (generates a default Gemfile)
*bundle install* ==> installs required libraries and their dependencies (gems listed in the Gemfile)
*bundle exec rspec* --init ==> to set up the project to use RSpec, generates two files. The *.rspec* file contains default command line flags and the *spec/spec_helper.rb* file contains configuration options.

### Testing
*bundle exec rspec* ==> runs our specs

### API
**bundle exec rackup** ==> comes from Sinatra HTTP toolkit Rack that runs Rack application, rackup config file required (*config.ru*)
**curl localhost:9292/expenses/2017-06-10 -w "\n"** ==> sample request sent to our app that returns data to the console