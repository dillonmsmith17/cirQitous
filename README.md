# CirQitous README

### Dillon Smith and Robert Dorfman


Our application, CirQitous, runs in CS50 IDE using flask. The first page you see
is the login page. If you do not have a login yet, you must register, choosing a
username and password and inputting your weight, height, and DOB for future uses.
The registration link is located as a tab in the top right corner of the website.
After registering, you will receive a confirmation banner as well as an
explanation of what the purpose of the application is. Then you are logged in
and redirected to the main page of the website in which you are prompted to enter
a distance for how far you would like to go on a cardio workout (You must select
values that are multiples of .5 and must specify whether your inputted distance
is in miles or kilometers). After confirming this information, you are sent to a
map. This map will have a red circle of radius equal to the distance you entered
divided by two. The map is centered at your current location. You then click the
small X on the banner that alerts the application successfully found your
location to get rid of the notification pop-up. The purpose of this design (with
a circle of radius equal to distance divided by 2 centered around the user’s
current location) is so that you can select points on or within the circle to go
to and back from, so that your round-trip workout is near the value of the
desired distance.


There is a pin labelled B in the center of the circle, at your location. You can
drag this pin anywhere on the map, and are instructed to drag it to wherever you
would like. As you drag you see the route from your current location to this pin
created. When you drop the pin you can see how far the distance is to go to this
pin and back to your current location in the top right (This is all updated
automatically). You can keep moving the pin around until you are satisfied.
Below the distance (listed both in miles and kilometers) are directions on how
to follow the route.


 If you wish to update your information, you can use the “Update Profile” tab to
 change username, full name, dob, height, and weight. This way, if your body
 type has changed since you made your profile, or you made a typo in registering,
 you can update your information. All you have to do is type in each of the
 fields and click update!
