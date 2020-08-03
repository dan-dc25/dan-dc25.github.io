---
layout: post
title:      "Rails Portfolio Project"
date:       2020-08-03 04:43:38 +0000
permalink:  rails_portfolio_project
---


The time has come for yet another project with FlatIron School. This project was pretty difficult, in a sense that the requirements are pretty extensive. 
We built our projects on Ruby on Rails framework. 
We needed to stablish the relationships between our Models as to have at least one has_many, on belongs_to and at least 2 has_many through. This would insure that our Models can communicate with one another. 
Use of validations to defende against invalid data.
Provide user authentication, like user login, sigup, password, and logout. I used Devise for user authentication. It took a bit to set up, but following the [Github](https://github.com/heartcombo/devise) instructions and after some work, it was all set to go. Devise creates all the Views related to related to user authentication, which is pretty great. We don't need to edit anything, the forms are all created for us. 
On the subject of User authentication, we must provide login options from other services, like Facebook, Github. Omniauth is an amazing Gem for Rails that lets us use multiple authentication providers. 
We must include nested routes using RESTful URLs. The routes should be related to the parent resource. 
Our forms should display validations errors.

Like I said, the requirements are pretty extensive. And a great opportunity to learn more about the power of Rails and AcriveRecord. 

I decided to create a Health and Wellness App. Where users can join the Wellness community and share recipes and post blog posts about whatever it is wellness related they'd like to share. 

When the user first come to the app, they are greeted by the About page, welcoming them to the community. There is a navigation bar with a button to Login or Signup. Users have the option to create an account by entering their name, email and password, or they can choose to signup through their Facebook or Github accounts. Once the user is signed in, the navigation bar changes and they can see a list of all posts, see a lits of all recipes, see a list of posts and recipes they created themselves, and they can find the forms to create a new post or recipe. 

Users can load all posts, organized alphabetically. They can then view a specific post or click on the user's name and see a whole list of posts published by that user. Users can also comment on each other's posts, and on the post show page, it displays all comments and it has a form for users to leave a comment. 

It is a pretty standard web application, but I am pretty proud I was able to build something that it feels to me production like application. It took a lot of trial and fail to get all models working, but I am happy with the outcome. 
