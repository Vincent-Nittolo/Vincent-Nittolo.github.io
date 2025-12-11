# Vincent-Nittolo.github.io

Overview: 
I decided to focus on Android, and the topics I used were data storage, game development, motion sensors, and google notification service. 
The app I made is called Semester, and it is a mon-catcher game. 

Getting started: To make a similar app, you will need to install the latest version of android studio from google, then edit the gradle files to allow the local database to work properly. You can learn more about that here 

https://developer.android.com/training/data-storage/room

Step-by-step coding instructions. This is how the files are structured, with the databse and page files bundled. <img width="304" height="478" alt="image" src="https://github.com/user-attachments/assets/d029503e-5e4f-41bc-bc3c-6f81372a90b7" />

Pages: Each page follows the same format, where each displays images, text, and buttons to get the desired look and functionality. Do not put business logic inside of these pages. Each page will start like this to add the header and footer. 

<img width="563" height="342" alt="image" src="https://github.com/user-attachments/assets/459f3296-8da6-4da5-b514-a37d0b67e59a" />

Header/Footer: I use these for navigation and to display information. This shows how the navigation logic works, where the value of screen changes when a navigation button is pressed. 

<img width="633" height="155" alt="image" src="https://github.com/user-attachments/assets/af44b994-b377-4147-8e44-374e9a966b4c" />

Activity: My activity screen manages the setup of the database, the notifications, and the sensors. It also is in charge of the navigation seen here. 

<img width="666" height="343" alt="image" src="https://github.com/user-attachments/assets/6bfcfe6f-5819-465b-8a2e-b5717b16e7d1" />

Viewmodel: This handles all of the business logic, as well as the variables themselves. This is so all of the information can be contained in one place, and can be changed without having to change anything in the screen files. 

Drawable: All of the photo assets should be located in the drawable folder. 

<img width="257" height="408" alt="image" src="https://github.com/user-attachments/assets/cb6719e9-6d77-490e-8325-bbd001a691cc" />

Raw: All of the audio files are located in this raw folder. 

<img width="186" height="166" alt="image" src="https://github.com/user-attachments/assets/acfe7e0a-c441-4ba5-a16d-a0f61e4cb96f" />

Further Discussion/Conclusions: I think the main strategy when working on an app is to organize it so it is scaled more easily. Much of my work on the project was redoing older sections of code that I wrote not knowing that it will need to be improved on later, or when it restricted later functionality. 

See Also Section: I think the best tutorials can be found here in the lecture notes, as you know the code was written by a professional (the proffessor). 

https://dulimarta-teaching.netlify.app/cs357/lecture-notes.html

https://docs.google.com/presentation/d/1HJUYwKcTg0lA98VmxLSDRVWVwCvIJRziQgOcCHs_Wsc/edit?usp=sharing
