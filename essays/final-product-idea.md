---
layout: essay 
type: essay
title: "Final Project: Course SNS"
date: 2021-03-30
labels:
  - Software Engineering
  - Meteor
  - React
  - Semantic UI
  - JavaScript
---

Group members include: Chin Ting Liao, John Vicson Suelen, YongU Cho, and Ana Catarina Araujo.

## Overview
The problem: College is a period to study and to search for knowledge, but you do not have to limit yourself to books, do you? This stage is also a great opportunity to meet new people. If you are a student at the University of Hawaii at Manoa, you should probably ask yourself: How will I make friends during college?

The solution: Course SNS aims exclusively in providing a virtual environment where UH Manoa students among all registered courses and majors can interact with each other. Course SNS can also be used to share information about events, services offered by UH, job opportunities, apartments available for rent, talk about courses, projects, assignments, and etc. In this way, improving the integration and approximation at campus so that more students can make relevant content available.


## Approach

Authentication: responsible for validating a user's email and password so that he can access the system. If he does not have an account, he must use "Create Account" to register a new account. If authorized to access the system, then he will be redirected to his profile. 

Home page: On this page, the user can view friend requests and the academic updates his friends recently published.

Add/Remove friends: It is possible for users to add or remove friends from their list.

Allow private messages: Provide a chat function for users to chat in a restricted way.

User’s profile (seen by others): One of the main characteristics of a social network is the possibility to create a profile with personal information. This allows others to view all publications made by a given user. Having a good profile is essential for a user to stand out on the network. A good profile must meet the following requirements: having a username, profile photo that shows who the user is, and have as much information as possible about what is important to the user.

User’s profile (seen by the user): The main functions are Profile, Friends, and Settings. The Profile functionality has the function of viewing the user's own profile, identifying all the publications he has made in the system, and who are his friends. The Settings link allows the user to edit his profile, change his name, photo, welcome message, etc.

Creation of groups: If a user wants to create a new group, he must request it from the administrator (the administrator is the one who is responsible for the website). An example would be a study group for students currently enrolled in ICS 314, where users can teach, learn, and debate about the course.

Some possible mockup pages include:

- Landing page
- Admin home page (get notifications and make community page)
- User Profile page
- Edit Profile page
- Search for the course page (ICS311, ICS314, etc.)
- Course page (Who is in the community, Community chat, Posts, etc)
- Add Post page
- Notify admin page
- Random Profile page (E48C, know someone randomly)


## Use case ideas

- New user goes to the landing page, logs in, gets home page, sets up profile. (How do they learn how the system works?)
- Admin goes to the landing page, logs in, gets home page, edits site.
- User goes to the landing page, logs in, searches for the course, selects the course and participates in the community.
- User logs in, goes to the community page, makes a publication, comments on recent posts.
- Users and admin interact to ban inappropriate usage.


## Beyond the basics

- Individual chat to other users
Possible ones. Not defined yet:
- Dark mode (?)
- "Like" function (?)
- Add/ Delete friends (?)
- Upload pictures (?)
- User’s backlog (to do list) (?)
