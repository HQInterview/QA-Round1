# QA Round #1

This document explains the requirements for first round of the QA interview.

## Requirements

Since we consider QA very important, we'd like to see how would you start with QA at HotelQuickly.

For that we created a quick overview of our architecture and more detailed questions below.

## Infrastructure overview

HotelQuickly consists of:

* 3 mobile apps (iOS, Android and BlackBerry)
* Backend for HotelQuickly staff
* Extranet for hotel managers
* APIs for the mobile apps to communicate with our Backend
* AppTracker - simple utility to track users' activity from mobile apps, saving the data to database
* Our Backend is connected to other 3rd party services such as
  * 2 incoming payment gateways
  * 1 outgoing payment gateway
  * email sender
  * SMS sender
  * fax sender
  * push notification sender
  * tracking and analytic tools
  * and roughly 10-15 more services

## Question 1

Considering the services we are using, suppose we don't have any QA at the moment. During your first week / month, how would you approach it? What would be your first steps?

### Guidelines

* Please prepare a plan with suggestions and timeline.
* Include info about technologies you would use and write a detailed example for an example you choose
* What input would you need from other people in the company?
* Create a file named ```StartingQaAtHotelQuickly.md``` and use Markdown to format it
* Do not spend more than 2-3 hours on this task
* Commit the file and send a pull request when you are done (with both tasks)

## Question 2

Please download HotelQuickly app:

* iOS: [www.hotelquickly.com/app/ios](http://www.hotelquickly.com/app/ios)
* Android: [www.hotelquickly.com/app/android](http://www.hotelquickly.com/app/android)

and based on what do you see, prepare test scenarios for the app. Note that we're releasing a new build every 2-4 weeks and need to make sure everything is working well.

### Guidelines

* What would you test?
* How would you test it?
* Which tools would you use? Create an example
* Do not spend more than 1.5-2 hours on this task
* How would you test the connection to APIs? How to make sure a release in Backend doesn't break the app?
* Create a file named TestingMobileApps.md and use Markdown to format it
* Commit the file and send a pull request when you are done (with both tasks)

