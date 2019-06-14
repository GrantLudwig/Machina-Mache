# Machina Máche
![Logo](MachinaMache.png)

# Process Blog
## Problem Statement
We were originally tasked with tackling the problem of data dignity by creating a product or system that helped users to maintain control of their data. Currently, companies mostly have free reign over peoples data that they easily collect and can predict from our actions on thier platforms. Many people today have surrendered to the fact that companies have data on us and are using it for thier own economic gain, with no benefits to us.

We aim to create a product that will allow people to better understand what thier data is being used for and where it ends up. Our main goal is to de-stigmatize Big Data and provide ethical avenues for companies/researchers to collect data. Through brainstorming ideas and multiple interviews with potential users, we created Machina Máche.

## Project Description
We have designed two platforms for both of our different user bases. A desktop webstite for companies looking for a ethical way to obtain data where they can create requests for data. We also created a mobile app for ordinary people to fulfill requests and potentially get compensated for their efforts.
-------NEEDS MORE-------

## Context
This project was created as a part of the User Experience Design course at Seattle University, offered Spring Quarter 2019 through the Computer Science department.

Our group ended up on this idea after reading about an idea similar to ours in a paper called *A Blueprint for a Better Digital Society* by Jaron Lanier and E. Glen Weyl. We all agreed how companies obtained data from users is in a morally gray area and we wanted to find a better way for comapies to obtain data from users, without bascially stealing it from them. Thus we began creating Machina Máche.

## Group Members
- Jack Arnold: arnoldj1@seattleu.edu
- Mitchel Downey: downeym1@seattleu.edu
- Grant Ludwig: ludwigg@seattleu.edu

# Design Process
## Interview Findings
#### ----------------TODO----------------

## Design Sketches
#### ----------------TODO----------------

## Information Architecture
#### ----------------TODO----------------

## User Task Flows
#### ----------------TODO----------------

## Paper Prototypes
#### ----------------TODO----------------

## Findings from User Evaluations
#### ----------------TODO----------------

## Annotated Wireframes
#### ----------------TODO----------------

## High-fidelity Mock-ups
### Interactive mock-ups
- [App Mockup](https://pr.to/NG1HA6/)
- [Desktop Mockup](https://pr.to/2CWV41/)

### App Mock-up
#### Login and Create Account
This is the login and create account screens of our application. Here the user can login to thier account or if they are a new user, they can create an account. Once they are signed in our have completed sign in they will go to the Home screen.

![Login and Create User](Hifi/App/LoginCreate.png)

#### Home
This is the home screen, the main feature of our app. From this screen a user can look at all the requests they qualify for. From this screen the user can open the menu to go to the my account screen, fulfilled screen, and logout. They can also go to notifications in the top right. If they would like to learn more about a request, they can touch the box with the request and the request expands into the screen next to the default home screen. Once expanded a user can read the full terms or go to select photos for the request.

![Home](Hifi/App/HomeFull.png)

#### Request Fulfillment
The first screen shows what will show up when you come to after choosing to select photos from a request. This displays all the photos in your camera roll (which the app will permissions for) which you can select for the request. This screen has been vastly redone because of feedback. We were told the old version had too much on it and it would be simplier to just fully integrate the camera roll into selection. Off of that feedback, we created this new designed screen. Once a user selects the photos they want to send, they can touch send which will display the below popup. After they confirm sending, the last below popup will display on the home screen.

![Request Fulfillment](Hifi/App/Fulfillment.png)

#### App Camera
This is the app camera. Here a user can take photos for a request. Also if the company requires, for example, an eye picture in a specific part of the photo, the app will display a box for the user to focus their eye into. The second screen displays the pictures that you have taken with the camera. Once a user leaves the page, the new pictures will display on the camera roll.

![Camera](Hifi/App/CameraFull.png)

#### My Account
This screen displays a users information. The user can change thier username, email, and password. From this screen the user can also link their bank information or Venmo (do not know if actually possible) for payment.

![My Account](Hifi/App/MyAccount.png)

#### Fulfilled
This screen displays all of a users past requests that they have fulfilled. If touched on, it will expand displaying the information about the request.

![Fulfilled](Hifi/App/FulfilledFull.png)

#### Notifications
This screen is where all notifications for a user are located. This is also another goal of our app, which is to give users updates on how thier data is being used. The four different notification types are displayed below and when one is opened it will go to a new screen with the full information from the notification.

![Notifications](Hifi/App/NotificationsFull.png)

### Desktop Mock-up

#### Landing Page and Create Account
This is the landing page for the webiste, where the user can login if they have an account, or go to the account creation screen to create an account for themselves.

![Landing](Hifi/Desktop/Landing.png)
![Create](Hifi/Desktop/CreateAccount.png)

#### Home Page
This screen is the central home page of the website. It contains navigation tabs on the left to get to various screens, and icons to take the user to the account page and back to this home page. All these navigational buttons are consistent across all screens, except where changing to a screen would not make sense. The Home page contains a small selection of the user's active requests, with a dropdown menu to change how they are ordered. In addition, it contains some simple statistics about the performance of certain requests over the last month

![Home](Hifi/Desktop/HomeScreen.png)

#### Active Requests
This page contains the user created requests that are still active, in that they will be shown to app users. Clicking on the expansion dots on the lower right of each box will expand out to show more detailed data, and allow the user to edit certain parameters of the request or collect submissions from app users. This page, and all the others of similar formats, were significantly redesigned after the wireframing phase. The feedback we received caused us to rethink how the information was presented, and the general design of the request cards

![Active1](Hifi/Desktop/Active1.png)
![Active2](Hifi/Desktop/Active2.png)

#### Past Requests
This page contains the user created requests that have passed their end date. The functionality of this page is identical to the active requests page, excepting that requests cannot be edited.

![Past1](Hifi/Desktop/Past1.png)
![Past2](Hifi/Desktop/Past2.png)

#### Collection Page
This page is where the user can collect the data that app users have submitted to their requests. The data is given through an API key which will not be presented if the promised compensation has not been provided to the submitters.

![Collect1](Hifi/Desktop/Collect1.png)
![CollectUnpaid](Hifi/Desktop/CollectUnpaid.png)
![CollectActive](Hifi/Desktop/CollectStillActive.png)
![CollectAPI](Hifi/Desktop/CollectAPI.png)

#### Create/Edit Request
This page is where  the user can create a new request to be presented to app users to fulfill. They can also edit currently active requests, but are not allowed to change the accessibility of the app users data to other projects or third parties, as that could violate the trust that the submitters had in the requester.The design of the text boxes was changed after the wireframing stage in order to make the design more consistent across the website and the mobile app.

![NewRequest](Hifi/Desktop/NewRequest.png)
![EditRequest](Hifi/Desktop/EditRequest.png)

#### User Account
This page is where the user can view information about their account, change that information, and view some statistics on the activity of their account.

![Account1](Hifi/Desktop/Account1.png)
![Account2](Hifi/Desktop/Account2.png)
![Account3](Hifi/Desktop/Account3.png)
