# SwissPassMobile SDK v4 for iOS and iPadOS

Copyright (C) Schweizerische Bundesbahnen SBB, 2024

## Overview

SwissPassMobile SDK is a client library that enables the integration of the digital SwissPass card into your mobile app.

### SwissPass Mobile

SwissPass Mobile enables travelers to display public transport travelcards conveniently on a mobile device. 

* SwissPass Mobile can be integrated into your app in 2 different ways, either as a fullscreen representation using the `SwissPassMobileViewController` or embedded in a custom screen of your app using the `SwissPassMobileCardViewController`. 
* SwissPass Mobile can be activated by the user in up to 3 different apps simultaneously. In case of a forth activation, the first activation will be deleted automatically.
* When performing a logout operation, an existing SwissPass Mobile will not be deactivated until another user performs a login operation in the same app. In this case, the existing SwissPassMobile will be deactivated automatically.

## How to use the SDK

The SwissPassMobile SDK is written in Swift 5 and compiled using the option *Build Libraries for Distribution* with deployment target iOS 12. It is distributed as a binary XCFramework. 

In addition:

* Make sure to integrate the *Swift Standard Libraries* in your build. I.e., the option *Embedded Content Contains Swift Code* (EMBEDDED_CONTENT_CONTAINS_SWIFT) must be set to YES.

### Swift Package Manager

The SDK can be integrated into your build process as an XCFramework using the Swift Package Manager. To do so, just add the package by using the following url

```
https://github.com/SchweizerischeBundesbahnen/SwissPassMobileSDK-iOS.git
```

## License

This project is licensed under [LICENSE.md](./LICENSE.md).

## Additional information

Further documentation is available on the NOVA UserGroup website.
### Contact

General inquiries, suggestions, bug reports and feedback can be made via the NOVA UserGroup website or the SwissPass Alliance.
