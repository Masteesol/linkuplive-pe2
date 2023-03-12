# About this project

## Background

I am a graduate from Noroff Vocational School studying frontend development. This website is my final degree exam. The backend is developed by the school and we were tasked with making the frontend for a social media platform.

The task challenged students to use HTTP requests like POST, PUT, GET and DELETE to modify posts, comments, reactions, viewing profiles etc. Quite a complex task compared to previous tasks we were given, but a very challenge nontheless.

## User interface

The centerpiece of this app is the idea of having the pages "about", "feed" and "profile" as sections inside a carousel component. The carousel component serves as navigation between the sections. I had done this before with [https://www.eternal-blue.net/](https://www.eternal-blue.net/), a small artist page for a band I have with my wife.

When logged in, the hero banner of the logged in user will serve as a partial background picture behind the navigation carousel. I think if you are going to have a nice hero banner, you should see it youself too. In this way, the user is creating their own personal space in the app.

Many user interaction are done through bootstrap modals. These interactions include viewing profile settings, user posts, adding new posts, commenting, to mention a few.

## Tech used

* React
* styled-components
* react-bootstrap

## End notes

Grade received: yet to be graded.

I wanted to do a lot more with this app. I originally designed a dark/light mode toggle, but due to time restrictions I didn't have time to implement it. There is also me deactivating ESLint in order to being able to deploy the project. I didn't watch for the errors it threw during development as it didn't affect development locally - lesson learnt! I think the UI /UX idea is this projects strongest point.

## How to run the app locally

To run the app locally, simply run `npm run start`. Remember to install the requisite node modules, but running `npm install`.
