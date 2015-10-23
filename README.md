== README

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


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.

To get to work I had to update mysql type in my gem file to 

gem 'mysql2', '~> 0.3.18'

and then run `bundle install`

Then I had to run: 

```
rake db:create

```
to create a database
