# Double R Video Video and Admin Portals

_Evan Rosen's Galvanize Capstone Project_

## Summary

This is a full stack web application for a local video production company that has two main features. First, it enables customers to log into their account, where they can view a list of the videos they have purchased, watch the videos, and purchase additional videos. The second main feature will be an administration portal where the administrator is able to add new videos and customers to the database, as well as manage users and videos to grant or remove access as needed.

## Tech Stack

#### Front End

1. JavaScript
2. React
3. Redux
4. Still Deciding on the styling... maybe Semantic UI, maybe Material UI, maybe Bootstrap... going to build the back end first and then decide this later.

#### Back End

1. Java
2. Spring
3. Authentication? Spring Security or Okta
4. Back end admin portal?
5. Videos hosted on Google Drive - embed videos or use google API?

## User Stories

#### Authentication

1. User will be presented with login page upon accessing the website
2. User will be able to log in with user name and password
3. Authentication to be handled on the back end using Spring Security or Okta
4. User will have ability to reset password
5. User will have ability to register account
6. Once logged in, user will be presented with the User Portal
7. Once logged in, if admin, user will be presented with Admin Portal.

#### User Portal

1. Application will be built using responsive design, ability to view on all devices
2. Layout will be similar to YouTube
3. Page will have top menu with Double R Video branding
4. Top menu will include a small icon including the user name, ability to log in/out
5. Video will be conditionally rendered below the top nav, only displayed if a user selects a video
6. List of items including all the user's purchased videos
7. Stretch Goal: Allow users to view list of videos they do not own including previews and ability to purchase
