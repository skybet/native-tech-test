# SkyBet iOS/Android Tech Test

## Scenario

You are asked to build a new feature for a betting app, to allow the user to track the odds and the changes to potential payouts during the life of an in-play bet.

In future the data will come from a RESTful API but for now you will need to build a stub for this; an example JSON response is given below.

## What we require

You will build an app that works across a range of device sizes in both landscape and portrait orientations.

On load, the user is expected to enter a 4 digit PIN or use TouchID to access the app if it is available.

It will load the user’s bets from the API, showing them ordered by expiry.

If the odds change the user expects to be informed, even if the app is closed. 

##Expectations

We value well structured, modular, reusable code with unit tests that is easily maintainable.

Spend up to 6 hours over no more than 5 days on this. We expect to see regular commits to Git with meaningful commit messages.

You should not use a code generation tool/frameworks

For Android apps we expect you to use the latest version of Android Studio, and for iOS the latest version of XCode.

## What to submit

* A bundled/archived repository showing your commit history, for example:

```git bundle create <yourname>.bundle --all --branches```

* A covering note explaining the technology choices you have made.

##Example API response:

```json
{
  "timestamp": "10/08/2016 10:40:23",
    "bets": [
    {
      "betId"  : 0,
      “stake"  : 10,
      “odds"   : "1/2",
      “market" : "Arsenal to Win 2-1"
    },
    {
      "betId"  : 1,
      “stake"  : 35,
      “odds"   : "11/2",
      “market" : "Arsenal to Win 3-1"
    },
    {
      "betId"  : 2,
      “stake"  : 0.5,
      “odds"   : "7/4",
      “market" : "Draw 1-1"
    },
    {
      "betId"  : 3,
      “stake"  : 100,
      “odds"   : "8/1",
      “market" : "Draw 3-3"
    },
    {
      "betId"  : 4,
      “stake"  : 2.5,
      “odds"   : "1/2",
      “market" : "Manchester Win 1-0"
    }
  ]
}
```
