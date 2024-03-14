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
Following the guide below 
https://guides.rubyonrails.org/getting_started.html 

## Currently on step 7.2 of the guide

Commands to note 
# Tips 
  - if server won't restart kill the pid with this command `kill -KILL PID_NUMBER`

# Make a controller 
  - bin/rails generate controller Articles index --skip-routes

# Make a Model 
  - bin/rails generate model Article title:string body:text

# Migrate to a database 
  - bin/rails db:migrate

# launch the console
  command to a launch
    - bin/rails console

  used to add to add items to database 
  example: 
    1. article = Article.new(title: "Hello Rails", body: "I am on Rails!")
    2. article.save 
    3. Article.find(1) ( check to see if it appears ) 
      OR Article.all
    
