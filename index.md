# Manoa Eats

## Table of contents

* [Team Contract](#team-contract)
* [Application Repo](#application-repo)
* [Overview](#overview)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Deployment](#deployment)
* [User Guide](#user-guide)
* [Team](#team)

# Team Contract
Manoa eats is a team consisting of 5 computer engineering and computer science students that have signed this [Team Contract](https://docs.google.com/document/d/1-v9pqiJ7Q1Jij45WQcrJkHYzmSRQN-saOC0DPg8Gzvk/edit?usp=sharing) to follow a work criteria we all decided upon.

# Application Repo
Visit [github.com/manoa-eats/manoa-eats](https://github.com/manoa-eats/manoa-eats) to access our application repo

# Overview
Manoa Eats is a web application that will allow students and staff access to the different eateries information on campus. When they visit our landing page they will notice a search bar in the middle of the page and a collum of the left of the page giving he hours of various eateries. At the top of the page there will be several different tabs which include an All Restaurants tab and I'm Feeling Hungry tab. Once the user signs in or creates an account they will able to have access to a reviews tab.

### The Problem
Not many students know about all of our fine dish eateries on the UH Manoa campus. In addition, some students who want to try new restaurants may not get a chance to because they may have time conflicts with their schedule leaving some restaurants having either too many students in line or not enough students.

### The Solution
Manoa Eats will allow hardworking students to nourish their brains with UH’s nutritious food located all around the campus. Students will be able to upload their schedules along with their course locations, and our website will estimate the best restaurant locations to stop at on their path to their next class.

# Developer Guide
### Installation

First, [install Meteor](https://www.meteor.com/developers/install)

Second, visit the [Manoa Eats application github page](https://github.com/manoa-eats/manoa-eats), and click "Use this template" button to create our own repository initialized with a copy of this application. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

Third, cd into the Manoa Eats app/directory and install the libraries with:
```
$ meteor npm install
```
Fourth, run the system with:
```
$ meteor npm run start
```
If all goes well it will appear at [http://localhost:3000/](http://localhost:3000/)

### ESLint
You are also able to invoke the ESLint command from the command line with: 
```
meteor npm run lint
```
Here is an example showing that no ESLint errors were detected: 
```
$ meteor npm run lint

> manoa-eats@ lint /Users/johndoe/github/manoea-eats/app
> eslint --quiet --ext .jsx --ext .js ./imports ./tests

$
```
ESLint should run without generating any errors 

# Development History

| Milestones | Description |
| --- | --- |
| [Milestone 1](https://github.com/manoa-eats/manoa-eats/projects/1) | **Mockup Development:** Our goals of Milestone 1 was to create different Mockups so we all were able to get a general idea of how we wanted different pages to look. We also needed to create a landing page of our website. The landing page is meant to help users get a general understanding of what our website is about.  |
| [Milestone 2](https://github.com/manoa-eats/manoa-eats/projects/4)| **Data Model Development:** Our mail goal of Milestone 2 was to improve the functionality and quality of or website beyond Milestone 1.  |
|Milestone 3 |   |

# Deployment

We added our current changes into our [Digital Ocean](https://manoa-eats.xyz/#/) where everyone is able to see

# User Guide
### Landing Page
![](images/Landing-Page-Full.png)

On the left hand side of the landing page the user will be able to see the restaurants that are currently open. If the user is craving something specific they will be able to easily find the food by searching for it in the search bar. 

### Sign in Page
![](images/Sign-In.png)
![](images/Signed-In-Page.png)

The user will be able to navigate to the all restaurants tab without being logged in. However, they will not have access to the different reviews that have been left unless they sign in or create an account. Once the user has signed in or created an account they will be able to see all of the tabs in our nav bar. 

### Sign up page
![](images/Sign-Up.png)

If a user does not have an account with us they will be able to create one. All we ask for is an email, password, and for them to indicate if they are a user or a vendor. 

### Logo
<p align="center">
<img src="images/Manoa-Eats-Logo.png" height="500" width="500">
</p>

We also created a new logo that will appear in our top left hand corner. 

### Create a Profile
![](images/Create-Profile.png)

When creating a profile the user is able to tailor their searches to their specific wants. They are also able to add in any diets they may be on which will filter out the different restaurants that fits their needs. A name and profile picture will also be needed when creating a profile. 

### All Restaurants
![](images/All-Restaurants.png)

The all restaurants tab will show all of the restaurants that are available on campus. The user will also be able to filter the restaurants in alphabetical order for an easier search. 


## Team
Manoa Eats is designed, implemented, and maintained by
[Tyler Baguio](https://tylerb8.github.io), [Kristi Chinen](https://kristihchinen.github.io), [Jeraldine Milla](https://itsjerie.github.io), [Nenye Ndili](https://nenyehub.github.io), [Gavin Peng](https://devgav.github.io). 


[manoa-eats.github.io](https://manoa-eats.github.io) is maintained by [manoa-eats](https://github.com/manoa-eats/manoa-eats)
