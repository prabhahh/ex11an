Experiment 11: Develop an Application to Display Google Maps

1. Aim

To develop an Android application that displays Google Maps using Google Maps API and provides a map view within the application.

2. Introduction

Google Maps is a mapping service that helps users find locations, view geographical areas, and navigate from one place to another.

In Android development, Google Maps can be integrated into an application using the Google Maps SDK.

This experiment demonstrates how to integrate Google Maps into an Android application and display a map on the mobile screen.

3. Objectives

- To understand Google Maps integration in Android.
- To learn how to use Google Maps SDK.
- To display Google Maps inside an Android application.
- To understand the use of API keys.
- To explore map features such as zooming, scrolling, and location viewing.

4. Software Requirements

- Android Studio
- Android SDK
- Kotlin or Java
- Google Maps SDK
- Internet connection
- Android Emulator or Android mobile device

5. Concepts Used

A. Google Maps SDK

Google Maps SDK allows developers to add Google Maps functionality to Android applications.

B. API Key

An API key is a unique code used to access Google Maps services. It connects the Android application with Google Cloud services.

C. SupportMapFragment

It is used to display Google Maps inside an Android application.

D. OnMapReadyCallback

It is an interface that is called when the Google Map is ready to use.

E. Map Types

Google Maps provides different types of map views:

- Normal Map
- Satellite Map
- Terrain Map
- Hybrid Map

6. Procedure

1. Open Android Studio.
2. Create a new Android project.
3. Select Kotlin or Java as the programming language.
4. Add the Google Maps SDK dependency.
5. Generate a Google Maps API key from Google Cloud Console.
6. Enable the Maps SDK for Android.
7. Add the API key in the AndroidManifest.xml file.
8. Create a layout containing a SupportMapFragment.
9. Implement OnMapReadyCallback in the MainActivity.
10. Run the application on an emulator or Android device.
11. The Google Map will be displayed on the screen.

7. Working Principle

1. The application starts when the user opens it.
2. The application requests access to Google Maps using the API key.
3. Google Maps SDK loads the map.
4. The map is displayed on the mobile screen.
5. The user can zoom in, zoom out, and move around the map.
6. The application provides a basic map viewing experience.

8. Application Structure

GoogleMapsApp/
│
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       │   └── MainActivity.kt
│   │       │
│   │       ├── res/
│   │       │   └── layout/
│   │       │       └── activity_main.xml
│   │       │
│   │       └── AndroidManifest.xml
│   │
│   └── build.gradle.kts
│
└── README.md

9. Features

- Displays Google Maps inside the application.
- Allows users to zoom in and zoom out.
- Supports map movement and scrolling.
- Provides different map viewing options.
- Helps users explore geographical locations.

10. Applications

- Location-based applications.
- Travel and tourism applications.
- Food delivery applications.
- Cab booking applications.
- Navigation applications.
- Location tracking applications.

11. Advantages

- Easy to understand and use.
- Provides geographical information.
- Helps users identify different locations.
- Supports interactive map features.
- Can be integrated into various Android applications.

12. Result

Thus, an Android application to display Google Maps was successfully developed and executed. The application displays the map on the mobile screen and allows users to explore different locations using basic map controls.

13. Conclusion

Through this experiment, we learned how to integrate Google Maps into an Android application using Google Maps SDK. We also understood the importance of API keys, SupportMapFragment, and OnMapReadyCallback. This experiment helped us understand the basics of developing location-based Android applications.

---

Experiment Number: 11
Experiment Name: Develop an Application to Display Google Maps
Platform: Android Studio
Language: Kotlin / Java
