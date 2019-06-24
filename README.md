# RAILS CI CD SETUP

[![CircleCI](https://circleci.com/gh/thoth-ky/rails-ci-cd-setup/tree/develop.svg?style=svg)](https://circleci.com/gh/thoth-ky/rails-ci-cd-setup/tree/develop)  [![Coverage Status](https://coveralls.io/repos/github/thoth-ky/rails-ci-cd-setup/badge.svg?branch=develop)](https://coveralls.io/github/thoth-ky/rails-ci-cd-setup?branch=develop)

This is a simple rails project to demonstrate how to setup CI/CD. The app's functionality is simply to keep track of products and their prices. 

## System dependencies
  * Ruby 2.6.2 (You can use [rbenv](https://github.com/rbenv/rbenv) or [rvm](https://rvm.io/) but not both)
  * Rails 5.2.3
  * Bundler gem
  * PostgreSQL 11.3

## Configuration
  * Clone this repository
    ```zsh
    $ git clone https://github.com/thoth-ky/rails-ci-cd-setup.git
    $ cd rails-ci-cd-setup
    ```
  * Ensure that the Postgres is installed, and linked
    ```
    $ brew install postgres
    $ brew link postgres
    ```
  * Install gems
    ```zsh
    $ bundle install
    ```

## Database creation
  ```zsh
  $ rails db:create
  $ rails db:migrate
  ```

## How to run the test suite
  ```zsh
  $ bundle execrspec
  ```

## Deployment instructions

 * Check out deployed version on heroku [here]( https://rails-test-app-ky.herokuapp.com/)
 * To try it locally, run the following command on Heroku CLI
  ```zsh
  $ heroku local web
  ```

## Author
  * Joseph Mutuku Kyalo


