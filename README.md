# Android-Invintory-App


<img src="inventory_app_login.png" alt="inventory_app_login" width="200"/><img src="inventory_app_home.png" alt="inventory_app_home" width="200"/><img src="inventory_app_additem.png" alt="inventory_app_additem" width="200"/><img src="inventory_app_settings.png" alt="inventory_app_settings" width="200"/>



<img src="inventory_app_xml_example.png" alt="inventory_app_xml_example" width="500"/>



### Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The goal of this application is to be used to track items in a warehouse. To meet user needs this application includes the following:

- A database with at least two tables, one to store the inventory items and one to store user logins and passwords
- A screen for logging into the app. Note that this should also be used to create a login if the user has never logged in before.
- A screen, with a grid, that displays all items in the inventory
- A mechanism by which the user can add and remove items from inventory
- A mechanism by which the user can increase or decrease the number of a specific item in the inventory
- A mechanism by which the application will notify the user when the amount of any item in the inventory has been reduced to 0 (zero)

### What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
Login:
- Fields for the user to provide a username and password
- A button for the user to submit their username and password
- A button for the user to create a new login if it is their first time using the application


Display database:
- A grid for displaying data
- Logical labels and headers for the data that will be displayed
- A button for adding data to the grid
- A button on each row for deleting that row of data from the grid
- A mechanism that allows a user to change the value associated with each grid item (e.g. the number of a specific item in an inventory or the date of an event)

Settings (SMS messaging):
- A button, or alternate mechanism, that would cause the app to ask a user for permissions so it can communicate with SMS messaging. 

My UI designs keep users in mind by focusing on content order, grouping, and transitions. Additionally, I focused on the Android Developers design guidelines for visual and navigation patterns along with the quality guidelines for compatibility, performance, security, and more.

### How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
To ensure that my code, apps, and software I write are maintainable, readable, and adaptable it is important to evaluate the requirements from the user. I followed the classic Software Development Life-Cycle (SDLC), by building the project in smaller sections it allowed me to meet smaller goals and easily combine the project together at the end. My design approach can easily be applied in future work. Making sections of my code modular and repeatable is a tatic that saves time on future projects.

### How did you test to ensure your code was functional? Why is this process important and what did it reveal?
Using Android Studio's built in Emulator allows for you to run code on a device to test the different components of the application.

### Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
I have never created an app or coded using Android Studio before, so the largest challenge for me was learning a new tool. Overcoming the challenge of using a new tool can be difficult, however, for me it is trial and error.

### In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The specific component from the mobile app that I demonstrates my knowledge, skills, and experience the best is the connection to the database, focusing on the fundamentals of C.R.U.D. (Create, Read, Update, Delete) gives us a systematic approach of creating and testing a database on a high level.


