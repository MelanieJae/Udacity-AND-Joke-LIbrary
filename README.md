# Joke library (Gradle for Android and Java Project)

In this project, you will create an app with multiple flavors that uses
multiple libraries and Google Cloud Endpoints. The finished app will consist
of four modules. A Java library that provides jokes, a Google Cloud Endpoints
(GCE) project that serves those jokes, an Android Library containing an
activity for displaying jokes, and an Android app that fetches jokes from the
GCE module and passes them to the Android Library for display.

## Build Notes
This project utilizes the Gradle build system.

## Development Notes

* contains free and paid flavors; the free flavor contains test ads supplied by Google AdMob 
* contains a Java library for supplying a joke to the UI from an expandable joke library (currently in ArrayList format)
* contains an Android library handling display of jokes retrieved from the Java library
* contains a backend via Google Cloud Endpoints and the AppEngine Gradle plugin Use the Gradle App Engine plugin to deploy a backend
* contains an instrument test suite that runs against the local App Engine development server

## Sources:
https://github.com/rominirani/HelloCloudEndpoints-tutorial and other projects for consuming API endpoint in an Android app
