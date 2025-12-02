# React Native Navigation Lab Activity

A React Native application demonstrating stack navigation using React Navigation and Expo.

## Student Information

- **Name:** Jio Patrick Rufer Quion  
- **Student ID:** 202305666
- **Course:** Mobile Application Development
- **Date:** December 02, 2025

## Features

- Stack navigation between screens
- Home and Details screens
- Navigation buttons and gestures
- Android emulator support

## Technologies Used

- React Native 0.76.3
- Expo ~52.0.0
- React Navigation 6.x
- JavaScript/ES6

## Installation

```
bash
npm install
```

## Running the App

```
bash
```

# Start development server

```
npm start
```

# Run on Android

```
npm run android
```

# Run on iOS

```
npm run ios
```

# Run on web

```
npm run web
```

## Project Structure

```
├── App.js # Main app with navigation
├── screens/
│ ├── HomeScreen.js # Home screen
│ └── DetailsScreen.js # Details screen
├── package.json # Dependencies
├── app.json # Expo configuration
└── README.md # Documentation
```

## Screenshots

![Alt Text](hs.png)
![Alt Text](ds.png)

## Challenges Faced

Android Studio API installed was API 34. I resolved this by downloading the API 35.
Expo was constantly bugging, I double checked everything. I already installed all the components needed (npm install and such) and even tried redoing the whole process. AppEntry.js was unable to resolve the "../../App". 
I resolved this by asking a classmate to send me their working package-lock.json file and after running the program, it finally installed the right SDK version.

## Learning Outcomes

I learned the basics of creating the interface of a mobile app. 
Intalling the dependencies needed for the android studio and node package
I also learned some few debuggings 

## References

- [React Navigation Documentation](https://reactnavigation.org/)
- [Expo Documentation](https://docs.expo.dev/)
- [React Native Documentation](https://reactnative.dev/)
