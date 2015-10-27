##Basic Information
This is my first Ruby App.  

I followed [this](http://guides.rubyonrails.org/getting_started.html) tutorial to get started. 

And I am going to try and build this: [http://www.devwalks.com/lets-build-instagram-in-rails-part-1/]

##Issues I had to resolve
To get to work I had to update mysql type in my gem file to 

gem 'mysql2', '~> 0.3.18'

and then run `bundle install`

Then I had to run: 

```
rake db:create

```
to create a database


