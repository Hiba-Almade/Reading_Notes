## S3:


### Introduction to Amazon

**What is Amazon S3?**
* Amazon Simple Storage Service (Amazon S3) - is storage for the Internet.
* Amazon S3 has a simple web services interface that you can use to store and retrieve any amount of data, at any time, from anywhere on the web.
* Gives any developer access to the same highly scalable, reliable, fast, inexpensive data storage infrastructure that Amazon uses to run its own global network of web sites.

* Amazon S3 provides strong read-after-write consistency for PUTs and DELETEs of objects in your Amazon S3 bucket in all AWS Regions.

* Amazon S3 offers a range of storage classes designed for different use cases.


### Amplify Storage:
* Amplify Storage category - provides an interface for managing user content for your app in public, protected, or private storage buckets.
* Setup
    - Provision backend storage - execute the command:
      `amplify add storage, and then answer the questions`
    - To push changes to the cloud use the command: `amplify push`
    - Install Amplify Libraries - add these
      `dependencies {
      implementation 'com.amplifyframework:aws-storage-s3:1.17.1'
      implementation 'com.amplifyframework:aws-auth-cognito:1.17.1'`
      }
    - Initialize Amplify Storage - initialize the Amplify Auth and Storage categories you call `Amplify.addPlugin()` method for each category. To complete initialization call  `Amplify.configure()`.
      Add the following code:
      `Amplify.addPlugin(new AWSCognitoAuthPlugin());
      Amplify.addPlugin(new AWSS3StoragePlugin());`

    - Uploading data to your bucket - specify the key and the data object to be uploaded.
    - Upon successfully executing this code, you should see a new folder in your bucket, called public. It should contain a file called **ExampleKey**, whose contents is Example file contents.
