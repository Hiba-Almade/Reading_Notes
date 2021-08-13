# Authentication:

## **OAuth**

### What is OAuth?
OAuth is an open-standard authorization protocol or framework that provides applications the ability for “secure designated access.”

### `>` For example:
you can tell Facebook that it’s OK for any app to access your profile or post updates to your timeline without having to give the app your Facebook password. This minimizes risk in a major way: In the event this app suffers a breach, your Facebook password remains safe.

### How does OAuth work? What are the steps that it takes to authenticate the user?

An application or service to obtain limited access to a protected HTTP resource.

* Step 1 – The User Shows Intent.
* Step 2 – The Consumer Gets Permission.
* Step 3 – The User Is Redirected to the Service Provider.
* Step 4 – The User Gives Permission.
* Step 5 – The Consumer Obtains an Access Token.

### What is OpenID? 

OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords.

You may choose to associate information with your OpenID that can be shared with the websites you visit, such as a name or email address. With OpenID, you control how much of that information is shared with the websites you visit.

---

## **Authorization and Authentication flows**

### What is the difference between authorization and authentication?


Despite the similar-sounding terms, authentication and authorization are separate steps in the login process. Understanding the difference between the two is key to successfully implementing an IAM solution.

Let's use an analogy to outline the differences.

Consider a person walking up to a locked door to provide care to a pet while the family is away on vacation. That person needs:

Authentication, in the form of a key. The lock on the door only grants access to someone with the correct key in much the same way that a system only grants access to users who have the correct credentials.
Authorization, in the form of permissions. Once inside, the person has the authorization to access the kitchen and open the cupboard that holds the pet food. The person may not have permission to go into the bedroom for a quick nap. 
Authentication and authorization work together in this example. A pet sitter has the right to enter the house (authentication), and once there, they have access to certain areas (authorization).

![ex](https://techdifferences.com/wp-content/uploads/2018/01/Untitled-4.jpg)

### What is Authorization Code Flow?

Authorization code flow is used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token. A refresh token is valid indefinitely and provides ability for your application to schedule tasks on behalf of a user without their interaction.

### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?


The Proof Key for Code Exchange (PKCE, pronounced pixie) extension describes a technique for public clients to mitigate the threat of having the authorization code intercepted.

The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced “pixy” is an acronym for Proof Key for Code Exchange.

### What is Implicit Flow with Form Post?

The Implicit flow was a simplified OAuth flow previously recommended for native apps and JavaScript apps where the access token was returned immediately without an extra authorization code exchange step.

### What is Client Credentials Flow?

The Client Credentials flow is a server to server flow. There is no user authentication involved in the process. ... This flow is useful for systems that need to perform API operations when no user is present. It can be nightly operations, or other that involve contacting OAuth protected APIs.

### What is Device Authorization Flow?

The OAuth 2.0 Device Authorization Grant (formerly known as the Device Flow) is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token. This is commonly seen on Apple TV apps, or devices like hardware encoders that can stream video to a YouTube channel.

### What is Resource Owner Password Flow?

The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token. This flow has significantly different security properties than the other OAuth flows. The primary difference is that the user’s password is accessible to the application. This requires strong trust of the application by the user.
