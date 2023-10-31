# KettlerBikeController
A javascript program that controls a Kettler Bike Ergometer

This is a very simple program that runs in a web-browser and communicates via the USB link to a Kettler Ergometer. It is currently set to control a bike with a fixed data-structure. It only ustilizes a few commands - RS to reset, CM for command mode, PW to set power and ST to get the status.

It currently has a protocol box for a list of duration and power. Duration is in minutes and power in watts, separated by a comma.

You need to connected to a bike first and the click start. If you click start without selecting the bike you get simple fake data.

There is a stop button and a button to download the data to a CSV file for further processing.

That's it!
