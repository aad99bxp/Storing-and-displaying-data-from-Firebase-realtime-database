# Storing-and-displaying-data-from-realtime-database

This project intends to store and Display data from Realtime Database of Firebase.

The file named Store-data.html is for Storing data which takes the following details:
a) Username
b) Email
c) Name


![image](https://github.com/user-attachments/assets/32f873b0-a8a2-4325-b61e-94b674bc7af3)

The other file fetch-all-data.html fetches all the data from the Firebase Realtime Database.

![image](https://github.com/user-attachments/assets/c9aa2048-457a-4823-945f-3ed00e05c73f)

## To use this code, follow the steps below:

1. Go to Firebase and create a project.
2. Go to the Firebase Console.
3. Click Add project and follow the prompts to set up your project.
4. Once your project is created, navigate to it in the console.
5. Add Realtime Database to the Project:
-In your project, select Build > Realtime Database from the left sidebar.
-Click Create Database.
-Choose a location for the database. Select the Start in test mode option to allow read and write access to the database (useful for development). Click Enable to create the database.
-Configure Database Rules (Optional):

## Copy the Firebase Configuration Object & Replace it in the code.

1. Go to Project settings (gear icon) > General.
2. Under Your apps, select your app (Web, iOS, or Android).
3. Copy the Firebase configuration object (firebaseConfig), which you’ll use to connect to Firebase in your app.
4. Find the follwing Firebase Configuration object in the files and replace with your own firebase configuration object.

![image](https://github.com/user-attachments/assets/b6148bb9-e46c-4c5c-ac49-ae39e70f0fe2)



