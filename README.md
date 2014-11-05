ShyHi
=====
Mission Statement: 
Our mission is to provide android users the easiest solution to open communication with other android users who are in close proximity. 


Features
========
  

Development Status
==================

Current:
We are currently working on our Minimum Viable Product which is outlined in "Application Features". We are looking for more feature
ideas to add in the future. Do not hesitate to contact us. 

Future: 
After the MVP is completed we will be adding all new features and begin planning for the official application launch. 

View Business Model Canvas: https://docs.google.com/drawings/d/1AztKXoJiuu3lqGtF5Hxkpt8GmunLJhSMcD4bC1kbScw/edit?usp=sharing


How It Works
============ 

Create A Profile: the user will be prompted to create a basic profile that includes: profile picture, full name, email address, and phone number. 
	

Nearby Feed: after creating a profile, users will then be able to see a home page that primarily shows a feed. The feed will show other users in order of proximity to their current location - the user information will show their picture and full name. 


Interaction: after seeing the feed, the user can decide to request that persons contact information or private message them. 
	

Application Infrastructure & Design
===================================
ShyHi will utilize the built in Android Google Play Services for it's location handling. It will store users locations in a web server database via a RESTful service and pull locations using the same service. This is planned to use JSON objects and as such will require usage of Google's GSON library for handling JSONs in Android. The database will be built using a NoSQL database such as MongoDB in order to take advatage of the speed and the simple conversion to JSON objects.

Contributors
============
Jared Stephens

Doug Woodward


