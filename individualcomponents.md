# Portfolio

[About](https://matped.github.io/myportfolio/) - [Project Management](https://matped.github.io/myportfolio/projectmanagement/) - [Individual Components](https://matped.github.io/myportfolio/individualcomponents/) - [Learning Plan](https://matped.github.io/myportfolio/learningplan/)


## Spotify API usage with Python in PyCharm in RaspberryPi.

- Grabbing the user credentials and the scope. The user credentials are supposed to be that of the spotify user playing the music, example is the bar owners spotify account. The scope is what determines which actions are authorized, like putting a song in queue or reading the contents of their playlists.
![image](https://user-images.githubusercontent.com/59559634/165117830-a2dadc04-c90c-4bb9-bee0-e4d5dfef8872.png)

- In a seperate file, the client information is at the moment hardcoded, but it is supposed to be acquired via the local network in the bar.

- Here the class TrackGrabber is introduced and it contains methods directly used within in the Spotify API to get the specified information.
![image](https://user-images.githubusercontent.com/59559634/165118488-6d04604f-64e3-4cd7-a9a3-9d7123fdc4d3.png)

- One of the most important methods for this project is the abillity to search for a track.
- The method has several important parameters that are required. 'q' is the input string acquired from the app, example: 'Kim Larsen - Midt om natten'. Limit is the maximum amount of songs it will return. Offset is where the indexing will start. Type is the type of information returned, in this case it is a track. Market is which market it will choose from.
![image](https://user-images.githubusercontent.com/59559634/165119627-2a1ca4f1-bbbf-4489-af12-5e0250e4bdf6.png)


