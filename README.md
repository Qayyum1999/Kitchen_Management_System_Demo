# Kitchen App System 👩🏻‍🍳🛎️
<a href="https://github.com/Qayyum1999"><img alt="views" title="Github views" src="https://komarev.com/ghpvc/?username=Qayyum1999&style=flat-square" width="125"/></a>

A fullstack kitchen system app made in **Flutter** with **Firebase** to enable kitchen staff to review and track orders received from the Food Ordering App. The app allows staff to view incoming order status, order lists, order history, and statistical order reports.

Demo: https://kitchen-management-138cf.web.app/

## Features 🚀
1. Order progress tracking based on table.
2. Manage order status with drag and drop
3. View order list & bills.
4. Check payment status.
5. Track orders with daily, weekly, monthly graphs

## Built With 🛠
1. google_fonts (https://pub.dev/packages/google_fonts) - A package for using custom fonts from Google Fonts in Flutter apps.
2. provider (https://pub.dev/packages/provider) - A package for managing app state and dependencies in Flutter.
3. fluttertoast (https://pub.dev/packages/fluttertoast) - A package for showing toast messages in Flutter.
4. responsive_framework (https://pub.dev/packages/responsive_framework) - A package for building responsive Flutter apps.
5. http (https://pub.dev/packages/http) - A package for making HTTP requests in Flutter apps.
6. cloud_firestore (https://pub.dev/packages/cloud_firestore) - A package for accessing and managing data in Firestore, a NoSQL cloud database by Firebase.
7. firebase_core (https://pub.dev/packages/firebase_core) - A package for initializing and configuring Firebase services.
8. intl (https://pub.dev/packages/intl) - A package for internationalizing Flutter apps.
9. fl_chart (https://pub.dev/packages/fl_chart) - A package for creating beautiful and responsive charts in Flutter apps.

## Structure for app 🗼

    lib # Root Package

    ├── models                       #source of data
    |   ├── database            #all firebase functions (firestore,cloud storage)
    |
    ├── providers                    #state management
    |   
    ├── screens                      #ui screen for each pages 
    |   ├── dragdroporders
    |   ├── orderhistory
    |   ├── reportscreen
    |   ├── tablescreen
    |      
    └── main.dart                    #entry point

## Platform Supported 💻📱

- [x] Android
- [x] Web





