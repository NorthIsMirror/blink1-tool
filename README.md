Command-line Tool for blink(1)
==============================

To build, see the Makefile.





Making it a service on Mac OS X
-------------------------------
(note this is a little stale)

to start:
% launchctl load -w ./com.thingm.blink1.plist
% launchctl start com.thingm.blink1

to stop:
% launchctl stop com.thingm.blink1
% launchctl unload ./com.thingm.blink1.plist
