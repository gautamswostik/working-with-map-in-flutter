# angleswing_skill_assesment

A new Flutter project.

## Getting Started

# Project Setup

I have tried to follow clean architectire for the project for better redability and better management

Firstly I installed the packages and plugins which I'm going to use most in this project, the packaces are added throughout the development phase according to the needs of application.

The main packages and plugins installed are follows
1.Flutter_map
I dicided to use this package because it is based on MapBox and uses MapBox api for Maps and stuffs related with map. There are many packages like google_maps which provide many more feature. But it was specified if I have used MapBox the better in requirement of Job vacancy so I dicided to go with MapBox. 2. Bloc - For state management 3. Dio - For api calls 4. ohters for code generations and some other suffs

The project is divided into 4 parts 1. App Setup 2. Application 3. Infrastructure 4. Presentation

# App Setup

    The App setup consists of Api services, Local storage services , bloc observer for observing bloc states and event and app.dart which is beginning of our application.

# Infrastructure

    The Infrastructure consits of Repository classes for api, local storage , Models of api etc.

# Application

    The Application is used to call repository which consists of bloc, api failure entites and api endpoints.

# Presentation

    The presentaion consists of User Interface section of the application. All the screens and widgets are located in presentation.
