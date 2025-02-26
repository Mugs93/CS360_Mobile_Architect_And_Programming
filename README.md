# Weight Tracker
Weight Tracker was developed to help the user track their weight gain/loss journeys. The user’s data is securely and efficiently saved via an SQLite database where the user can create a login, enter a weight goal, and track their daily weights on their journey to their goals. 
# Key Features
Weight Tracker was designed to be easy to use and understand so the user can get in and out of the app to continue their weight journey. This is done via a few key features: 
-	User created login that saves data via an SQLite database.
-	Home Tab:
	  - Enter goal and add weight buttons that allow the user to enter this information into the database.
    - A scrollable list of all entered weights, with the date they were entered so the user can track their progress. 
    - A progress bar that gives the user a way to visualize their progress.
- Settings Tab:
    - Allows the user to switch between Metric and Imperial systems.
    - Gives the user the option to opt into SMS Messaging, to receive goal and daily weigh in updates.
The simplicity of the design is purposeful, as it makes user interactions with the interface meaningful, so as to not overwhelm the user with bloat. Placement of UI elements are prominently placed for easy access while the scrollable list is clear and chronological, to enhance the user’s experience. 
# Development Process
From the beginning, my thought process was with the user. When developing an application, it is important to try to “step into a user’s shoes” so to say, to get a full understanding of what the user might want, when looking for a Weight Tracking app. As there is a tremendous amount of competition within this app category, it is important to keep the apps goals in line with the users. This means keeping this simplistic and intuitive to use.
Once those considerations are all on the table, it is time to gather the resources needed to complete the task. This includes things like libraries and APIs that are going to make the development process easier. Gathering all of this information before getting started will save a lot of time and headaches in the future. Furthermore, getting a good understanding of the flow of data is important as well, so visual diagramming of those flows is important as well. 
# Testing
Testing is an aspect of development that needs to be considered from the very beginning of the process. Creating unit tests and consistently running the emulator between changes are good ways to combat bugs. Furthermore, having the flow of the application mapped out early, will assist in ensuring that the application is well thought out before any code is written. Furthermore, the use of logging proved to be useful in finding where bugs were occurring, further increasing the detection of bugs. Using these tools is important because a large bug or a cluster of smaller bugs can make or break an application.  
# Challenges
Due to naivete on my part, I ran into many challenges during the creation of this application. Most of my biggest challenges came from the fragments. I had never worked in Android Studio, or with mobile applications for that matter and so I had made some assumptions about data manipulation between fragments, without a parent fragment that sibling fragments could inherit from. This made the implementation of metric and imperial systems more challenging than needed to be. 
# Strengths
I believe that the login screen was my greatest success. It feels intuitive to use and gives the user as much feedback as needed without overwhelming them. I believe that making the buttons non-clickable until the conditions are met can help increase security. Alongside that, all possible outcomes (account already exists, account doesn’t exist, wrong password, and successful login) provide user feedback through toast messages. 
