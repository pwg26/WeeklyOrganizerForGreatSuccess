# WeeklyOrganizerForGreatSuccess

Introduction:
This repository contains a daily planner that allows the user to imput activities and locally store them in colums and rows based on the time of day. It works by haveing 3 coloums- an hour, the activity, and then a save button to store the activity so that if the page is refreshed the activity will always be ther.

Motivation:
Everyday life is busy and as our day unfolds, it can be easy to loose track of what is going on. If we use organizers and agendas to mark the events in our lives we lower the margin of error to make sure we are completeing our nessesarry activities. Creating an interacting online one that saves and logs ones activities is an exellent way to accomplish this.

Development:
To begin I created a row with 3 colums- one for the hour of the day, one for the activity to be written in, and one for a save button. I did this by using the DOM to add tags, add attributes and classes to those tags, then append those tags to other tags to generate my colums and rows for each our in a regular business day(9-5). After this I wrote a function to add a click event to my save button in order to locally store the users imput in the activities coloumn then a if statement to append the those locally stored activities so that if the page werer to be refreshed they would still persist. Finally I wrote another function that would color code my activity rows relative to the present, past and future.

Usag:
The planner works by the useer typing there activity to be completed in the middle row, then simpling clicking save. the useer can do this for every business our in a day. The activitys can be added and subtracted from at any point and they are displayed as green for upcoming, red for past, and grey for present.
