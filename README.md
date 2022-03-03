# Chat-Application-using-JavaScript-PHP-MySQL

In this chat application, when you open it for the first time on the browser, it will show a signup form where you have to signup with your details like name, email-id, password 
and image. Email-Id and image field is fully validated which means you’ve to enter a valid email and an image file only. Once you signed up successfully, you’ll be redirected to 
the user’s page where you can see your full name, image, status(Online/Offline), and logout button at the top, and the other will appear on the bottom if someone has signed up.

On this page, you can see their image, name, status, and the last message if they have sent to you. You have to click on the particular user or you can also search any existing 
user with their name then you’ll be redirected to the chat page and there you can see the image, name, status of that user who is going to chat.

Once you send a message to another user then immediately that message appears in your chat box and another user chatbox too which you’ve sent the message. On the message receiver 
chatbox, this user received the message with the sender image. Remember chatbox will be automatically scrolled to the bottom once the chatbox starts scrolling. 

You can log out from the chat application at any time and once you log out, immediately all other users will know that you are offline.

Once you log out, you can again login and with your email and password that you used when signing up for the form. If you entered the correct credentials then you’ll be redirected 
to the user’s page and all other users will immediately know that you’ve logged in and now active & all the message will be present.


[Installation Part]

Step 1: Install XAMPP 
Step 2: Copy and paste this ChatApp folder in XAMPP->htdocs
Step 3: Start Apache & MySQL
Step 4: Go to your browser & Open the URL -> localhost/phpmyadmin
Step 5: Create a new database with name as ChatApp
Step 6: Click on import option & import the SQL file which is present in the ChatApp folder
Step 7: Open the URL -> localhost/chatapp
Step 8: Your chat application is ready to chat
