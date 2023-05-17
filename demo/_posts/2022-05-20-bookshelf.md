---
layout: demo
title: "Bookshelf website"
name: "bookshelf"
descr: ""
order: 1
link: "http://bookshelf.novalinq.nl"
img: "/assets/projs/bookshelf_thumb.png"
---

This website is used to share study materials ([Novalinq academy](https://www.novalinq.nl/academy){:target="_blank"}).
It is built completely in Django and supports social logins.

The site provides all required functionalities: contact form, a page for the classes one is 
registered in (register token sent via email), a page for the (HTML) documents attached to each class.
A protected admin interface is also available for staffs.

![front_page](/assets/proj_scr/bookshelf-2.png)

### Details

- deployed in Google App Engine
- sends email for confirmation, password reset, token activate
- HTML materials were prebuilt with Rmarkdown
- front-end was built with Django templates

### login/signup pages

![login_page](/assets/proj_scr/login-2.png)
![signup_page](/assets/proj_scr/signup-2.png)