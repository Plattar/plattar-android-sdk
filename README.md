<h3 align="center">
  <img src="Graphics/icon.png?raw=true" alt="Plattar Logo" width="500">
</h3>

[![Twitter: @plattarglobal](https://img.shields.io/badge/contact-@plattarglobal-blue.svg?style=flat)](https://twitter.com/plattarglobal)
[![Join Slack Chat](https://img.shields.io/badge/chat-slack-orange.svg?style=flat)](https://plattar.slack.com/messages/CB85ZEKNZ)
[![Build Status](https://circleci.com/gh/Plattar/app-android/tree/master.svg?style=shield&circle-token=039e652a97c51f9cc66c23bd36b86c282ae4652c)](https://www.plattar.com)

_Plattar SDK_ is a native framework which works with the _Plattar CMS_. This is a sample repository with example code to help integrate the _Plattar SDK_ into existing Android Applications. Looking for [IOS Integration](https://github.com/Plattar/PlattarSDK-IOS-Public)?

***

### About

Plattar is an Augmented Reality Content Management System (CMS). The Plattar SDK allows developers to add the Plattar UI and 3D Rendering into existing Android applications. Adding content/interactions will still need to go through the CMS. 

This Plattar Project will compile and run without modifications and uses a sample application from the Plattar Staging Server which is an environment used for testing latest dev code.

### CMS Access

This Plattar Project can be tied into a custom application if required. Please [Generate](https://github.com/Plattar/PlattarSDK-Android-Public/wiki/Generating-App-Key) the required _App Key_.

Once the _App Key_ is recieved, update the following file

```
// res/values/strings.xml

<resources>
    <string name="app_name">Plattar Project</string>
    <string name="app_code">APP KEY GOES HERE</string>
</resources>
```

Save, recompile and relaunch the app.

### Limitations

Plattar is designed to support multiple AR tracking backends. The following version of the SDK only supports Google ARCore. Attempting to launch any of the other backends is likely to lead to errors and problems.

ARCore is only supported on selected Android devices. Check the [Supported Device List](https://developers.google.com/ar/discover/supported-devices) for more info.

### Questions and Feature Requests

Please use the [Issue Tracker](https://github.com/Plattar/PlattarSDK-Android-Public/issues) for any questions, bug reports or feature requests.
