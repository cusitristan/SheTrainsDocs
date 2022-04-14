# Wiki
Welcome to the SheTrains wiki!

You can also check out our [product page here](https://sites.google.com/view/shetrains), [developer documentation here](dev_docs.md) or you may wish to return to SheTrains' [private GitHub repository here](https://github.com/shetrains-admn/SheTrains).

## Table of Contents
|    Section              | Link                                                                                       |
|-------------------------|--------------------------------------------------------------------------------------------|
|    Product Page         | [Product Page](https://sites.google.com/view/shetrains)                                    |
|    Personas             | [Personas](#personas)                                                                      |
|    Market Research      | [Google Docs](#market-research)                                                            |
|    User Feedback        | [Google Docs](#user-feedback)                                                              |
|    Use Case             | [Use Case](#current-main-use-case)                                                         |
|    Design Philosophy    | [Design Philosophy](#design-philosophy)                                                    |
|    Requirements         | [Requirements](#full-requirements)                                                         |
|    Prototypes           | [Figma and Google Docs](#prototypes)                                                       |
|    Presentations        | [Google Slides](#presentations)                                                            |
|    Get Started          | [Get Started](#get-started)                                                                |
|    GitHub Repo          | [GitHub Repo (Private)](https://github.com/shetrains-admn/SheTrains)                       |
|    Development Progress | [Miro Kanban Board](#development-progess)                                                  |
|    Team Contributions   | [Google Docs](#team-contributions)                                                         |
|    Developer Docs       | [Dev Docs](dev_docs.md)                                                                    |
|    Wiki                 | [You're here!](#wiki)                                                                      |

## Personas
To gain perspective on our target users we have created two personas.

The first is Katie and she helps us stand in the shoes of an athlete 
![Athete persona](/docs/assets/imgs/katie_rugby_player.png)

The second is Avi and she helps us see the our app through the eyes of a coach
![Coach persona](/docs/assets/imgs/avi_strength_coach.png)

## Market Research
Our market research can be found [here](https://docs.google.com/document/d/1_obkrHjP5iOUZ2Q-JGU_X8vTIjbpcwR4s2MqTUNNHiw/edit?usp=sharing).

## User Feedback
Our user feedback can be found [here](https://docs.google.com/document/d/1_KWH0lfyA3akdgJwGFHxCtil1POfQ8QoXNo63ExMCQA/edit?usp=sharing).

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

## Prototypes
Our application prototypes can be found [here in the Figma editing mode](https://www.figma.com/file/5Pyjp46OvK1oBDYIykatoO/SheTrains-Prototype).

Our most recent prototype for SheTrains for the athlete-focused mobile app can be found [here](https://www.figma.com/proto/5Pyjp46OvK1oBDYIykatoO/SheTrains-Prototype?node-id=250%3A389&scaling=scale-down&page-id=248%3A68&starting-point-node-id=250%3A389). Check out [Get Started](#get-started) to see how to install the in-development version of Shetrains on your phone.

Our most recent prototype for Shetrains for the coach-focused dashboard can be found [here](https://www.figma.com/proto/5Pyjp46OvK1oBDYIykatoO/SheTrains-Prototype?node-id=582%3A2211&scaling=scale-down&page-id=582%3A2210&starting-point-node-id=582%3A2211).

A full explanation and brief history of what has been implemented in the Figma prototypes can be found [here](https://docs.google.com/document/d/1OiIDcKvZn4npOs_Kk-im-NLK1wx6Or7-hB1xVATzYdc/edit?usp=sharing)

## Presentations

Our most recent presentation of SheTrains can be found [here](https://docs.google.com/presentation/d/11TU_hkToKIVkC5dw11DQNkuDw6Ly1O8s8zWJBCn3lT4/edit?usp=sharing), and an older presentation can be found [here](https://docs.google.com/presentation/d/1LUVmGt--WbwQ2dODBmNgDb2L01qHghVwyP6BGZIMLzo/edit?usp=sharing).

You may also find a presentation of our older vision of SheTrains [here](https://docs.google.com/presentation/d/1dNkHQp1s_kYHDXfFVXeRnpM1mjSNfx-HJK76AULFA3s/edit?usp=sharing), although it no longer reflects the current vision for SheTrains.

## Get Started

:warning: Our development team is currently working hard to develop SheTrains, but it is still under active development. Please see the Figma prototypes on our [product page](index.md) for a demo of what we are striving towards! You may still follow the steps below to try out the SheTrains mobile app for athletes if you'd like.

### Private GitHub Repo Access
You will need to be given permission from the development team in order to get access to the SheTrains GitHub repository. Please contact us for this.

After you have access, running SheTrains is simple: clone the repo, install dependancies, and run the code.

### Clone Repo
In the SheTrains [repo](https://github.com/shetrains-admn/SheTrains), press the ![code button](/docs/assets/imgs/code_button.jpg) button and clone the repo by following one of these three steps:
1. Copy the HTTPS URL and open GitHub Desktop -> File -> Clone repository -> URL -> paste URL and choose location
2. Copy the HTTPS URL -> open a location for SheTrains to be downloaded in your preferred terminal -> run `$ git clone <URL>`
3. Press Download ZIP -> extract the archive to a desired location

### Install Dependencies
Once you have a local copy of the repo you'll need to install dependencies:
1. Open the repo directory in your terminal: `cd SheTrains`
2. Install dependencies: `yarn install`

### Run the Code
Once dependancie are installed:
1. Run the app on your machine using `yarn run`
2. Once the app is running, it will display a QR code similar to the one below
3. Download [Expo Go](https://expo.dev/client) on your mobile device and scan the QR code to run the app on your mobile device
4. Enjoy the sneak peek at what SheTrains has to offer!

![QR_code](/docs/assets/imgs/QR_code.png)

## Development Progess

You can track the development progress of SheTrains on our [Miro Kanban board](https://miro.com/app/board/uXjVOHIqjM4=/?invite_link_id=871805981124). Our long-term strategy for SheTrains' development is continuously evolving as our team progresses through the project milestones; our tickets only reflect what we think is important at each milestone and are subject to change as we make progress and gather feedback.

## Team Contributions
A breakdown of team contributions can be found [here](https://docs.google.com/document/d/11S9Xa3bdAaYhfWwDXiT6zvBAnbTua4WQ0faoHrVRx2w/edit?usp=sharing).
