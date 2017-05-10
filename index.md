

# About Rude-Oh-Villanueva

Rude-Oh-Villanueva is our homepage for our group project for ICS 314 Spring 2017 semester.  The team consists of Jacob Rude, Christopher Oh, and Aaron Villanueva.  We will be creating a functioning version of Club Hub as described in the next section of our website.  

# Project: Club Hub

## Overview

The problem: UH Manoa has over 200 Registered Independent Organizations, plus many more that do not have this “official” status but are nonetheless active organizations. Unfortunately, there is no easy way for students to learn (a) what student clubs (both registered and unregistered) exist, what they do, and how to get further involved.

The solution: The Club Hub application will provide a centralized directory for UH Manoa student clubs. UH Manoa students can login to browse a well organized directory of all current student clubs, with brief descriptions, meeting times and locations, URLs to their websites (if any), contact information for officers, and a few select photos.

Club Hub has three user roles, all of whom login with their UH ID. Regular users browse the directory. Admins make sure site content is appropriate and grant “club admin” privileges to selected users. Club Admins have the ability to edit the data associated with their club.

The site should not simply support browsing by a list of clubs in alphabetical order, but should also allow filtering by interest area. For example, “athletic” clubs, “art” clubs, “music” clubs, etc. A club can belong to multiple interest areas.

Users can specify interest areas, and be notified when a new club is created matching that interest area (or an existing club adds that interest area).

Admins can monitor the site for inappropriate content, create new categories of musical tastes, capabilities, and goals, and ban inappropriate users who violate the Terms of Use.

Upon first login, all users must agree to Terms of Use before they obtain access to the system.

## Mockup page ideas

Some possible mockup pages include:

* Public Landing page
<img width="1440" alt="screen shot 2017-04-13 at 12 02 24 am" src="https://cloud.githubusercontent.com/assets/22675838/25000319/84f6096e-1fdc-11e7-8149-fe734e9e0c21.png">

* Login page
* User home page
<img width="1440" alt="screen shot 2017-04-13 at 12 00 36 am" src="https://cloud.githubusercontent.com/assets/22675838/25000259/5a3bf8c8-1fdc-11e7-9a5c-b05f2daffc22.png">
* Admin home page
* Club admin home page.
* Browse clubs by interest area(s).
<img width="1440" alt="screen shot 2017-04-13 at 9 46 11 am" src="https://cloud.githubusercontent.com/assets/22675838/25021554/4bcc0646-202e-11e7-802d-f9563cbfda68.png">


<img width="1440" alt="screen shot 2017-04-13 at 9 46 03 am" src="https://cloud.githubusercontent.com/assets/22675838/25021549/496a0b46-202e-11e7-8f01-c65498d91e7a.png">
## Use case ideas

Whether or not the following bullet points list all pages or not, the completed use case should show an end-to-end scenario of using the system.

* New user goes to landing page, logs in, gets home page, sets up profile. (How do they learn how system works?)
* Admin goes to landing page, logs in, gets home page, edits site.
* User goes to landing page, logs in, looks for clubs of interest.
* Club admin goes into site, updates their club profile.

## Beyond the basics

After implementing the basic functionality, here are ideas for more advanced features:

* Notify admins when club data changes so they can review for appropriateness.
* Provide “expiration date” for club listings (either one semester or one academic year). To retain a listing, the club admin or admin must login and click a “renew” button for the club to re-list it in the site.
* Allow students to rate clubs.

# Milestone  one
Milestone ones goal was to create the mockup pages for the website.
None of these pages have functionality but, will in the upcoming milestones.

## Landing Page
<img width="1440" alt="screen shot 2017-04-13 at 12 02 24 am" src="https://cloud.githubusercontent.com/assets/22675838/25000319/84f6096e-1fdc-11e7-8149-fe734e9e0c21.png">
## Home Page
<img width="1440" alt="screen shot 2017-04-13 at 12 00 36 am" src="https://cloud.githubusercontent.com/assets/22675838/25000259/5a3bf8c8-1fdc-11e7-9a5c-b05f2daffc22.png">
## Edit Club Page
<img width="1440" alt="screen shot 2017-04-13 at 9 46 11 am" src="https://cloud.githubusercontent.com/assets/22675838/25021554/4bcc0646-202e-11e7-802d-f9563cbfda68.png">

# Milestone two

For this milestone we decided to do two things, implement functionality to the add club page, and add a CAS login system.

## Add Club Functionality.  
First, we decided to implement the functionality of the Add Club page, this task was assigned to Aaron Villanueva.  Now with the new implemented functionality, a user can add a new club, select the appropriate category, choose a meeting time, and submit a short bio describing the club.
<img width="1440" alt="screen shot 2017-04-27 at 6 03 23 pm" src="https://cloud.githubusercontent.com/assets/22675838/25513891/47110290-2b74-11e7-99a2-0a096e296502.png">


## CAS Login 
Second, we decided to implement the CAS login system for our website, now users have the ability to login and view clubs with their own person University of Hawaii login.  Originally this was assigned to Jacob Rude, but a bug persisted in trying to get it finished.  Christopher Oh, was able to bug fix the code and complete it.  We decided to commit Chris's branch as that was the one that worked.  Users can click the login button in the top right of the screen and login with their student account.


