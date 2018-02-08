# Pure SDK

## What is Pure SDK?
Pure SDK is a SDK to provide location awareness for your app. Location data is gathered and sent to the cloud for analysis and makes it possible to target users in other contexts based on location data from your users. The SDK is available for iOS and Android.

The SDKs relies on OS-level location data collection methodologies (Google’s Awareness API and iOS’s Significant Changes API) to assess the current state of the device and trigger appropriate scanning logic.

All configurations used by the SDK are provided by an external endpoint, which makes it possible to change the configuration without releasing a new version of the application. It is also possible to use different configurations based device type, Android version, etc.

The SDK relies on scanning jobs running in the background. Below you will find information on battery usage, required user opt-ins and permissions, privacy and many details about the data collected and the data flow. The SDK is built to be lightweight and easily configurable in the cloud.  


### How to implement
The documentation for the Pure SDK depends on your operating system:

* [Android](https://github.com/unacast/pure-sdk-android)
* [iOS](https://github.com/unacast/pure-sdk-ios)

