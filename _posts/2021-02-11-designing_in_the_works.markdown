---
layout: post
title:      "Designing in the works"
date:       2021-02-11 06:26:46 -0500
permalink:  designing_in_the_works
---


Coming from Rails to JavaScript was a bit of a steep learning curve. It was a lot to digest in a short period of time. It definitely took time to learn how to use functions, how to use class inheritance, and how to correctly use `this`. But it was also awesome to see how two things connect. How the backend and frontend of programming come together to build beautiful interactive webpages.

For this section of our Flatiron SWE curriculum we were tasked to build a Single Page Application that used Rails as backend and JavaScript as frontend. 

The first thing to do was to create the rails directory. We did that by running `rails new travel-planner-app --api --database=postgresql` . This line allows us to create a full application with all views and things we won't be using, since we will be using JavaScript to manipulate and display content on the screen. So we use the `--api` flag to specify what we want. That will remove a lot of unused code from our application. And then we chose the database we prefer with the flag `database=postgresql`. After a couple minutes, our backend application is all set for us. We can then start building our Models, Controllers, Routes, and our Migrations. 

I have come to learn that set time to plan your application is crucial when building an app. We want to make sure we know what relationships they will have and what type of data we will be handling. That will make setting up our backend so much faster. 

I was not very prepared with my planning, so I ended up having to drop migrations a few times until I got it right. Definitely will be spending more time planning out the application. And it helps to create a visual represantation of what you want your app to look like, and create a visual of your dtabase as well. 

Moving on from the back end to the frontend, I started out by creating the HTML file.I created a complete HTML file with everything I wanted on the page. That way it was easier to use JavaScript to manipulate the DOM(Document Object Model). The DOM is a representation of the webpage, which can be modified or manipulated with JavaScript.

I started out by building the classes for separation of concern. I had two Models on my backend, so I needed to have two classes to handle each of them. All classes were able to reference one another and communicated with a apiAdapter file which was a facilitator to fetch from our database.

A lesson on scope was very important when working with JavaScript. Knowing that variables declared inside a functions would not be accessible from outside the function was helpful and saved me a lot of headache. The use of `this` keyword was essential when wanting to have a variable to be a class variable and accessible everywhere inside that class.

Overall, building this application was very important in my journey in becoming a Software Engineer. I was able to create a simple Single Page Application where users can plan out their next trips. They create the trips and then are able to plan activities. With DOM manipulation the used can do all that without being redirected to another window amd without having to reload the page. 

I am looking forward to the next chapter where we will be learning React and seeing how this lesson on JavaScript prepared me for this.  
