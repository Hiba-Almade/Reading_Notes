## Android Tasks and the Back Stack

#### Task:
a collection of activities that users interact with when performing a certain job.

* Activities are arranged in a the back stack in the order in which each activity is opened.
* When apps are running simultaneously in a multi-windowed environment the system manages tasks separately for each window, and each window may have multiple tasks.
* The device Home screen is the starting place for most tasks. When the user touches an icon in the app launcher, that app's task comes to the foreground. If no task exists for the app, then a new task is created and the "main" activity for that app opens as the root activity in the stack.

`>>` Two ways to define different launch modes: Using manifest file or using intent flags.

* Manifest file : when declaring an activity in your manifest file, you can specify how the activity should associate with a task using the element's `launchMode` attribute.
* Intent flags: when starting an activity, you can modify the default association of an activity to its task by including flags in the intent that you deliver to `startActivity()`.

#### Clearing the back stack :

If the user leaves a task for a long time, the system clears the task of all activities except the **root activity**.

Activity attributes used to modify behavior: `alwaysRetainTaskState`, `clearTaskOnLaunch`, and `finishOnTaskLaunch`.


`>` Use the SharedPreferences APIs when you have a relatively small collection of key-values that you'd like to save.

#### SharedPreferences object :

points to a file containing key-value pairs and provides simple methods to read and write them. Each SharedPreferences file is managed by the framework and can be private or shared.

Can create a new shared preference file or access an existing one by calling one of these methods:

* getSharedPreferences() — use this if you need multiple shared preference files identified by name.
* getPreferences() — use this from an Activity if you need to use only one shared preference file for the activity.
