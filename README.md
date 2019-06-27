# Reminder-App
This is a basic reminder app which takes in data(Date, Time and Message) from the user and notifies the user on the given date and time.
<br><br>
In this app, I have used ***Room Database*** for storing the data of the reminders. The user is being notified by a notification which contains the message entered by the user. 
We have been using ***AlarmManager*** which fires a ***PendingIntent*** which in turn call a ***BroadcastReciever*** that creates a notification for the user with the message.
<br>
* Adding Reminder<br><img src="https://github.com/vaibhavjain30699/Reminder-App/blob/master/Screenshot%20from%202019-06-13%2011-58-39.png" alt = "Adding Reminders" width=200 height=350>
* All the reminders which haven't been notified<br><img src="https://github.com/vaibhavjain30699/Reminder-App/blob/master/Screenshot%20from%202019-06-13%2012-06-28.png" alt = "Adding Reminders" width=200 height=350>"
