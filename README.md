rails-training
==============

Write Board training app for rails

Write Board is a messaging board application, people once registered can post any messages in the app, those messages will be publicly visible to all visitors even when they're not registered.

## Specifications:

* Write Board consist of many messages
* Any visitor can view all messages
* To post a message, visitor need to register as a member
* Member data consist of: email, password, firstname, lastname
* Member can change his/her data
* Old password is required to change email or password
* Message can be edited or deleted only by its creator
* Message can be replied by any registered user
* Reply can be replied by any registered user
* Both message and reply need to have at least 3 characters but no longer than 150 characters

## Pages Overview:

* Homepage:
  * Display all messages, newest first, paginated 20 messages per page
  * For non registered/logged in member, display link to sign up and login
  * For logged in member, display link to edit profile, sign out and form to post message and reply
* Registration:
  * Display form to enter firstname, lastname, email, password and password confirmation
  * Password need to have at least 6 characters
  * Upon successful registration, user will be redirected to sign in page with success message
* Login:
  * Display form to enter email and password
  * Upon successful sign in, user will be redirected to homepage with success message
* Edit Profile:
  * Display link to change email and password, when clicked it will show form to enter old password, email, new password and new password confirmation
  * Display form to change firstname and lastname
  * Upon successful edit, user will be redirected to homepage with success message

## Project details:

Create a new rails project under your name, for example
  
  rails new roy

CSS styling isn't required but is a good thing to have to make things neat

Deadline for the project is 1 week since project start