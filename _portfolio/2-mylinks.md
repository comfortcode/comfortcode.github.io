---
layout: post
title: Mylinks
thumbnail-path: "img/mylinks.jpg"
tagline: Social Bookmarking Application

---

{:.center}
![]({{ site.baseurl }}/img/mylinks.jpg)

{:.center}
_Mylinks_ is a production quality social bookmarking application that allows users to email, manage and share bookmarked URLs.

{:.center}
<a href="https://github.com/comfortcode/mylinks" target="_blank" class="button">View the Repository
  <i class="fa fa-fw fa-github"></i>
</a>
<a href="https://mylinks-app.herokuapp.com/" target="_blank" class="button">View the App Live
  <i class="fa fa-fw fa-external-link-square"></i>
</a>

## Overview

##### Presented Problem:
It's easy enough to bookmark a URL in a browser, but eventually an individual’s  bookmark library gets cluttered, and it may take time and effort to manage bookmarks. We need a solution that allows users to easily add, organize bookmarks and share bookmarks with friends.

##### My Solution:
Mylinks is an app that allows users to create a free profile page where a user’s bookmarks are organized by topic. Bookmarks can be added easily from the user’s profile page, or simply by emailing the topic and bookmark content to the app. The pages are public, so users can share their pages with others who can easily browse- and even “like”- users’ bookmarks.

## Integrated Gems and Services
* Devise - User Authentication
* Figaro - Secure App Configuration
* Bootstrap - Front-end Framework (HTML, Javascript)
* Mailgun - Receiving and tracking email
* Pundit - User Authorization

## User Stories
* As a user, I want to sign up for a free account by providing a user name, password and email
* As a user, I want to sign in and out of Blocmarks
* As a user, I want to see an index of all topics and their bookmarks
* As a user, I want to create, read, update, and delete bookmarks
* As a user, I want to be the only one allowed to delete and update my bookmarks
* As a user, I want to email a bookmark to the Mylinks app, and have it automatically posted to my personal profile
* As a user, I want to "like and unlike" bookmarks created by other users
* As a user, I want to see a list of bookmarks on my personal profile that I've added or liked

## Conclusion
Developing this application challenged me to learn and utilize new technologies to implement higher level features like the ability for a user to email content to the application. During development I also had the opportunity to strengthen my abilities to integrate user authentication and authorization into a multi-layered rails application.