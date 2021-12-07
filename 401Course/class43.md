### Amplify and Kinesis:

  * Analytics category - enables you to collect analytics data for your App. The Analytics category comes with built-in support for Amazon Pinpoint and Amazon Kinesis.
  * Set up Analytics backend
    - Run the following command in your project’s root folder: `amplify add analytics`
  
  * Install Amplify Libraries
     ```
    dependencies {
    // Add these lines in `dependencies`
    implementation 'com.amplifyframework:aws-analytics-pinpoint:1.17.1'
    implementation 'com.amplifyframework:aws-auth-cognito:1.17.1'
    }

  * Initialize Amplify Analytics - initialize the Amplify Auth and Analytics categories you call Amplify.addPlugin() method for each category. To complete initialization call Amplify.configure().
    - Add the following code to onCreate():
    ```
    Amplify.addPlugin(new AWSCognitoAuthPlugin());
    Amplify.addPlugin(new AWSPinpointAnalyticsPlugin(this));

  * Record Events:
    ```
    AnalyticsEvent event = AnalyticsEvent.builder()
    .name("PasswordReset")
    .addProperty("Channel", "SMS")
    .addProperty("Successful", true)
    .addProperty("ProcessDuration", 792)
    .addProperty("UserAge", 120.3)
    .build();
    Amplify.Analytics.recordEvent(event);

  * View Analytics console with the following command:
    `amplify console analytics`
