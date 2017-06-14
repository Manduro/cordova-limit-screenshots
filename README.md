This Cordova plugin combines two others:

#### [PrivacyScreenPlugin](https://github.com/devgeeks/PrivacyScreenPlugin)
The Android part of this plugin is used. It sets `FLAG_SECURE` which achieves two things:

- It prevents users from taking screenshots.
- It hides the app interface in the task switcher.


#### [cordova-plugin-detect-screenshot](https://github.com/Restocks/cordova-plugin-detect-screenshot)
The iOS part of this plugin is used. It detects when users take a screenshot.
