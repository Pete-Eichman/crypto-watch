# Crypto Watch
Crypto Watch is a cryptocurrency tracker. It will pull from coin market APIs to allow users to keep track of the prices of cryptocurrencies they care about, across different markets, in one easy location.

## Why Crypto Watch?
Most cryptocurrency websites keep track of all the cryptocurrency prices across markets. Crypto Watch will allow users to create an account to track specific coins in their profile. This way, a user can look at one page and see only the coins they care about, rather than having to search for them individually, or sleuth through a long index of coins.

## Back End
* Ruby -v 2.3.1
* Rails -v 5.0.0.1
* PostgreSQL -v 0.15

## Testing
* Rspec-rails gem
* Capybara & Capybara-webkit gems
* Factory Girl via the factory_girl_rails gem

# Get Set Up
* Clone down the repository.
* Run 'bundle install' or 'bundle exec bundle install' to download the Gemfile.
* Run the following commands to setup the database:
  * 'rake db:create'
  * 'rake db:migrate'
  * 'rake db:seed'
* Run 'rake' or 'rspec' to start the test suite.
* Run 'rails s' to start the server, and CTRL+C to stop the server.
* Visit localhost:3000 while the server is running.
