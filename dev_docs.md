# Developer Documentation
Welcome to the SheTrains developer documentation!

Currently, only the athlete mobile app has a codebase. The coach dashboard is a series of Figma prototypes which can be accessed from the [wiki](README.md#prototypes).

For more info about SheTrains as a whole, check out our [product page here](https://sites.google.com/view/shetrains).

To clone our codebase and start developing, go to SheTrains' [private GitHub repository here](https://github.com/shetrains-admn/SheTrains) and be sure to check out the [getting started section in the wiki](README.md#get-started).

## Table of Contents

|                                       Sections                     |
|--------------------------------------------------------------------|
|   [Tech Stack Overview](#tech-stack-overview)                      |
|   [Routing/Component Overview](#routingcomponent-overview)         |
|   [Helpers](#helpers)                                              |


## Tech Stack Overview
- [TypeScript](https://www.typescriptlang.org/)
  - Ensures type errors are kept to a minimum 
- [Expo](https://expo.dev/) + [React Native](https://reactnative.dev/)
  - Enables simultaneous Android/iOS development using React principles
- [React Redux](https://react-redux.js.org/)
  - Enables global states
- [tailwind-react-native-classnames](https://github.com/jaredh159/tailwind-react-native-classnames)/[TailwindCSS](https://tailwindcss.com/)
  - Handles the majority of the styling throughout the app
- [Firebase/Firestore](https://firebase.google.com/)
  - Handles authentication and database operations. 

## Routing/Component Overview
![Routing](/docs/assets/imgs/routing.jpg)

- Loading
  - Checks whether the user is logged in, redirects to Login/Main 
- Login
  - Handles signing in via Google using Firebase and Expo authentication functions
  - Redirects to Main after a successful login
- Main
  - Stack navigator
  - Default route is Home
- Home
  - Tab navigator
  - Default Route is Track
- Track
  - Contains the calendar where athletes can click days to enter their symptoms 
- Account
  - Handles user account features
  - Incomplete
- Queries
  - Where athletes would see queries sent by their coach
  - Clicking a query will take them to its respective form
  - Queries are hardcoded
- Symptom
  - Where athletes log their symptoms
- TestForm
  -  Handles form entry for athletes
  -  Form variants are hardcoded, and the form displayed is dependant on an option passed into the route    

## Helpers
- authHelpers.tsx
  - Wrapper for Firestore get/set operations
  - Ensures user is actually authenticated before accessing the database
  - Takes in the navigation object (default on routes) and a callback which takes in the users uid and completes the operation
- dateFuncs.tsx
  - A series of helper functions for manipulating Date objects and getting date strings
- hooks.tsx
  - Custom TypeScript hooks to replace the useAppSelector/useAppDispatch Redux hooks   
- styling.tsx
  - Contains strings made of tailwind classnames for styling 
