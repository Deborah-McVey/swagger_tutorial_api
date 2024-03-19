# README

Codefi lesson due 03/18/2024

rails new swagger_tutorial_api --api -T

# test and document
add gem 'rswag'
gem 'rspec-rails', '~> 6.1.0' to production test block

bundle i

rails g rspec:install

rails g rswag:install

# Run the following command to generate the swagger documentation
rails rswag:specs:swaggerize

rails s

http://localhost:3000/api-docs