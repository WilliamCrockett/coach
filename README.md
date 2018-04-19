# Welcome to Coach
## A simple web app designed to help you manage your training sessions
### Currently designed for the RSA Olympic Sailing team. I plan to extend it to other sports in the future.

### [link to api] (https://github.com/WilliamCrockett/coach-api)
### [link to deployed-api] (https://coach-api.herokuapp.com/)
### [link to deployed version] (https://coach.iamwilliam.co.za)

### https://imgur.com/a/FmXhN98

<img src=https://imgur.com/a/FmXhN98
     alt="Screenshot"
     style="float: left; margin-right: 10px;" />

---

## Technologies Used:

* HTML
* CSS/SASS
* Bootstrap
* Javascript
* Ember front end framwork
* Handlebars for rendering data within Ember
* Ember TinyMCE wysiwyg editor: https://github.com/marucjmar/ember-cli-tinymce
* Ember Sanitize and Sanitze.js to protect against malicious script insertion: https://github.com/minutebase/ember-sanitize


## Premise

After years of working with the RSA Olympic Sailing Team, I wanted to build something
that would prove useful for tracking and reviewing training sessions. Hence I've built
this simple web-app which allows users to create and view sessions. I intend to have this
as a closed deployment initially, where users must be pre-approved to access the site.
But an extension of this will include the ability to create Organizations, and users within
Organizations.

## Known issues

* none Currently


## Future release roadmap:

* Export session to PDF
* Graphs and searches (things like program doing the most sessions, average sessions per week). As well as things like ‘get me all the sessions where the rating was 4 or better' type thing
* A race mode. Log information from a race, including different legs and write info on a per-leg basis.
* And results from the day’s mini-series
* Individual objective raating. (currently you can rate the overall session. Allow user to be able to rate each session objective.)
* Stretch/dream goal - integrate with smart watch data for calorie information.
* A mobile app so you can capture a session from your phone, including photo upload. So a coach can log the session as the day is going. Uploads photos from phone as the day is going, etc. This is also a stretch/dream goal.

## Planning information

### [Wireframes](https://imgur.com/HhO4AEi)
### [Wireframes] (https://imgur.com/j1Ek5ae)
### [Wireframes] (https://imgur.com/yd3fDjk)
### [Wireframes] (https://imgur.com/PSX8sNX)
### [Wireframes] (https://imgur.com/5kkg1Lh)
### [Wireframes] (https://imgur.com/S7v6nD0)

### User Stories:

* As a user I want to be able to sign in
* As a user I want to be able to sign up
* As a user I want to be able to change my password
* As a user I want to be able to view a dashboard of information (v2)
* As a user I want to be able to create a new training session
* As a user I want to be able to edit a training session I create
* As a user I want to be able to view other training sessions
* As a user I want to be able to view a list of training sessions by date
*	As a user, I want to change my password, only after logging in
