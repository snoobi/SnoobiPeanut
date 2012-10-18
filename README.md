# SnoobiPeanut

## Objective

Your objective is to create simple forum where user can:
* Browse forum categories 
* Browse posts within single category
* Create post to category
* Write reply to existing post
* There will be no authentication
** When creating a post, user just gives his/her name to proper field

## Rating

Snoobi will evaluate your code based on following conditions:
* Code structure (MVC or other design pattern)
* End-user usability
* SQL statements
* OWASP top 10 web application risks
** https://www.owasp.org/index.php/Category:OWASP_Top_Ten_Project
* UI can look ugly from the CSS point of view
** Emphasis on the usability rather than "eye-candy"
* Application must work well with newest Firefox and Chrome

## Data model requirements

* Post relates to single forum category
* Reply relates to single Post
* One Post can have zero or more Replies
* One forum category can have zero or more Posts
* Forum category must hold at least "Name", "Number of posts" and "Last activity time"
* Post must hold at least "Subject", "Body", "Username" and "Created time"
* Reply must hold at least "Body", "Username" and "Created time"
