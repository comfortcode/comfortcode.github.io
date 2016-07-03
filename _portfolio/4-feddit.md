---
layout: post
title: Feddit
thumbnail-path: "img/feddit2.png"
tagline: Family-Friendly Reddit Replica
short-description: Feddit is an application where users can post, vote on, share and save family-friendly links and comments.

---

{:.center}
![]({{ site.baseurl }}/img/feddit3.jpg)

{:.center}
_Feddit_ is a Reddit replica where users can post, vote on, share and save family-friendly links and comments.

{:.center}
<a href="https://github.com/comfortcode/feddit" target="_blank" class="button">View the Repository
  <i class="fa fa-fw fa-github"></i>
</a>
<a href="https://feddit-nb.herokuapp.com/" target="_blank" class="button">View the App Live
  <i class="fa fa-fw fa-external-link-square"></i>
</a>

## Overview

I developed Feddit during the guided phase of Bloc’s Rails Web Development Apprenticeship. Each feature of this application was introduced as an opportunity to explore another aspect of Rails application development. Like Reddit, Feddit is an application where users to create, vote on, and share posts; Feddit also incorporates robust application features such as image and email integration to make for a complete, well-rounded product.

## Integrated Gems and Services
* Devise - User Authentication
* Figaro - Secure App Configuration/safely store and access sensitive credentials
* Bootstrap - Front-end Framework (HTML, Javascript)
* Pundit - User Authorization
* Faker - Generating fake data for testing
* Sendgrid - Cloud-based email infrastructure
* RedCarpet - Allow users to style with markdown
* Amazon S3 - Image Storage
* CarrierWave - File uploading
* ImageMagick - Editing and converting images
* WillPaginate - Pagination library
* RSpec - Testing Framework
* Factory Girl - Generating Test Factories
* Capybara - Simulating user interaction for testing 

## User Stories

* As a user, I want to **sign up** for a free account by providing a user name, password and email
* As a user, I want to **sign in** and out of Feddit
* As a user, I want to see an index of all topics and their posts
* As a user, I want to see an index of all posts and their comments
* As a user, I want to **create multiple topics, posts and comments**
* As a user, I want to be the only one allowed to delete and update my topics and posts
* As a user, I want to **"like and unlike"** posts created by other users
* As a user, I want to see a list on my personal profile of the posts and comments that I’ve created
* As a developer, I want to **seed the development database** automatically with topics, posts and comments
* As a developer, I want to **validate** that posts meet specific requirements (length etc.)
* As a user, I want to use **markdown syntax** to format my posts
* As a developer, I want to display posts using any Markdown formatting
* As a user I want to **upload a profile picture** to Feddit
* As a developer, I want to paginate results
* As a user, I want to upvote and downvote posts
* As a user, I want the ability to **flag a post as a "favorite"**
* As a user, I want to receive an email when a new comment is added to a post that I favorited
* As a user, I want the option to opt in or out of receiving emails from Feddit
* As a user, I want to see **public and private topics** and navigate to a private topic's URL
* As a visitor, I do not want to see private topics or navigate to a private topic's URL
* As a user, I want to be **redirected** to the index of topics after I sign-in
* As a user, if I previously voted, I want to see the up/down arrow icon to reflect that they I voted
* As a visitor, I want to see a user's information, posts, and comments on the user’s profile page
* As a user, I want to see a page that displays **active posts** from the past 7 days
* As a user, I want to see a page that displays the most **active users** (ranked by the number of posts plus comments that users have created)

## Conclusion
Developing this application was an important step for me in learning how to build a robust web application. In addition to learning basic development principles and practices, I learned more advanced development techniques such as: user authentication and authorization, sending custom emails with ActionMailer, scoping, integrating ajax to increase page performance, nesting resources and routes, pagination, seeding a development database, application deployment, model validations, simple and complex model relationships (including polymorphism), image uploading and hosting, and TDD principles.