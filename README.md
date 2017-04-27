# Gallery Project

This is a simple Java project which contains REST communication between Android app and Spring MVC web app.

The project contains two subprojects: gallery(Spring) and galleryApp(Android)

Gallery project provides webservices for android app so it's need to be active all the time.

Initial configuration:

1. To provide proper communication with database, proper db connection parameters must be set in spring-security.xml in gallery project.
2. To provide proper webservice communication the webservice url must be set in HttpService in service package(with /webservice pattern).

First of all user needs to lanuch Android app and add it permission for use internal camera.
Then user needs to create a new account, log in and take some pictures wchich will be stored in database.

Then the user is sign in on the webste(parent url of the webapp) and explore his photos.
