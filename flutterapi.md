# How to do API calls in Flutter and examples of state management in the UI.

## Model class.
- Used to "map" the incoming json data into variables that can be used in the UI.
![image](https://user-images.githubusercontent.com/59559634/167414246-3466214e-779f-49d9-93a8-7749e6c959c1.png)

## The service file.
- Uses fetchCurrentSong method to make a request for the API. Async is neccesary to wait for the response to succesfully complete. It uses an imported library to handle http requests and responses. If succesfull, it decodes the body of the response.
- The updateSong method handles state management and listens periodically every 5 seconds. If there is new or changed data, it will update the state of the data and rebuild the UI specifically where the updateSong method is being used.
![image](https://user-images.githubusercontent.com/59559634/167415618-af06ca77-38ec-4e41-8704-7377bc7ae1bf.png)

## Using StreamBuilder to handle data changes.
- The StreamBuilder uses the CurrentSong model. The stream arguement is set as the updateSong method so it knows where to listen.
- If any changes happen, the builder will rebuild the UI paired with the snapshot, which is used to display the data in a textbox.
![image](https://user-images.githubusercontent.com/59559634/167416305-2b382c77-814f-4e1a-9bb1-74adc8040ee0.png)
