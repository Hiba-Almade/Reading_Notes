## Spring

* An application with a static home page, a web page that displays HTML.
* Accepts HTTP GET requests at: http://localhost:8080/Regards

* Starting with Spring Initializr
* Choose either Gradle or Maven and the language you want to use.
* Download the resulting ZIP file, an archive of a web application configured according to your choices.
* Create a web console
* HTTP requests are handled by a controller.

` >` Thymeleaf: is a rendering technique for HTML.

#### Run the app
* You can run the application from the command line using Gradle or Maven.
* You can run the app with ./gradlew bootRun
* You can build a JAR file with ./gradlew build


#### Test Application:
The application can be easily tested using a web browser after running the application by visiting http://localhost:8080


#### Spring Model Attributes
* Spring MVC calls the pieces of data that can be accessed during the implementation of Views model attributes.
* There are several ways to add model attributes to a view in Spring MVC.

* The model attributes can be accessed from the thyme leaf with the following syntax ${attribute name}.