[![npm](https://img.shields.io/npm/v/cordova-plugin-gameanalytics.svg)](https://www.npmjs.com/package/cordova-plugin-gameanalytics)
[![npm](https://img.shields.io/npm/dt/cordova-plugin-gameanalytics.svg?label=npm%20downloads)](https://www.npmjs.com/package/cordova-plugin-gameanalytics)
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

# cordova-plugin-gameanalytics
Official Cordova plugin for the GameAnalytics SDK for Android and iOS.

#### Native Libraries:
Android | iOS
---------- | -----------
[GA-SDK-ANDROID](https://github.com/GameAnalytics/GA-SDK-ANDROID) |  [GA-SDK-IOS](https://cocoapods.org/pods/GA-SDK-IOS)

## Installation
From your command prompt/terminal go to your app's root folder and execute:

`cordova plugin add cordova-plugin-gameanalytics`

## Usage
```

onDeviceReady: function() {
    GameAnalytics.initialize({
        gameKey: "[INSERT_GAME_KEY]",
        secretKey: "[INSERT_SECRET_KEY]"
    });

    GameAnalytics.addDesignEvent({
        eventId: "design:event"
    });
}

```

For more documentation click [here](https://gameanalytics.com/docs/cordova-sdk).

Changelog
---------
<!--(CHANGELOG_TOP)-->
**1.0.3**
* readme updated

**1.0.2**
* plugin description fixes

**1.0.1**
* version fix

**1.0.0**
* initial version
