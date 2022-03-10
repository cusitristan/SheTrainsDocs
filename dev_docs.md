# Welcome to the SheTrains Developent Documentation
Back to [product page](index.md) 
## Get Started
To get started we'll have you clone the SheTrains repo, install dependancies and of course run the code.

### Clone Repo
Press the ![code button](/docs/assets/imgs/code_button.jpg) button and clone the repo either by:
1. Copying HTTPS URL and opening GitHub Desktop -> File -> Clone repository -> URL -> paste URL and choose location
2. Copying HTTPS URL and opening your preffered terminal -> cd into location -> run `$ git clone <URL>`
3. Press Download Zip -> find .zip file -> extract it and place in preffered location

### Install Dependencies
Once you have a local copy of the repo you'll need to:
1. open a terminal and cd to the repo
2. type `yarn install` or `npm install`

### Run the Code
Once dependancie are installed:
1. type `yarn run` or `npm run`
2. once the app is running press w to see app run in a browser
3. or download [expo go](https://expo.dev/client) on your mobile device and scan the QR code to run the app on your mobile device

![QR_code](/docs/assets/imgs/QR_code.png)

## Personas
To gain perspective on our target users we have created personas.

The first is Katie and she helps us stand in the shoes of an athlete 
![Athete persona](/docs/assets/imgs/katie_rugby_player.png)

The second is Avi and she helps us see the our app through the eyes of a coach
![Coach persona](/docs/assets/imgs/avi_strength_coach.png)

## Current Main Use Case

Using the coach persona defined above, Avi. This is the main use case we've defined so far based on our current requirements set. Something to note is that our current requirement set is not the same as the requirements defined below. Below is the **full** set of requirements.

1. Avi signs in
2. See list of athletes
3. Sees dashboard
4. Selects athlete
5. Checks athletes fatigue chart
6. Sees what phase the athlete is in
7. Sees suggestions for that phase
8. Sends “nudge” to athlete
9. Adjusts training plan based on athlete response


## Full Requirements

### Traits:

- Quick and easy for athletes & coaches to use
- Limited manual input
- Very low barrier to entry for each party
- Slick, modern UI
- Simplicity

### Coaching:

- Dashboard
  - Show aggregate data for each/all athletes
  - Data filtering
  - Data sorting
- Show cycle data for individual athletes so coaches can make decisions based off the research surrounding training and the menstrual cycle
  - Where each athlete is in their cycle
  - Symptoms that commonly occur during those phases (submitted by athletes through period tracking companion app)
- Communication Features
  - Coaches can create custom forms to “query” their athletes, mostly based on menstrual cycle info/suggestions
    - Training data - out of scope for the course, but necessary in the future
    - General data
  - Ability to send these forms on a periodic interval set by the coach
  - Forms would be very easy for the athlete to use
    - Sliders
    - Buttons

### Athletes:

- Period/symptom tracking companion app for athletes
  - Calendar view
  - Shows where athlete currently is in their phase based off user input
    - Age, birth control, last period, etc.
  - Can enter symptoms on each day
    - Bleeding, cramps, etc.
  - Potentially mild predictive features
  - View for answering coach “queries”
    - Sliders, buttons, etc.
  - Notifications for coach “queries”
  - Workout tracking - out of scope, but necessary in the future

## Design Philosophy

- Initially, our team was heavily focused around providing value to the athlete
- After lengthy discussion, as well as an interview with a national level athlete, we decided to pivot our app quite heavily
- Instead of focusing on providing value to the athlete, we’re focusing on providing value completely to the coach, specifically, high level coaches
  - High level athletes don’t pay for their training apps/coaches, it’s the team that sponsors them that pays (needs citation)
  - Coaches are more able to use the period tracking information vs. athletes, whose training plan is mostly dictated by their coach anyways
  - At the highest levels, coaches/teams are much more likely to pay for fringe benefits vs. lower level/amateur teams where the difference in performance does not matter as much
- Also deciding to focus on sports where millisecond differences matter
  - Sprinting, cycling, etc.
  - These sports are more likely to pay for very small benefits vs. sports like hockey where these minute benefits would not be very noticeable
