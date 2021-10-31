## Spring Boot and OAuth2

#### Examples of single page apps:
* simple - a very basic static app with just a home page and unconditional login Spring Boot’s OAuth 2.0 configuration properties
* click - adds a link that the user has to click to login
* logout - adds a logout link as well for authenticated users
* two-providers - adds a second login provider so the user can choose on the home page which one to use
* custom-error - adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API
#### Each app can be imported into an IDE, and can run the main method in SocialApplication to start an app. They all come up with a home page on http://localhost:8080.
#### Can run all the apps on the command line using mvn spring-boot:run or by building the jar file and running it with mvn package and java -jar target/*.jar.
#### Creating a New Project:
* create a Spring Boot application by go to https://start.spring.io and generate an empty project
*  put these commands into the command line: `mkdir ui` ,  `cd ui curl https://start.spring.io/starter.tgz -d style=web -d name=simple | tar -xzvf -`
* Add a home page - create a index.html
* Securing the application with GitHub and Spring Security
  To make the application secure, you can simply add Spring Security as a dependency.
  `org.springframework.boot spring-boot-starter-oauth2-client`

* Add a New GitHub app