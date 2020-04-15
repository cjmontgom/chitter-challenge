# Shitter

A shit version of Twitter (to learn the basics of connecting to an SQL database when doing web development).


### Quickstart

```
# Ensure you have rbenv and ruby installed globally 

# Clone the repository
git clone https://github.com/cjmontgom/battle-game

# Go inside the directory
cd battle-game

# Install dependencies
gem install bundler
bundle install

# Set up the local database
psql -d postgres -U <your-username>
CREATE DATABASE shitter;
CREATE DATABASE shitter_test;

# Start the development server on port 3000
bundle exec rackup -p 3000

# Go to http://localhost:3000/ in your browser to start peeping

# Be sure to read the terms and conditions

```


Features:
-------

```
STRAIGHT UP

As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a Maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

HARDER

As a Maker
So that only I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

ADVANCED

As a Maker
So that I can stay constantly tapped in to the shouty box of Chitter
I want to receive an email if I am tagged in a Peep
```
