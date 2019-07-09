# SeatPlannerApp
Project Name: Seat Planner

Objective: To create a multi platform mobile app powered by react native and firebase which provides innovative seat planning solution to big organisations having multiple office buildings with many floors.

Identified problem: Big companies/organisations may have multiple office buildings with large number of employees working in those buildings at different floors. It becomes really tedious task to allocate cabins/seats in such a complex system. The current solution is manual one, which uses excel sheets and bulk email services, which is not so efficient and prone to error.

Proposed solution: To tackle this problem, we propose a mobile app where the organisation or company can login and put all the details and data about their office buildings and employees. Once all the data is fed in the app then through easy interface of app, organisations can allocate employees their designated seats without much hassle. 

The working and features of app:

|Components|Functionality|
|---|---|
|SplashScreen.js|
It’s the very first screen which opens when app executes. It determines whether the user is logged in or not. If the user is not logged in It navigates to the Auth.js component (Login screen) else it navigates to the Home.js component (Dashboard screen).|
Auth.js
Login screen where user can put email address and password to sign in the app.
Home.js
It’s provides the dashboard screen where user can do following things:
 -View Offices
 -View Seat plans specific to selected office
 -Press button and edit office list
 -Press button and edit seat plans
AddOffices.js
In this component user can edit or add new offices.
AddSeatPlan.js
To add and edit seat plans
AddSeatPlanDetails.js
To add and edit seat allocation details of a seat plan.
SendEmail.js
To send email to the employees stating their allocated seat for a specific date.



