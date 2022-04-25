## Get song method.
- This method takes a string input from the app and uses the method inside the SpotifyTrackGrabber class to search for a song.
- It is specified what data it is supposed to take from the search method.
- Returns the data in json format via the jsonify method from the Flask framework library.
![image](https://user-images.githubusercontent.com/59559634/165127471-a1d78ea0-f291-4da5-bc9d-6acb51e4edd2.png)

## Get currently playing method.
- This method uses a method from SpotifyTrackGrabber to find the song being played.
- Specifies which data to grab.
- Returns as json via the jsonify method.
![image](https://user-images.githubusercontent.com/59559634/165130827-026fa78f-ff12-4e3a-a17c-b4b1ad882f24.png)

## Updating the playlist methods.
- Two methods, one to append and one to remove based on the interactions within the app.
![image](https://user-images.githubusercontent.com/59559634/165131138-167ad783-bf1b-43af-abcf-7d5f3ed0dcbc.png)

## Get playlist method.
- Gets the playlist and returns the playlist variable as json via jsonify method.
![image](https://user-images.githubusercontent.com/59559634/165131728-e4abe000-e4c3-4da7-82ff-e8b91ba7d857.png)

## Queue song method.
- Gets the song id and uses SpotifyTrackGrabber method to set the track in queue.
![image](https://user-images.githubusercontent.com/59559634/165131655-9e20bc6f-1446-460e-905c-b2fcf6783eed.png)





