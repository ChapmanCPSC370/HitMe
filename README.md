HitMe
=====
A Location Based Information Exchange


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


