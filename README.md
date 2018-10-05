 to Mountain View, CA on November 7-8, 2018.
Create an Android project
This lesson shows you how to create a new Android project with Android Studio and describes some of the files in the project.

First, be sure you have installed the latest version of Android Studio. Download Android Studio here.

In the Welcome to Android Studio window, click Start a new Android Studio project. 
Or if you have a project opened, select File > New Project.

In the Create New Project window, enter the following values:
Application Name: "My First App"
Company Domain: "example.com"
You might want to change the project location. Also, if you want to write a Kotlin app, check the Include Kotlin support checkbox. Leave the other options as they are.

Click Next.
In the Target Android Devices screen, keep the default values and click Next.
In the Add an Activity to Mobile screen, select Empty Activity and click Next.
In the Configure Activity screen, keep the default values and click Finish.
After some processing, Android Studio opens the IDE.


Now take a moment to review the most important files.

First, be sure the Project window is open (select View > Tool Windows > Project) and the Android view is selected from the drop-down list at the top of that window. You can then see the following files:

app > java > com.example.myfirstapp > MainActivity
This is the main activity (the entry point for your app). When you build and run the app, the system launches an instance of this Activity and loads its layout.
app > res > layout > activity_main.xml
This XML file defines the layout for the activity's UI. It contains a TextView element with the text "Hello world!".
app > manifests > AndroidManifest.xml
The manifest file describes the fundamental characteristics of the app and defines each of its components.
Gradle Scripts > build.gradle
You'll see two files with this name: one for the project and one for the "app" module. Each module has its own build.gradle file, but this project currently has just one module. You'll mostly work with the module's build.gradle file to configure how the Gradle tools compile and build your app. For more information about this file, see Configure Your Build.
