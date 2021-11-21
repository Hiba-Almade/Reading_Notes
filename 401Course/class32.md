
### Intro to Serverless

**What is Serverless Architecture? What are its Pros and Cons?**
* Serverless - is a cloud computing execution model where the cloud provider dynamically manages of servers.
* Traditional vs. Serverless Architecture
    - Traditionally - applications have run on servers which you had to patch, update, and continuously look after late nights and early mornings due to all the unimaginable errors that broke your production.
    - Serverless - no longer need to worry about the underlying servers, and can be worked on at anytime.
* Serverless is reduced cost.

----
**AWS Amplify**

* AWS Amplify - set of tools and services that can be used together or on their own, to help front-end web and mobile developers build scalable full stack applications, powered by AWS. Can configure app backends and connect your app in minutes, deploy static web apps in a few clicks, and easily manage app content outside the AWS console.

----

**API (GRAPHQL)**
* GraphQL Transform provides a simple to use abstraction that helps you quickly create backends for your web and mobile applications on AWS, and define your application’s data model using the GraphQL

* Create a GraphQL API
    - Run this command amplify init
    - Select GraphQl
    - When asked if you have a schema, say No
    - Select one of the default samples; you can change this later
    - Choose to edit the schema, and it will open the new schema.graphql in your editor
    - Save the file and hit enter in your terminal window. if no error messages are thrown this means the transformation was successful and you can deploy your new API.
  