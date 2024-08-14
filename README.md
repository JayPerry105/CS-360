# CS-360
Mobile Architect and Programming (Android Studio)



    **Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?**
    
  This app had 6 main requirements for functionality. It needed a database with 2+ tables. One for inventory and one for login credentials. A main login screen. A grid style display to show inventory items. 
  Functionality for adding and subtracting item quantities. Functionality for adding new and removing items completely. Functionality for SMS notifications when an items stock has depleted.
  This app was designed for anyone needing to manage a basic inventory of items. This could be anyone from a small business owner selling a few clothing items to a manufacturing stockroom supervisor.

    **What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?**
  
  I designed the UI of this app while keeping ultimate simplicity for the user in mind. I did not add any more screens and widgets than I saw necessary. There is a basic login screen which also allows the user to create a new account.
  The main inventory screen is a simple grid with item names and quantities. There is a button to add items to inventory buttons to increment, decrement, or delete existing items. There is a button to navigate to the settings screen to check/allow SMS permissions for the app.
  I believe my design was successful in such a way that it left no room for user error. Each screen and button serves an important, yet straightforward purpose.
  
    **How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?**
    
  The project relating to the development of this app helped with my planning for it. Our first project was to pick which app to develop and write how we would want to design it. Project two brought us into Android Studio and had us use the layout editor to fully design the UI while not worrying about functionality.
  Project three was creating the finished product. My first step in project three was to complete all of the layouts first, and then worry about the activities. Of course I had to go back to the layouts periodically to make adjustments, but I believe this technique helped me out.
  I believe following these steps and techniques will help me in any future UI or full stack type development projects. Breaking large projects down into smaller sections has proven to be a successful technique.

    
    **How did you test to ensure your code was functional? Why is this process important, and what did it reveal?**

   Once I was able to run the app on an emulator in Android Studio I tested any new features that I added constantly. I also tested when I made tweaks to existing features. I did my best to imagine I was writing test cases for all methods and tried to re-enact any possible combinations of user
   button presses on the emulator. This technique made me aware of several bugs to fix like my textView to show SMS permissions not being updated after changing the permissions multiple times in the settings.  ?
    
    **Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?**

   The largest challenge for me, by far, was project three. Writing about designing a theoretical app and doing a simple layout with the layout editor was extremely simple compared to when it came time to develop the fully functional app. I had to overcome many challenges and lapses in memory of what we learned
   throughout the course while coding the app. I was constantly referencing the course resources and external resources to make sure my app was functional in every sense of the word. One of the topics I had to repeatedly seek out resources and reminders for was listeners. I kept finding myself forgetting to place
   listeners in the proper locations and wondering why certain features of my app were not responding properly.
    
    **In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?**

   I like to think that my settings screen shows some applicable knowledge and skills regarding mobile app development. I chose to add a seperate screen to give the user more control over enabling/disabling their SMS permissions rather than just the initial pop-up prompt. This required incorporating extra
   callbacks and listeners and another layout, but I beleive that it took the project one step further than required and I am happy with it.
