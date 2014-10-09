HitMe
=====

Current
HitMe is an open source application. The MVP (Minimum Viable Product) will be a simple location exchange: the user will 
be able create a simple profile. The user will also be able to see other users in the area. 

Future
An app that will allow users to message other users that are nearby. It will also allow venues/events/businesses to push
notifications to users that are within its geoFence. 

View Business Model Canvas: https://docs.google.com/drawings/d/1AztKXoJiuu3lqGtF5Hxkpt8GmunLJhSMcD4bC1kbScw/edit?usp=sharing


How It Works
============ 

Create A Profile
	- Full Name
	- UserName
	- Email Address
	- Phone Number
	- Profile Picture 

Nearby Feed
	- List of people nearby 
	- In order of proximity
	- Person Profile
		- Name of person
		- Picture 

Application Infrastructure & Design
===================================
HitMe will utilize the built in Android Google Play Services for it's location handling. It will store users locations in a web server database via a RESTful service and pull locations using the same service. This is planned to use JSON objects and as such will require usage of Google's GSON library for handling JSONs in Android. The database will be built using a NoSQL database such as MongoDB in order to take advatage of the speed and the simple conversion to JSON objects.

Contributors
============
Jared Stephens
Doug Woodward


