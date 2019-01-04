# .github.io.
# Site settings
title: Md Taufiq Nasseef
twitter_username: taufiq278
name: Md Taufiq Nasseef
#User specific content
#Links that will appear in the navbar
primarylinks:
 - title: Blog
   url: http://automateddeveloper.blogspot.com/
 - title: GitHub
   url: https://github.com/robhinds
 - title: DZone
   url: https://dzone.com/users/899489/rhinds.html
#Any buzzword skills you want to include
skills:
 - Groovy
 - Spring MVC
 - Spring Boot
#Blogfeed is optional - including this will add JS to call the feed and populate blog list
blogfeed: http://automateddeveloper.blogspot.com/feeds/posts/default
#Work experience is required
roles:
 - title: Post doctoral fellow
   start: 2016
   end: Ongoing
   employer: Douglas Mental health University Institute, Mcgill University, Canada
   description: MRI, Brain connectivity, Opioid drug, resting state
#Education is required
education:
 - level: Doctor of Philosophy (Ph.D.)
   date: 2015
   subject: Cognitive and Brain Sciences
   school: University of Trento
 - level: Master of Science (M.Sc.)
   date: 2012
   subject: Mathematics and its applications
   school: University of Kent
#This section is optional (as is the image link below)
coursera:
   profileurl: https://www.coursera.org/user/i/c6362b4056f755a04bef6a791a62102b
   courses:
    - title: Functional Programming Principles in Scala
      link: https://www.coursera.org/course/progfun
      optionalimage: https://d1z850dzhxs7de.cloudfront.net/topics/progfun/small-icon.hover.png
      date: September 16, 2013
#List of interesting Github repo/projects to include - optional
github:
 - robhinds/twitter-sentiment-analysis
 - robhinds/spring-reactor-twitter
 - robhinds/microservices
#Stackoverflow flair is optional
stackoverflow:
   profileurl: http://stackoverflow.com/users/258813/rhinds
   flairimageurl: http://stackoverflow.com/users/flair/258813.png
#Mobile apps section is optional
apps:
 - name: Chuck the Quiz
   platform: Android
   url: https://play.google.com/store/apps/details?id=com.tmm.android.chuck&feature=search_result#?t=W251bGwsMSwxLDEsImNvbS50bW0uYW5kcm9pZC5jaHVjayJd
   description: A basic early Android app (open sourced)
#An additional info freetext section is optional at the bottom of the page - can be text or HTML
additionalinfo: |
   <strong>JVM</strong>: I am experienced in a variety of Java API’s and frameworks. I have recently worked with Spring 4, Spring Boot, JPA (Hibernate and EclipseLink) in addition to others.  In my current role Groovy is the primary language used - and I am familiar with many of the languages features and quirks (including writing <a target='_blank' href="https://dzone.com/articles/functional-programming-groovy">Functional Programming style groovy</a>).
And that's all that the configuration it takes! The YAML format is pretty readable; it largely just works with indenting. Hopefully, after taking a look over the nested sections of data, it's fairly easy to understand how you can modify parts to make it customizable.

You can see my GitHub CV page here. Out of the box, you can configure lots of aspects: custom text blocks, key skills, blogs, apps, GitHub projects, StackOverflow, etc.

How Can You Have a Custom GitHub CV?
It really is super simple to get your own GitHub CV.

Create a GitHub account (if you don't already have one)
Go to the project repository and fork the repository.
Change the name of the repository (in the settings menu) to {{yourusername}}.github.io.
Edit the /_config.yml file in your repository. It should be pretty straight-forward as to what the links and details are that you need to add.
Visit your new profile page ({{yourusername}}.github.io) and start sharing it!
