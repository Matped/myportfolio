# UI example from the app focused on the search feature.'

![image](https://user-images.githubusercontent.com/59559634/167418769-0681a7bb-099c-4964-b442-2aab70177d67.png)

The primary page is determined by which button in the bottom navigation bar has been clicked on. As the 3 different buttons are being switched between, the bottom nav bar will always be visible.

The bottom nav bar is created in the main page and uses a list called "bottomNavBarPages" populated with calls to methods that determine which page will show depending on the clicked button. The variable "bottomNavBarIndex" stores which index number it currently is and the "updateIndex" method gets called and updates the variable as one of the buttons are clicked.

![image](https://user-images.githubusercontent.com/59559634/167421489-50567b50-a2da-4c86-b5c8-d49bc87e92b1.png)

Here a bottomNavigationBar UI element is coupled with the variable containing the index information and the list. The onTap arguement is used to determine which method gets called when any of the buttons are clicked. Under the items arguement is where you create the actual buttons. When all this is coupled together, it figures out automtically which button belongs to what index. In this case "Home" is 0, "Search" is 1 and "Deposit" is 2.

![image](https://user-images.githubusercontent.com/59559634/167419587-507d2a78-d46c-4f64-b747-f9db390cd6e3.png)

When the "Search" button is clicked, it uses this page to return the actual SearchPage, which contains all the UI elements and features to search, display and set a song in queue. The bottom nav bar is still visible and can be switched between.

![image](https://user-images.githubusercontent.com/59559634/167423225-86c18f19-f98d-423a-821f-44d8e1768044.png)


