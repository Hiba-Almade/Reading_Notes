## Spring Authentication:

### Authentication and Access Control

`>` Two problems of app security: authentication and authorization

#### Authentication:

main strategy interface for authentication is `AuthenticationManager`

**AuthenticationManager can do one of 3 things in its authenticate() method:**

* Return an Authentication if it can verify that the input represents a valid principal.

* Throw an AuthenticationException if it believes that the input represents an invalid principal.

* Return null if it cannot decide.

`>>` Spring Security provides some configuration helpers to quickly get common authentication manager features.


#### Spring Auth Cheat Sheet

1. set up a user model and repo
2. create a controller for that model
3.  UserDetailsServiceImpl implements UserDetailsService - gets a User from the database by username
4. ApplicationUser implements UserDetails - use IntelliJ to implement the methods; make the boolean ones all return true
5. WebSecurityConfig extends WebSecurityConfigurerAdapter - has a UserDetailsService, passwordEncoder bean, configure AuthManagerBuilde, and configure HttpSecurity
6. registration page - create it with form, ensure it posts to a route your controller is ready for, and check it's saving in the DB
7.  login page - create it with form, ensure it posts to the route you specified in, web config, try it out. 