## Project Management

<img width="1440" alt="screen shot 2017-04-13 at 9 46 11 am" src="https://raw.githubusercontent.com/Rude-Oh-Villanueva/Rude-Oh-Villanueva.github.io/master/images/M2_project.PNG">
<img width="1440" alt="screen shot 2017-04-13 at 9 46 11 am" src="https://raw.githubusercontent.com/Rude-Oh-Villanueva/Rude-Oh-Villanueva.github.io/master/images/M2_issue.PNG">
<img width="1440" alt="screen shot 2017-04-13 at 9 46 11 am" src="https://raw.githubusercontent.com/Rude-Oh-Villanueva/Rude-Oh-Villanueva.github.io/master/images/M2_network.PNG">


To view the website, [Click Here](http://clubhub.meteorapp.com/) .
To view this milestone's progress and issues, [Click Here](https://github.com/Rude-Oh-Villanueva/Club_Hub/projects/2) .

# Milestone three

For this milestone we had to do two things.  First we had to continue to close out as many issues as possible to help complete the website and maximize its functionality.  Second, we needed to collect user feedback on the website.

## Database

We implemented and finished putting together the data-base for our add club featue, now whenever a user added a new club to the website it will be saved and can be viewed by other users.

## User Feedback

For this milestone we had a total of five people report feedback on the website, this included: Robert Figgs, a former ICS 314 student and Computer Sciences major.  Kahlin Baughman, a Computer Sciences major who has yet to take ICS 314, Bret Armstrong, a Math major who has dabbled in algorithmic analysis, Steven Braun, a previous ICS 314 student and Computer Sciences major, and Miles Provincer, a Music major and vocalist.  One of the underlying themes during the testing of the project was more personalization.  Having the ability to add pictures to the club pages and have user profiles with maybe a headshot picture would have been a huge plus.  Unfortunately, it did not make it into this deadline, but if we were to do it again we would add some of this user customizability.  Overall I heard some good comments, Miles Provincer said "The site is very smooth and makes navigation easy, even though there is a minimalistic feel to it, it makes viewing and using the website more streamline".  

We wanted to stress a diverse userbase in asking for input on our website, not only were computer scientist good for finding some minor bugs and details, but other users who were not familiar with coding were very helpful in bringing to life bigger details in what could be done in the future.

<img width="1680" alt="screen shot 2017-05-09 at 2 24 37 pm" src="https://cloud.githubusercontent.com/assets/22675838/25878062/a4a2c918-34c3-11e7-9ed5-4c3defed696a.png">

# Commit Data 

<img width="1680" alt="screen shot 2017-05-09 at 11 07 02 pm" src="https://cloud.githubusercontent.com/assets/22675838/25891345/71e05786-350c-11e7-97c5-fd63bb654600.png">
<img width="1680" alt="screen shot 2017-05-09 at 11 07 49 pm" src="https://cloud.githubusercontent.com/assets/22675838/25891350/73d12c3c-350c-11e7-8c94-7791a15f1e94.png">



## Up to date screenshots of the Website

<img width="1680" alt="screen shot 2017-05-09 at 2 25 15 pm" src="https://cloud.githubusercontent.com/assets/22675838/25878041/82b69c9e-34c3-11e7-801d-65d74b682b1a.png">
<img width="1680" alt="screen shot 2017-05-09 at 2 25 25 pm" src="https://cloud.githubusercontent.com/assets/22675838/25878046/8c04b92a-34c3-11e7-9f6e-b6c8385986fc.png">
<img width="1680" alt="screen shot 2017-05-09 at 11 00 24 pm" src="https://cloud.githubusercontent.com/assets/22675838/25891052/60a6861c-350b-11e7-9d27-86dae1fcb633.png">
<img width="1680" alt="screen shot 2017-05-09 at 2 25 34 pm" src="https://cloud.githubusercontent.com/assets/22675838/25878050/8fe16962-34c3-11e7-968c-9b7a297abdd3.png">
<img width="1680" alt="screen shot 2017-05-09 at 2 25 40 pm" src="https://cloud.githubusercontent.com/assets/22675838/25878052/91998668-34c3-11e7-8478-3830269d61f6.png">

To view the website, [Click Here](http://clubhub.meteorapp.com/) .
To view this milestone's progress and issues, [Click Here](https://github.com/Rude-Oh-Villanueva/Club_Hub/projects/3) .

# Installation

First, [install Meteor](https://www.meteor.com/install).

Second, [download a copy of ClubHub](https://github.com/Rude-Oh-Villanueva/Club_Hub.git), or clone it using git.
  
Third, cd into the app/ directory and install libraries with:

```
$ meteor npm install
```

Fourth, run the system with:

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000). If you have an account on the UH test CAS server, you can login.  

## General Links

To view the website, [Click Here](http://clubhub.meteorapp.com/).

To view Milestone One, [Click Here](https://github.com/Rude-Oh-Villanueva/Club_Hub/projects/1) .

To view Milestone Two, [Click Here](https://github.com/Rude-Oh-Villanueva/Club_Hub/projects/2) .

To view Milestone Three, [Click Here](https://github.com/Rude-Oh-Villanueva/Club_Hub/projects/3) .









