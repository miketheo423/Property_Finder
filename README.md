# Property_Finder - React Native Tutorial

Getting a native app on your phone is a lot easier to do than you may think!
React Native transpiles your javascript, making it possible to create a native app without having to know the code for iOS and Android.

You can get started on creating an app with [this](https://www.raywenderlich.com/165140/react-native-tutorial-building-ios-android-apps-javascript) tutorial.

The official documentation for getting started with react native can be found [here](https://facebook.github.io/react-native/docs/getting-started.html). It is definitely a good idea to have both of these tutorials side by side.

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

However for the sake of finding and following a solid tutorial, I built this app using the react native cli.

## Step for Getting Started with react-native-cli
1. brew install node
2. brew install watchman
3. npm install -g react-native-cli
4. react-native init (App-Name)
5. cd into Project
6. react-native run-ios OR open the .xcodeproj file in the ios folder with Xcode, then run build.

That's it! Technically now you have a running native app being simulated with Xcode.
If you want to start modifying the app, go into index.js and start editing some lines of code. Then, save your changes and refresh the simulator and voila!

From here you can start building out components and really exploring what you can do with react-native. Once you're ready to deploy the app to your phone, follow the steps below...

## Running your app on iOS devices 
1. Plug in your device via USB
- Connect your iOS device to your Mac using a USB to Lightning cable. Navigate to the ios folder in your project, then open the .xcodeproj file within it using Xcode.
- If this is your first time running an app on your iOS device, you may need to register your device for development. Open the Product menu from Xcode's menubar, then go to Destination. Look for and select your device from the list. Xcode will then register your device for development.

2. Configure code signing #
- Register for an Apple developer account if you don't have one yet.
- Select your project in the Xcode Project Navigator, then select your main target (it should share the same name as your project). Look for the "General" tab. Go to "Signing" and make sure your Apple developer account or team is selected under the Team dropdown.

3. Build and Run your app 
- If everything is set up correctly, your device will be listed as the build target in the Xcode toolbar, and it will also appear in the Devices pane (⇧⌘2). You can now press the Build and run button (⌘R) or select Run from the Product menu. Your app will launch on your device shortly.


