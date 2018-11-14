# Homecooked
Homecooked is a ruby on rails application created to manage and share recipes.

## Installation to run locally
In a bash terminal, clone the application repository from github then run the application.

    $ git clone git@github.com:nichia/homecooked.git
    $ cd homecooked
    $ mv .env.bak .env  (edit the .env file to fill in secret keys)
    $ run bundle install
    $ run rake db:setup
    $ run rake db:migrate
    $ run rake db:seed

## Run the server
In a bash terminal, run the server.

    $ rails s

## Usage
Open up another terminal and copy/paste the IP server address into a web browser URL (usually http://localhost:3000) to use the application.

Sign up and login to keep track of and share your favorite tools. Or, you can use this pre-made user account setting to login:

    $ username: lorem
    $ email: lorem@email.com
    $ password: Password1!

## Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/nichia/homecooked.

## License
The application is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...