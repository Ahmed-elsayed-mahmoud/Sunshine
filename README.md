
# Sunshine

## Overview

An android mobile application. The purpose of this project was to built an app, optimized for tablets, to help users discover the daily weather. 
It displays a list of forecasts for the weather of each day of the weak starting from today's weather. 
This app utilizes core Android user interface components and fetches movie information using openweathermap.org web API.

# App Fundamentals

* RecyclerView, onClick implementation, LayoutManager
* Threading and ASyncTask, JSON parsing
* Intents, PlacePickerIntent (Google PlacePicker API)
* Broadcast Intents and Broadcast Receivers
* Content Provider, SQLite databases and JUnit tests
* Supporting localization and variable screen sizes (Ukrainian language, tablet design)
* Accessibility Features, Custom views (EditText)
* Background services, SyncAdapters
* Notification

## Prerequisites

### [API Keys](http://openweathermap.org)
You need OpenWeather and Google Maps API keys: 
* OpenWeatherMap Key: <http://openweathermap.org/>
* Google Maps Key (PlacePicker): <https://developers.google.com/places/android-api/placepicker>

OpenWeather key you should add to the gradle.properties file:</br>
MyOpenWeatherMapApiKey = "**YOUR API KEY**"

Google Maps API key should be added to the api_key.xml in values folder as a string with name: youtube_api_key


### [Android Studio](https://developer.android.com/studio/index.html)

Android Studio provides the fastest tools for building apps on every type of Android device.

World-class code editing, debugging, performance tooling, a flexible build system, and an instant build/deploy system all allow you to focus on building unique and high quality apps.


## Running Tests
<img width="80%" src="http://ahmed-elsayed.890m.com/assets/images/works/sunshine.png" />

# How to Run

To make server calls, we use the API from [openweathermap.org](https://www.openweathermap.org/) which requires an API Key. To run this project, you need to add the API Key mentioned in build.gradle.
* To request an API key from [openweathermap.org](https://www.openweathermap.org/), you need to create an account on the site.
* In the request for a key, you have to state that our usage will be for educational/non-commercial use. You also need to provide some personal information to complete the request. Once you submit the request, you should receive your key via email shortly after.

## Libraries Used 

* [Retrofit](http://square.github.io/retrofit/) - A type-safe HTTP client for Android and Java
* [Butterknife](http://jakewharton.github.io/butterknife/) - Field and method binding for Android views


## License
 
CopyRight 2016 Ahmed Elsayed Mahmoud

