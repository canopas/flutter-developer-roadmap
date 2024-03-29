
<h1 align="center">Flutter Developer Roadmap 2023</h1>

![alt text](https://github.com/cp-sneha-s/flutter-roadmap/blob/main/Flutter-developer-roadmap-header-image.jpeg)

Flutter Developer Roadmap 2023 is a learning path to understand flutter development.

## What is Flutter?

Flutter is an SDK(Software Development Kit) developed by google that allows developer to build native cross-platform apps with just one programming langauage-Dart. From single codebase, it creates native app for ios, Android and web, that can be published to the stores later.

# Table of Contents:
- [Sprint 1](https://github.com/cp-sneha-s/flutter-roadmap#sprint-1)
- [Sprint 2](https://github.com/cp-sneha-s/flutter-roadmap#sprint-2)
- [Sprint 3](https://github.com/cp-sneha-s/flutter-roadmap#sprint-3)
- [Sprint 4](https://github.com/cp-sneha-s/flutter-roadmap#sprint-4)
- [Sprint 5](https://github.com/cp-sneha-s/flutter-roadmap#sprint-5)
- [Sprint 6](https://github.com/cp-sneha-s/flutter-roadmap#sprint-6)

#### Let's start with basic learning.

## Sprint 1:

### Flutter basics:
* introduction to [Flutter](https://www.javtpoint.com/flutter)
* [Why flutter?](https://medium.com/flutter-community/reasons-why-flutter-is-setting-the-trend-in-mobile-app-development-4aa707532fb)
* [Set up](https://docs.flutter.dev/get-started/install)

### Dart basics:
* Introduction to [Dart](https://hackernoon.com/why-flutter-uses-dart-dd635a054ebf)
* [Dart](https://dart.dev/guides/language/language-tour) programming langauage

### Code style:
* [Best practices and tips](https://medium.com/flutter-community/flutter-best-practices-and-tips-7c2782c9ebb5)
* [Effective Dart](https://dart.dev/guides/language/effective-dart)
* [Flutter code formatting](https://docs.flutter.dev/development/tools/formatting)

#### Practicle 1.1
* Do all [Practicles](https://github.com/cp-sneha-s/flutter-roadmap/blob/main/Practical-1.1) using [Dartpad](https://www.dartpad.dev/?).



#### References
* Introduction to version control: [What Is Version Control?](https://tutorials.codebar.io/version-control/introduction/tutorial.html)
* How to use git
    -  [Version control with git](https://www.udacity.com/course/version-control-with-git--ud123)
    -  [Git: The Beginner's Guide to Understanding Core Version Control Concepts](https://www.udemy.com/course/ios-13-app-development-bootcamp/learn/lecture/10929402#overview)
    -  [When to commit in version control](https://softwareengineering.stackexchange.com/questions/74764/how-often-should-i-do-you-make-commits)
    
 #### Practicle 1.2
* Create repository of practicle 1.1 on Gitlab
 
 ### Flutter Tools:
* [Hot Reload](https://docs.flutter.dev/development/tools/hot-reload)
* [Punspec file](https://docs.flutter.dev/development/tools/pubspec)


## Sprint 2:

* Introduction to [Declarative UI](https://docs.flutter.dev/get-started/flutter-for/declarative)
* Introduction to [Widgets](https://docs.flutter.dev/development/ui/widgets-intro)
* [Layouts in flutter](https://docs.flutter.dev/development/ui/layout)
* [Building Layout](https://docs.flutter.dev/development/ui/layout/tutorial)

### Supporting different devices
* [Adaptive and Resposive](https://docs.flutter.dev/development/ui/layout/adaptive-responsive) apps

### DelightFul User experience
* Intorduction to [Material components](https://docs.flutter.dev/development/ui/widgets/material)
* How to Build Beautiful UIs with Flutter Widgets 
    -  Udemy Course 1 - Section 6


### Practical 2.1
* Create given [Responsive UI](https://user-images.githubusercontent.com/92501869/202130578-6c42048a-ce47-4833-bdc2-9e700cc6a489.png) for mobile and       desktop app. 
    - You can use alternative images.
    - Note: It should not be break in portrait mode for mobile apps
 
   
### Navigation:
* [Navigation](https://medium.com/easyread/3-options-for-creating-responsive-layouts-in-flutter-app-live-demo-68b0c0e955ab) in Flutter
* [Navigation and Routing](https://docs.flutter.dev/development/ui/navigation)


### Practical 2.2
* Implement an app with a bottom bar that has 4 screens (home, setting, like, search).
   -  Implement a route between screens from Navigation 1.0.
   
   
### Json serialization:
* [Json and serialization](https://docs.flutter.dev/development/data-and-backend/json)
   - [Parsing Json](https://medium.com/@abhishekdoshi26/parsing-json-in-flutter-7519293f5168) in flutter
* [Auto generate](https://medium.flutterdevs.com/automatic-generate-json-serializable-in-flutter-4c9d2d23ed88) json serializable in flutter



## Sprint 3:

### Networking:
* [Networking in flutter](https://docs.flutter.dev/development/data-and-backend/networking)
* [Retrofit](https://medium.com/mindful-engineering/retrofit-the-easiest-way-to-call-rest-apis-is-flutter-fe55d1e7c5c2)
* [Dio](https://pub.dev/packages/dio)-  powerful HTTP client of dart
* [Chopper](https://pub.dev/packages/chopper)- HTTP client generator for Dart and Flutter using source_gen and inspired by Retrofit.
* [http](https://pub.dev/packages/http) for networking.

### Practical 3.1
* Implement Food Application with following functionality 
* Fetch food feeds from API 
* User should be navigate to its detail page by clicking reciepe
* Add long click delete functionality on food click to delete food.
* Implement [pull to refresh](https://pub.dev/packages/pull_to_refresh) functionality to refresh cached feeds.

    API - GET request - 'https://spoonacular-recipe-food-nutrition-v1.p.rapidapi.com/food/ingredient
    
    headers: {
    'X-RapidAPI-Key': '6991e41207mshaaf1e8dd61f03fdp17fbe9jsn3c96953146c7',
    'X-RapidAPI-Host': 'spoonacular-recipe-food-nutrition-v1.p.rapidapi.com'
  }
  * Note:
    - Use http package for networking
  
 ### Reference:
 * [Networking like a pro](https://medium.com/swlh/how-to-do-networking-like-a-pro-in-flutter-7e2612103cb5)
 * Flutter networking [tutorial](https://www.kodeco.com/5896601-flutter-networking-tutorial-getting-started)
 
 ### Work in background
 * [Concurrency](https://dart.dev/guides/language/concurrency) in Dart
 * [Asynchronous programming](https://dart.dev/codelabs/async-await)
 
 #### Reference:
 * [Asynchronous](https://medium.flutterdevs.com/concurrency-in-dart-b9171278af31) in Dart
 * [WorkManager](https://pub.dev/packages/workmanager)
 * [Thread and Isolate](https://medium.com/flutter-community/thread-and-isolate-with-flutter-30b9631137f3)
 
 ### Navigation 2.0
 * Introduction to [Navigator 2.0](https://blog.codemagic.io/flutter-navigator2/)
 
 ### Practicle 3.2
 * Implement Navigation 2.0 with [go_router](https://pub.dev/packages/go_router).
 * Implement navigation 2.0 in Practicle 3.1
 
 ### References:
* [A beginner’s guide to go_router in Flutter](https://blog.codemagic.io/flutter-go-router-guide/)
* [Get started with Go Router](https://pub.dev/documentation/go_router/latest/topics/Get%20started-topic.html)
 
 ## Sprint 4:
 
 ### App Architecture:
 * [Archtectural overview](https://docs.flutter.dev/resources/architectural-overview)
 * [Flutter MVVM Architecture](https://medium.com/flutterworld/flutter-mvvm-architecture-f8bed2521958)
 * [MVVM](https://medium.flutterdevs.com/design-patterns-in-flutter-part-3-mvvm-a310de4eb83) design pattern
 
 ### State management:
 * [Interoduction](https://docs.flutter.dev/development/data-and-backend/state-mgmt/intro) to state management
 * [Conceptual types of state](https://docs.flutter.dev/development/data-and-backend/state-mgmt/ephemeral-vs-app)
 * State management [approaches](https://docs.flutter.dev/development/data-and-backend/state-mgmt/options)
 * Udemy Course 1: Section 16

### Practical 4.1
* Implement state management approach in Practical 3.1
 - Note
    - Use flutter bloc for state management
    - Use provider for state management
 
### Reference:
* [Provider](https://medium.com/codechai/provider-state-management-in-flutter-d453e73537c5) state management in flutter
* [BLoC](https://blog.logrocket.com/state-management-flutter-bloc-pattern/) state management in flutter


### Local storage:
* [Store key-vaue pair](https://docs.flutter.dev/cookbook/persistence/key-value)
* [Read and write files](https://docs.flutter.dev/cookbook/persistence/reading-writing-files)
* [Sqlite database](https://docs.flutter.dev/cookbook/persistence/sqlite)
* [hive](https://pub.dev/packages/hive)

### Practical 4.2
* create a task management app with three screens: a login screen, a task list screen, and a task detail screen. The app should allow users to login with   their credentials, view a list of tasks, and view details of each task.
* Home screen should have list of task with add new task fab button
* Users can mark tasks as completed or incompleted.
* On the click of task it should be redirect to task status screen where it can be edit.
* On the cell swipe it shows delete option and on it's click that particular task should delete.
* The app should display a summary of the number of tasks that are completed and uncompleted.
   - Note
     -  Store data in SQLite 
     -  Shows the data from SQLite on home screen
     -  Implement CRUD operation with SQLite 
   
### Reference:
* [Database concepts](https://www.tutorialspoint.com/flutter/flutter_database_concepts.htm) in flutter
* [SQL Databsae storage using sqlite](https://medium.flutterdevs.com/sql-database-storage-using-sqlite-in-flutter-6e2fdcc8cfb7)

### Remote Storage:
* [Firebase](https://docs.flutter.dev/development/data-and-backend/firebase)

### Practical 4.3
* Use firebase as backend data service in Practical 4.1


## Sprint 5


### Depenedecy Injection
* [Introduction](https://www.geekyants.com/blog/understanding-dependency-injection-in-flutter-using-provider-143/) to dependency injection
* [DI in flutter](https://medium.com/flutter-community/flutters-dependency-injection-c4f053e4408)
* Package:
   -  [injectable](https://pub.dev/packages/injectable)
   -  [getIt](https://pub.dev/packages/get_it)
   
### Practical 5.1
* Implement DI in Practical 4.2
* Implement GetX in Practical 4.2


### Reactive programming
* [RxDart](https://pub.dev/packages/rxdart)
* Introduction to [RxDart](https://medium.com/flutter-community/why-use-rxdart-and-how-we-can-use-with-bloc-pattern-in-flutter-a64ca2c7c52d)

### Practical 5.2
Create a weather app that allows users to check the current weather conditions and forecast for any location. 
* The app should have three screens: 
    *  Home screen that displays the current weather conditions for the user's location,  
    *  Search screen that allows users to search for weather conditions by city name
    *  Details screen that displays the selected location's weather forecast for the next few days.
    * Implement Error screen in case of Exception.
    
    
      -  Refer: https://openweathermap.org./
      -  Generate your API key here: https://home.openweathermap.org/users/sign_up
      -  API-Get request for weather data: https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key}
      -  API-GET Request for location data: https://api.openweathermap.org/geo/1.0/direct?q={city}&limit=1&appid={API Key}

  - Note
    - Use rxDart

### Testing:
* [Intruduction](https://docs.flutter.dev/testing) to testing flutter apps
* [Unit testing](https://docs.flutter.dev/cookbook/testing/unit/introduction)
* [Widget testing](https://docs.flutter.dev/cookbook/testing/widget/introduction)
* [Integration testing](https://docs.flutter.dev/cookbook/testing/integration/introduction)
* Mock dependencies using [Mockito](https://docs.flutter.dev/cookbook/testing/unit/mocking)
* Introduction to [TDD](https://medium.com/upday-devs/flutter-test-driven-development-e57f2defff43)

### Package
* [Test](https://pub.dev/packages/test)

### Practical 5.3:
* Add Unit,widget and integration test in practical 5.1


## Sprint 6:


### Localization
* [Internationalizing Flutter apps](https://docs.flutter.dev/development/accessibility-and-localization/internationalization)

### Platform integration
* [Supported Platforms](https://docs.flutter.dev/development/tools/sdk/release-notes/supported-platforms)
* [Desktop support for flutter](https://docs.flutter.dev/development/platform-integration/desktop)
* [Web application with flutter](https://docs.flutter.dev/get-started/web)

### Practical 6.1:
* Add localization in Practicle 5.1
* Add desktop and web support for the same. 
 
### Advanc UI
* [Slivers](https://docs.flutter.dev/development/ui/advanced/slivers)
* [Animation](https://docs.flutter.dev/development/ui/animations)


### Final Practice:
1 Implement a shopping application 
      
  Screen one - Home screen 
   -  On main screen show list of products - [API](https://fakestoreapi.com/products)
      
   -  Open product detail on it’s click - [API](https://fakestoreapi.com/products/1)
      
   -  Add option to search products by categories - [API](https://fakestoreapi.com/products/categories)
      
   -  Add option to check out all product in cart
 
  Screen two - Detail screen
   -  Show full detail with images and description 
   -  Add option to add/remove the product from the cart ( Add/delete an item in local database)  

  Screen three - Show products from cart
     
   -   Fetch and show all cart item from local database
   -   Add option checkout and show total price of products
   -   Add option to remove from cart
                  

  Screen four - Login 
   -   User must have to login before adding any item into cart - API
   -   Add option to logout 
      


  - Add unit test for all viewmodel and helper classes

 2  Make a calculator application. Save calculation history in the database. Users can view history and clear history.


### Extra:

### Dev Tools:
* [Flutter Inspector](https://docs.flutter.dev/development/tools/devtools/inspector)
* [Memory allocation](https://docs.flutter.dev/development/tools/devtools/memory)
* Flutter performance [best practices](https://docs.flutter.dev/perf/best-practices)












