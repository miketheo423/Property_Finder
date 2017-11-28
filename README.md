# Property_Finder - React Native Tutorial

Getting a native app on your phone is a lot easier to do than you may think!

You can get started on creating an app with [this](https://www.raywenderlich.com/165140/react-native-tutorial-building-ios-android-apps-javascript) tutorial.

## Two ways to start building:
1. Quick Start:
- npm install -g create-react-native-app - Create React Native App is the easiest way to start building a new React Native application. It allows you to start a project without installing or configuring any tools to build native code - no Xcode or Android Studio installation required. 
- The Caveat: Because you don't build any native code when using Create React Native App to create a project, it's not possible to include custom native modules beyond the React Native APIs and components that are available in the Expo client app.
- If you know that you'll eventually need to include your own native code, Create React Native App is still a good way to get started. In that case you'll just need to "eject" eventually to create your own native builds. If you do eject, the "Building Projects with Native Code" instructions will be required to continue working on your project.
- Install the Expo client app on your iOS or Android phone and connect to the same wireless network as your computer. Using the Expo app, scan the QR code from your terminal to open your project.

2. Building projects with native code:
- You will need Node, Watchman, the React Native command line interface, and Xcode.
- While you can use any editor of your choice to develop your app, you will need to install Xcode in order to set up the necessary tooling to build your React Native app for iOS.

I tested out the quick start method, which was really cool. Rather than using a simulator through Xcode, you actually use your phone as a dev environment.
Whenever you save your changes in your text editor, your phone refreshes and the changes can be seen!

However for the sake of finding and following a solid tutorial, I built this app using native code and the react native cli.
