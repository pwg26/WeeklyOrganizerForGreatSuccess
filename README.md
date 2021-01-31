# WeeklyOrganizerForGreatSuccess

 
Introduction:
This repository contains a daily planner that allows the user to input activities and locally store them in columns and rows based on the time of day. It works by having 3 columns- an hour, the activity, and then a save button to store the activity so that if the page is refreshed the activity will always be there.
 
Motivation:
Everyday life is busy and as our day unfolds, it can be easy to lose track of what is going on. If we use organizers and agendas to mark the events in our lives we lower the margin of error to make sure we are completing our necessary activities. Creating an interacting online one that saves and logs ones activities is an excellent way to accomplish this.
 <img src="https://github.com/pwg26/WeeklyOrganizerForGreatSuccess/blob/main/images/pic1.png">
Development:
To begin I created a row with 3 columns- one for the hour of the day, one for the activity to be written in, and one for a save button. I did this by using the DOM to add tags, add attributes and classes to those tags, then append those tags to other tags to generate my columns and rows for each hour in a regular business day(9-5). 
<img src="https://github.com/pwg26/WeeklyOrganizerForGreatSuccess/blob/main/images/pic2.png">

After this I wrote a function to add a click event to my save button in order to locally store the user's input in the activities column then a if statement to append the those locally stored activities so that if the page were to be refreshed they would still persist. Finally I wrote another function that would color code my activity rows relative to the present, past and future.
 
 <img src="https://github.com/pwg26/WeeklyOrganizerForGreatSuccess/blob/main/images/pic3.png">
 
Usage:
The planner works by the user typing their activity to be completed in the middle row, then simply clicking save. The user can do this for every business hour in a day. The activities can be added and subtracted from at any point and they are displayed as green for upcoming, red for past, and grey for present.
