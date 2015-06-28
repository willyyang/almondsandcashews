# Meteor Almonds & Cashews

A fun group game where one player is the odd one out - a cashew, and other players are almonds trying to find who is the cashew.


## Disclaimer

This is a a fork of [Spyfall](https://github.com/evanbrumley/spyfall). I modified Spyfall's architecture to create this game. This is an unofficial fan project designed for personal use and is not endorsed in any way by the designer or publisher of the actual game

## Running your own instance with custom locations

[Install meteor](https://www.meteor.com/install)

Clone the repository:

	git clone https://github.com/paulliwali/oddity ./oddity

Enter the oddity directory:

	cd oddity/oddity

Edit the locations file as required:

	nano lib/locations.js

Run the meteor server to test locally:

	meteor --settings settings/example.json

Make a production settings file:

	cp settings/example.json settings/production.json
	nano settings/production.json  # Edit as required

Deploy to meteor:

	meteor deploy myurl.meteor.com --settings settings/production.json

## Links
