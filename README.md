# CS-360-Mobile-Architecture-and-Programming
Applying mobile development principles and best practices to develop mobile applications using user-centered design principles and industry standards. 

# Briefly summarize the requirements and goals of the app
The goal of this project was to design and develop a functional mobile inventory management application. The requirements included allowing users to log in and manage their own inventory while ensuring that each user’s data remains private.

# Features necessary to support user needs 
To support these user needs, the application includes a login and registration screen for user authentication, a main inventory screen that displays items using a RecyclerView, and an add/edit screen for managing item details. The current design focuses on maintaining a simple layout and consistent navigation for ease of use to make tasks quick to execute. 

The development followed a structured and step-by-step approach. I began by implementing basic UI concepts and implementing the database and authentication system. Then I built the user interface, and finally connected functionality through event handling and database operations. 

I also applied object-oriented programming principles and reused code wherever possible to improve organization.

During development, I tested each feature individually. I also used the Android Emulator to simulate real user interaction and verify that the interface responded correctly. This process helped me identify errors early and ensured that the application behaves as expected. 

# Challengers
One challenge I encountered was keeping each user’s inventory data separate. To resolve this, I connected each inventory item to specific usernames and adjusted queries to filter data. 

In addition, implementing SMS notifications introduced another challenge. I had to implement proper runtime permissions handling, which required me to think beyond basic functionality.

One area where I was particularly successful was implementing full CRUD functionality within the inventory system. This demonstrated my ability to connect the user interface with the database and ensure that user actions were accurately reflected in the application. It also showed my understanding of core development concepts such as data persistence, event handling, and user interaction. 
