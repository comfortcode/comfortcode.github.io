---
layout: post
title: Didit
thumbnail-path: "img/didit.jpg"
tagline: Task Management Application

---
{:.center}
![]({{ site.baseurl }}/img/didit.jpg)

{:.center}
_Didit_ is a task management application; with a feature that automatically remove tasks after one week. 

{:.center}
<a href="https://github.com/comfortcode/didit" target="_blank" class="button">View the Repository
  <i class="fa fa-fw fa-github"></i>
</a>
<a href="https://github.com/comfortcode/registry" target="_blank" class="button">View the App Live
  <i class="fa fa-fw fa-external-link-square"></i>
</a>

## Overview
Didit was the first project I created after completing the “Foundation Phase” of Bloc’s “Rails Web Development Track”. Didit is a basic task management application with a twist; the tasks self-destruct after seven days, using an automatic rake task. The proposed purpose of the self-destructing feature was to add urgency, and prevent “to-do list build up”. Users can manage their account information and create, edit, and delete tasks on their to-do list.
  
## Integrated Gems and Services
* Devise - User Authentication
* Bootstrap - Front-end Framework (HTML, Javascript)
* RSpec - Testing Framework
* Figaro - Secure Configurations
* Faker - Generate fake data for testing

## User Stories
* As a user, I want to sign up for a free account by providing a user name, password and email
* As a user, I want to sign in and out of Didit
* As a user, I want to see my profile page (to-do list)
* As a user, I want to create multiple tasks
* As a developer, I want to seed the development database automatically with users and tasks
* As a user, I want to mark tasks as complete and have them deleted
* As a user, I want to see how many days remain before a task is automatically deleted	
* As a user, my to-dos should be automatically deleted seven days after their creation date
* As a developer, I want to automate my delete Rake task to run each day

## Bonus Screenshots
???
![]({{ site.baseurl }}/img/registry3.jpg)![]({{ site.baseurl }}/img/registry4.jpg)

## Conclusion
Developing this application was an enjoyable opportunity to build up a simple CRUD application by implementing page redirects, login functionality and an automatic rake task to create a fully functional service to the user. I also enjoyed implementing a Bootstrap theme, and designing the to do list using Bootstrap and CSS to create an upgraded user experience. 