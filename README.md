# Clicker App

An app that makes it easy to give feedback during a class.

## Local Setup

1. `bundle`
1. `cp .env{.example,}`
1. Add your correct username and password in the connection string in `.env`
1. `createdb -U gschool_user clicker_development`
1. `createdb -U gschool_user clicker_test`
1. `rake db:migrate`
1. `rackup`

## Running Specs

1. `rspec`

Note: The tests will automatically migrate the test database up to
the latest version before before running the tests.
