# SnoobiPeanut

## Objective

Your objective is to create simple forum where user can:
* Browse forum categories 
* Browse posts within single category
* Create post to category
* Write reply to existing post
* There will be no authentication
 * When creating a post, user just gives his/her name to proper field

Application must be written in PHP 5.3.6 (or higher) and MySQL 5.1.53 (or higher)

## Rating

Snoobi will evaluate your code based on following conditions:
* Code structure
* End-user usability
* SQL statements
* Application security
* UI can look ugly from the CSS point of view
 * Emphasis on the usability rather than "eye-candy"
* Application must work well with newest Firefox and/or Chrome
 * Forget IE :)

## Rules
* Third party libraries are allowed to use
* You must code the application yourself
 * No copy-pasting from external projects
* Database abstraction can be utilized
* Comment your code blocks

## Data model requirements

* Post relates to single forum category
* Reply relates to single Post
* One Post may have Replies
* One forum category may have Posts
* Forum category must hold at least "Name", "Number of posts" and "Last activity time"
* Post must hold at least "Subject", "Body", "Username" and "Created time"
* Reply must hold at least "Body", "Username" and "Created time"

## Deliverables

* Publish your work to github (or send via email)
 * Source code
 * Database schema
 * Documentation
* Deploy application to some web server so Snoobi can play around with it
* Inform Snoobi (jobs at snoobi.com) when your application is ready
