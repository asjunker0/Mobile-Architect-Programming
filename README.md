# Mobile Architect and Programming
CS-360 Mobile Architect & Programming
<br/>
<br/>(From the SNHU CS-340 Syllabus)
<br/>Students will apply mobile development principles and best practices to develop mobile applications using user-centered design principles and industry standards. Upon completion of a fully-functional mobile application, students will conduct security, product assuredness, and compatibility checks before launching the application.

# Course Competencies
This course covers the following competencies, which represent the knowledge and skills relevant to the field:
<br/>Apply mobile application development principles and best practices in the development of a mobile application
<br/>Apply user-centered design principles and industry standards in the development of a mobile application
<br/>Develop and launch a fully functional mobile application


# Software and Tools
<br/> Android Studio: Primary IDE for building, testing, and debugging.
<br/> Java: main programming language.
<br/> XML: Used for creating the layout files.
<br/> SQLite Database: Embedded relational database used for local data storage.
<br/> Android SDK & API Libraries: Core Android APIs provide the functionality for UI management, data persistence, and user permissions.


# Project Overview
__Project Summary__<br/>
My Inventory App is a mobile application designed to help users easily track and manage inventory. It allows users to create an account or log in, add new items, update quantities, and delete items when they’re no longer needed. The app uses an SQLite database for secure and persistent data storage and displays all inventory in a clean, grid-style layout. When an item’s quantity reaches zero, the user receives an in-app alert and, if enabled, an SMS notification. The app includes user-controlled SMS permissions and settings for enabling or disabling notifications at any time. It’s simple, efficient, and built to work smoothly on modern Android devices.
<br/>

__Features__
<br/> User authentication with secure login and account creation
<br/> Inventory management with options to add, edit, update, or delete items
<br/> Persistent data storage using an SQLite database
<br/> Grid-style inventory display using a RecyclerView layout
<br/> Quantity adjustment buttons for quick stock updates
<br/> In-app alerts for low or zero inventory levels
<br/> Optional SMS notifications with user-controlled permission settings
<br/> Settings screen to enable or disable SMS notifications and update phone number
<br/> Local data persistence through SharedPreferences for user preferences
<br/> Clean, simple interface designed for usability and accessibility

# SNHU project questions

__Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?__
<br/> __What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?__
This application had a total of four screens, all of which are important for a user-centered UI. Each screen is simple and follows a single task for the user to utilize if they choose. This type of simplicity cuts right to the chase, where users can get to exactly what they're expecting in each screen.
<br/> __How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?__
A lot of pre-planning was involved in the development of My Inventory App. Initially, I had to come up with a goal or what problem this was solving. I needed to consider what features to implement and if it supports that goal. I had to consider if the user would find these things beneficial. Then I needed to simplify each task and assign it to a screen. I came up with four layouts that did their task and only that. The login screen allows users to login or create an account, the main activity allowed users to manage their inventory, the settings screen allows users to update their SMS notifications, and the add/edit item screen allowed users to update or add an item to the list. After designing each layout, the backend wiring was implemented and the database was developed. This final step was a lot easier with the previous steps involved. Most of the remaining tasks were mundane and didn't take a lot of creativity since it involved wiring buttons to their functions or other interactive pieces to their code. This process is simple and can be applied in several placed, it follows a Plan-Design-Develop step-by-step. This makes it easy to remember and easy to do.
<br/> __How did you test to ensure your code was functional? Why is this process important, and what did it reveal?__
For me, testing the code must happen regularly to ensure everything is working correctly. Each layout had to be tested as I completed the code. I wanted to be sure each button or text box was functional before moving on. I did not want to form a nest of errors at the end caused by negligence in testing. This process is important to prevent bugs and crashes during launch. Its best to hash out potential problems and test the bounds now before it impacts user experience. 
<br/> __Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?__
The biggest challenges were found after the design stages, where I had to 
<br/> __In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?__
