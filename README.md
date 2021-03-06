<h3 align="center">
  <a href="https://www.plattar.com/">
    <img src="Graphics/icon.png?raw=true" alt="Plattar Logo" width="500">
  </a>
</h3>

[![Twitter: @plattarglobal](https://img.shields.io/badge/contact-@plattarglobal-blue.svg?style=flat)](https://twitter.com/plattarglobal)
[![Join Slack Chat](https://img.shields.io/badge/chat-slack-orange.svg?style=flat)](https://join.slack.com/t/plattar-public/shared_invite/enQtMzkyNjIxOTM1NjE4LTNkZmRiNWRkOTQ2MWQ4MTRlYTgyY2U0MGQxNjkyYzQ3MTc0NDAyZjE3MmU4MzRjNWQzYWM0NDA4YzRhNDBmNzA)
[![Build Status](https://circleci.com/gh/Plattar/app-android/tree/master.svg?style=shield&circle-token=039e652a97c51f9cc66c23bd36b86c282ae4652c)](https://www.plattar.com)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg?style=flat)](LICENSE)

_Plattar SDK_ is a native framework which works with the _Plattar CMS_. This is a sample repository with example code to help integrate the _Plattar SDK_ into existing Android Applications. Looking for [IOS Integration](https://github.com/Plattar/PlattarSDK-IOS-Public)?

***

### About

_Plattar is the Augmented Reality platform for product experiences._ Plattar’s simple AR creator, iOS and Android apps, 3D web viewers, developer-friendly SDKs & APIs empower brands to build amazing experiences that put virtual products directly into your customers hands.

- The Plattar SDK for Android lets you embed Plattar AR UI and 3D Rendering direct into your own apps and supports ARCore out of the box.
- Use the Plattar [Experience Builder](https://www.plattar.com/) to curate and enrich 3D content, and build and deploy updates direct to your SDK powered app.
- Create 3D content once and also deliver it dynamically to Plattar [3D Viewers](https://www.plattar.com/product) that can be embedded on your website.

3D content, rich media and interactions are created in the web based [Experience Builder](https://www.plattar.com/). Free trials are available at [plattar.com](https://www.plattar.com/)

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

### Documentation

Visit our dedicated [Wiki](https://github.com/Plattar/PlattarSDK-Android-Public/wiki) page for additional documentation.

### License

This project is licensed under the terms of the Apache 2.0 license. See the [LICENSE](LICENSE) file.
