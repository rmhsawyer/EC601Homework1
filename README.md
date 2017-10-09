# EC601Homework2
trello:
https://trello.com/b/pOMxgOJu/homework2
# Part 1 FoodTracker

Start Developing iOS Apps (Swift) is the perfect starting point for learning to create apps that run on iPhone and iPad. View this set of incremental lessons as a guided introduction to building your first app—including the tools, major concepts, and best practices that will ease your path.

Each lesson contains a tutorial and the conceptual information you need to complete it. The lessons build on each other, walking you through a step-by-step process of creating a simple, real-world iOS app.

As you make your way through the lessons and build the app, you’ll learn about concepts in iOS app development, gain a deeper understanding of the Swift programming language, and familiarize yourself with the many valuable features of Xcode, Apple’s integrated development environment (IDE).

This app shows a list of meals, including a meal name, rating, and photo. A user can add, remove, or edit a meal. To add a new meal or edit an existing one, users navigate to a different screen where they can specify a name, rating, and photo for a particular meal.

## Author
Sawyer (Minghe) Ren 
sawyermh@bu.edu

## How to use?

Please download the whole the FoodTracker Directory and run FoodTracker.xcodeproj in your Xcode application. You can use your simulator to test this app.


# Part 2 Friendly Pix iOS

Friendly Pix iOS is a sample app demonstrating how to build an iOS app with the Firebase Platform.

Friendly Pix is a place where you can share photos, follow friends, comment on photos...


## Initial setup, build tools and dependencies

Friendly Pix iOS is built using Objective-C and [Firebase](https://firebase.google.com/docs/ios/setup). The Auth flow is built using [Firebase-UI](https://github.com/firebase/firebaseui-ios). Dependencies are managed using [CocoaPods](https://cocoapods.org/). Additionally server-side micro-services are built on [Cloud Functions for Firebase](https://firebase.google.com/docs/functions).

Simply install the pods and open the .xcworkspace file to see the project in Xcode.

```
$ pod install
$ open your-project.xcworkspace
```

## Create Firebase Project

1. Create a Firebase project using the [Firebase Console](https://firebase.google.com/console).
1. To add the FriendlyPix app to a Firebase project, use the bundleID `com.google.firebase.friendlypix`.
1. Download the generated `GoogleService-Info.plist` file, and copy it to the root directory of this app.

### Google Sign In Setup
- Go to the [Firebase Console](https://console.firebase.google.com) and navigate to your project:
  - Select the **Auth** panel and then click the **Sign In Method** tab.
  - Click **Google** and turn on the **Enable** switch, then click **Save**.
- Open your regular `Info.plist` and replace the value of the `REVERSED_CLIENT_ID` with the value of the this key from the GoogleService-Info.plist`.
- Run the app on your device or simulator.
    - Select **Sign In** and select Google to begin.

### Facebook Login Setup
- Go to the [Facebook Developers Site](https://developers.facebook.com) and follow all
  instructions to set up a new iOS app. When asked for a bundle ID, use
  `com.google.firebase.quickstart.AuthenticationExample`.
- Go to the [Firebase Console](https://console.firebase.google.com) and navigate to your project:
  - Select the **Auth** panel and then click the **Sign In Method** tab.
  - Click **Facebook** and turn on the **Enable** switch, then click **Save**.
  - Enter your Facebook **App Id** and **App Secret** and click **Save**.
- Open your regular `Info.plist` and replace the value of the `FacebookAppID` with the ID of the
  Facebook app you just created, e.g 124567. Save that file.
- In the *Info* tab of your target settings add a *URL Type* with a *URL Scheme* of 'fb' + the ID
  of your Facebook app, e.g. fb1234567.
- Run the app on your device or simulator.
    - Select **Sign In** and select Facebook to begin.

### Twitter Login Setup
- Go to the [Twitter Developers Site](https://apps.twitter.com/) and follow all
  instructions to set up a new iOS app.
- Go to the [Firebase Console](https://console.firebase.google.com) and navigate to your project:
  - Select the **Auth** panel and then click the **Sign In Method** tab.
  - Click **Twitter** and turn on the **Enable** switch, then click **Save**.
  - Enter your Twitter **API Key** and **App Secret** and click **Save**.
- Open your regular `Info.plist` and replace the value of the `consumerKey` and `consumerSecret` values with the keys from the Twitter app you just created.
- Run the app on your device or simulator.
    - Select **Sign In** and select Twitter to begin.
- Note: you can also integrate with Twitter via Fabric using `[Fabric with:@[ [Twitter class] ]];`


## Contributing

We'd love that you contribute to the project. Before doing so please read our [Contributor guide](../CONTRIBUTING.md).


## License

© Google, 2011. Licensed under an [Apache-2](../LICENSE) license.



Part3 Cloud Storage for Firebase Quickstart
=============================

The Cloud Storage for Firebase iOS quickstart demonstrates how to upload data to a Cloud Storage bucket, and retrieve a download URL.

Introduction
------------

- [Read more about Cloud Storage for Firebase](https://firebase.google.com/docs/storage)

Getting Started
---------------

- [Add Firebase to your iOS Project](https://firebase.google.com/docs/ios/setup). The package name you'll use is `com.google.firebase.quickstart.StorageExample`.
- Enable Anonymous auth in the **Auth > SIGN IN METHOD** tab.
![Alt text](https://github.com/firebase/quickstart-js/blob/master/storage/pics/enable.png?raw=true "Enable auth")
- Run the sample on your iOS device or simulator.


Support
-------

- [Firebase Support](https://firebase.google.com/support/)

License
-------

Copyright 2016 Google, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

# Part4 Firebase Codelab: FriendlyChat

This is the source code for the Firebase FriendlyChat codelab. It includes start and end versions of the
code for Web and Cloud Functions. To get started open the codelab instructions:

 - [Firebase Web Codelab](https://codelabs.developers.google.com/codelabs/firebase-web/).
 - [Firebase SDK for Cloud Functions Codelab](https://codelabs.developers.google.com/codelabs/firebase-cloud-functions/).


## How to chat with me?
Click the link here:
https://friendlychat-ae995.firebaseapp.com/



## License
See [LICENSE](LICENSE)
