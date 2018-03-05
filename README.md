# README

This is an app which is a VERY basic Reddit imitation. The user may sign up, submit a link, and comment on, upvote, downvote links. 

Feedback is encouraged. Find me on Twitter: https://twitter.com/loudmouse312

A few things I'd decided on for this app include: 
- I've used 3 models: link, user, and comment. 
- Authentication is handled with Devise which will allow the user to login and out following signup. 
- I used the acts_as_votable gem for upvoting/downvoting functionality. 
- Basic styling is handled with Bootstrap.

To run locally:
- fork respository
- cd into /reddit_clone directory
- in terminal run: rails s
- in browser visit: localhost:3000




