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

## Data model requirements

* Post relates to single forum category
* Reply relates to single Post
* One Post may have Replies
* One forum category may have Posts
* Forum category must hold at least "Name", "Number of posts" and "Last activity time"
* Post must hold at least "Subject", "Body", "Username" and "Created time"
* Reply must hold at least "Body", "Username" and "Created time"

## Publishing the application

* Publish your source code to github
 * Other git based repository can be used as well
* Deploy application to some web server so Snoobi can play around with it
