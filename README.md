# Joke library (Gradle for Android and Java Project)

In this project, you will create an app with multiple flavors that uses
multiple libraries and Google Cloud Endpoints. The finished app will consist
of four modules. A Java library that provides jokes, a Google Cloud Endpoints
(GCE) project that serves those jokes, an Android Library containing an
activity for displaying jokes, and an Android app that fetches jokes from the
GCE module and passes them to the Android Library for display.

## Build Notes

This project is built using the Gradle build system and a Google Cloud Endpoints/AppEngine backend for its API.

## Development Notes

* contains free and paid flavors; the free version contains ads supplied via Google Play/AdMob
* contains a Java library having an expandable list of jokes
* contains an Android library that handles display of the joke once retrieved from the backend/API
* contains a backend constructed via Google Cloud Endpoints and the AppEngine plugin
* contains instrument tests for both the free and paid versions that runs against the local App Engine development server

## Sources
Project base
https://github.com/udacity/ud867/tree/master/FinalProject

