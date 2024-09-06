Multiplayer game using Unity and its integration with the Firebase (database) platform for real-time data management.

First Person Shooter multiplayer using Photon's PUN.

To integrate Firebase we import the necessary Firebase packages into our Unity project to store and retrieve the health scores in a real-time database. The Firebase SDK was imported, and FirebaseApp was initialized to establish a connection to the Firebase project. Next, a FirebaseInitializer script is created to initialize Firebase by calling FirebaseApp.CheckAndFixDependenciesAsync(). This ensures that all Firebase dependencies are resolved and the Firebase app is ready to use. Finally, configure the Firebase Realtime Database to set the URL for the Realtime Database. This integration enables us to utilize Firebase services, such as the Realtime Database, within the game.

![image](https://github.com/user-attachments/assets/70df3e4f-88e4-4520-9e8c-6195e511f92e)

