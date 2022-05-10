# About the project

In essence, the idea is to replace jukeboxes in bars and venues with a mobile application and a RaspberryPi device. The users will be able to purchase tokens to be able to put songs in queue.

## Mobile application and admin panel.
The app handles all user inputs such as searching for a song, putting a song in queue and so forth. The app also sends data to the Firebase cloud database such as how many users in the given bar are using the app. The admin panel is designed for the bar owners and can handle rules like what genres are allowed to be played and in general the same as the app, but for the bar owners. Both these work together with the RaspberryPi device by sending http requests and receiving responses.

## RaspberryPi device.
The RaspberryPi device handles its own API and also sends requests to the Spotify database for track data and manipulation of the playback feature in Spotify so users can play songs in the bar. The RaspberryPi has a sensor connected using motion detection to track how many people are in the bar. It transmits this data to the Firebase cloud database.

## Firebase Cloud Database.
This has all the data stored such as amount of users using the app currently, the amount of people in the bar and user data such as their available tokens and authentication of their login.

![image](https://user-images.githubusercontent.com/59559634/167661290-a672cb70-ff3a-4a09-a070-ce3d1233cd56.png)

