# RAILS CI CD SETUP

This is a simple rails project to demonstrate how to setup CI/CD.

## System dependencies
  * Ruby 2.6.2 (You can use [rbenv](https://github.com/rbenv/rbenv) or [rvm](https://rvm.io/) but not both)
  * Rails 5.2.3
  * Bundler gem
  * PostgreSQL 11.3

## Configuration
  * Clone this repository
    ```zsh
    git clone https://github.com/thoth-ky/rails-ci-cd-setup.git
    cd rails-ci-cd-setup
    ```
  * Ensure that the Postgres is installed, and linked
    ```
    brew install postgres
    brew link postgres
    ```
  * Install gems
  ```zsh
  bundle install
  ```

## Database creation
  ```zsh
  rails db:create
  rails db:migrate
  ```

## How to run the test suite
<!-- TODO: -->

## Deployment instructions
<!-- TODO: -->

## Author
  * Joseph Mutuku Kyalo


