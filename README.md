Antox
=====

Android client for the Tox project. Still in heavy development. 

####Known to work on
* Samsung S3 running android 4.4 and cyanogenmod
* Galaxy Nexus running android 4.4

####Submitting Pull Requests
- All pull requests must be well documentated before being accepted

###Completed

- Loading and saving of user settings
- Display a welcome screen when using the app for the first time
- Add Friend activity
- Design MainActivity window to hold friends list
- Extended Adapter class for the friends list (show status, online/offline)
- Design ChatActivity window for conversations 
- Extended Adapter class for displaying chat messages (only basic - needs a lot of design improvement)
- Searching through friends list
- Improve the ChatMessagesAdapter ([design goal](http://assets.hardwarezone.com/img/2013/11/messages.jpg)) 
- Store a list of up to date DHT servers (SettingsActivity)

###In Progress

- [Implement jToxCore](https://github.com/Tox/jToxcore)
- Create a singleton for Tox/JTox backend stuff
- Implement all the callbacks 
- Documenting the current code base

###TODO

- Add a QR scanner for adding friends and generating a QR of the users own public key

###Screenshots of progress
<img src="http://i.imgur.com/DQSxfjC.png" width="230px" height="400px"/><img src="http://i.imgur.com/JfX9ZgJ.png" width="230px" height="400px"/><img src="http://i.imgur.com/qQmpODj.png" width="230px" height="400px"/>

####Milestones

- Connect to the tox network
- Working chat
