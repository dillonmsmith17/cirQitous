# CirQitous Design Document

### Dillon Smith and Robert Dorfman

Our application is based off of a similar platform to pset 8’s cs50 finance. We
used flask to set up the web server on which our application can exist using the
CS50 IDE and followed an MVC structure design in the implementation of our
application.


For the model section, we linked our website to a SQL database containing user
information called “cirQitous.db”. The purpose of this was so that we can
further implement new functionality in further iterations of the application (a
history tab, a structured workouts functionality, etc.).


Regarding the “View” section, we used the Google Maps API and associated
functions to implement cirQitous. We looked into different functionalities we
could implement using this API and settled on geolocation, shape overlays, and
draggable points to make the application as useful and customizable as possible
for the users. In setting up our layout file, we altered the header to
accurately reflect our application name and an icon more suited to its purpose,
and we put the name and proper tabs in the banner at the top of the page. Also,
the footer was altered to reflect the source information and terms of use for
the Google Maps API. We also used JSON to implement our check function, as was
used in pset8. We used Jinja to connect our templates with our layout structure,
and used html with CSS to structure the interface. Javascript created the
interactivity and reactivity of the web page, ranging from drag and drop Maps
pins to monitoring required fields in the various form inputs throughout the
site.


Finally, for the controller, we faced some difficulties we had not anticipated.
The maps API required that we use HTTPS rather than HTTP so that we could access
locations, and in order to do so we downloaded SSLify using pip in order to
initialize the app via flask with a secure server.
