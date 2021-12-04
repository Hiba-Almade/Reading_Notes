### Intent Filters:

#### Allowing Other Apps to Start Your Activity:
* To allow other apps to start your activity, you need to add an <intent-filter> element in your **manifest file** for the corresponding <activity> element.
* When your app is installed on a device, the system identifies your intent filters and adds the information to an internal catalog of intents supported by all installed apps.
* Add an Intent Filter - to properly define which intents your activity can handle, each intent filter you add should be as specific as possible in terms of the type of action and data the activity accepts.

* Handle the Intent in Your Activity
    - In order to decide what action to take in your activity, you can read the Intent that was used to start it.
    - As your activity starts, call getIntent() to retrieve the Intent that started the activity.
* Return a Result
    - setResult() - to specify the result code and result Intent
    - finish() - to close (and destroy) your activity.
    - Must always specify a result code with RESULT_OK or RESULT_CANCELED. 
   