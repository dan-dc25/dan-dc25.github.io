---
layout: post
title:      "The Learning Curve"
date:       2020-05-24 18:03:43 +0000
permalink:  the_learning_curve
---


“What a miracle it is that out of these small, flat, rigid squares of paper unfolds world after world after world, worlds that sing to you, comfort and quiet or excite you. Books help us understand who we are and how we are to behave. They show us what community and friendship mean; they show us how to live and die.” -Anne Lamott

For my second project with Flatiron School, I was tasked with creating an application with Sinatra and ActiveRecord. ActiveRecord is used with web applications to store or persist data in relational databases. I used the CRUD (Create, Read, Update, and Delete) pattern within [ActiveRecord](https://en.wikipedia.org/wiki/Active_record_pattern).

I decided to create an application where users can add their favorite books and create a "favorites list". The user can also access favorites lists created by other users and add books to their favorites list as well. There were so many other applications I could have built, but I find books magical, especially in times like these. Books transport us to different times, better places. 

When the user first visits my application, they are welcomed with an “About” page. There is also a navigation bar where the user can sign up or log in. If the user isn't signed up yet, they can click the “Sign Up” button and they are taken to the “Sign Up” page. Once there, the user can create an account with an HTML form. In my Sessions Controller, I used the “Create” part of CRUD to render the form and "POST" to persist the information entered by the user, creating an instance of the User and saving it to the database.

I used "helpers" methods for some of the logic in the application. One helper method is responsible for verifying if the user is logged in before displaying any information. If the user is not logged in, they are redirected to the “Log In” page. If the user is logged in, the “About” page is displayed. 

Another use of the “Create” functionality is on the Books controller. When the user creates or adds a new book, the book is automatically added to that user's favorites list. Once added to the favorites list, the user has the ability to edit the book. They can change the name, genre, and then submit the edits. The user can also remove a book from their favorites list. Removing a book from the favorites list will not delete the book—it will still be available for all users to see and add to their own favorites lists. 

If the user wants to permanently delete a book, that is done through the other functionality of CRUD, the “Delete” action. Once a book is selected, there is an HTML update form with a POST method with a value of “DELETE.” The user sees a "Delete" button that, when clicked, submits the form and completely deletes the book from the application.

For this project, I was also given a bonus challenge. The bonus challenge was to display an error message if the user performed an action that was not allowed. As a beginner, I was afraid of attempting this bonus challenge because building complicated applications can get often confusing. However, after reading about how another student used Flag::Flash, I decided to implement Flash on my application as well. Flash is a method to render saved messages that can be displayed to the user. For instance, if the user clicks on their favorites list but hasn't added any books yet, the application displays an error message. My job, aside from writing the code, is to think about how the user interacts with my application, so successfully completing the bonus challenge was a very rewarding experience for me. 

Needless to say, I have learned so much during this project. I am so thankful to Flat Iron School and my instructors for pushing me to give my best, especially in the midst of this pandemic. They have been quick to adapt and help me through these challenging times. I am excited to see how the next few months of learning will look!
