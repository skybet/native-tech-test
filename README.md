# SkyBet iOS/Android Tech Test

## Scenario

You are asked to build a new feature for a betting app, this is to allow the user to login using a Pin / finger print / face scanning depending on device.

On initial load the App should ask for the user to enter a PIN which needs to be stored securly on the device.

On subsequent launches the App should ask for either a PIN / finger print / face Id depending on the users device preference.

The App should load a WebView from the included content - index.html

When the user has been logged in securely then you will need to call a javascript method on the web content called loggedIn(), this should then display that the user is logged in.

The App should also listen for events coming from the Web View for the user logging out called loggedOut().

## What we require

You will build an app that works across a range of device sizes in both landscape and portrait orientations.

On load, the user is expected to enter a 4 digit PIN or use TouchID/Face ID to access the app if it is available.

You should build a robust mechanism to allow the App to talk to the Web and Vice-Versa

Your App should not crash.

You should support the latest OS for devices and the last preceeding one. e.g iOS 11 & iOS 10.

##Expectations

We value well structured, modular, reusable code with unit tests that is easily maintainable.

Spend up to 6 hours over no more than 5 days on this. We expect to see regular commits to Git with meaningful commit messages.

You will write this in Objective-C for iOS & Java for Android

You should not use a code generation tool/frameworks

For Android apps we expect you to use the latest version of Android Studio, and for iOS the latest version of XCode. No Beta versions.

## What to submit

* A bundled/archived repository showing your commit history, for example:

```git bundle create <yourname>.bundle --all --branches```

* A covering note explaining the technology choices you have made.


