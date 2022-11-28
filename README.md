

# 
<img src="https://user-images.githubusercontent.com/70295997/204164772-653d0671-49aa-44ea-a155-dce73e75f9c4.png" width="50" /> *Automated Mobile Testing using Appium*

____

## Appium - an open-source tool for automating different types of mobile apps.


The mobile app marget is huge, and keeps increasing constantly.

It's essential to learn mobile app development and testing, due to the increasing demand.

____

Reports:

🔗 https://www.statista.com/topics/1002/mobile-app-usage

230 billion apps have been downloaded worldwide to mobile devices

🔗 https://www.statista.com/forecasts/1262892/mobile-app-revenue-worldwide-by-segment

the worldwide mobile revenue in 2020 amounted to $318 billion and is expected to reach $613 billion by 2025

____

🔵 Types of Mobile Apps

<img src="https://user-images.githubusercontent.com/70295997/204197612-0ca378ed-c00d-461e-86f1-320362f636f9.png" width=400/>

____


🔘 Native 🔘 

↣ ↣ developed for a particular mobile device or platform, such as Android or iOS)

↣ ↣ e.g., iPhone apps are written in Swift, and Android apps are written in Java

↣ ↣ better performing, high degree of reliability, as they use underlying system architecture and the device's built-in features

↣ ↣ can run in both online and offline modes

↣ ↣ tied to the mobile OS it was designed for, hence cannot be run on another OS

↣ ↣ development is costly, since the same app must be rewritten for another OS

↣ ↣ available for download on mobile via a respective app store.

↣ ↣ example 1: The Washington Post app is a native app bundled with iPhone. It can be downloaded from the Apple App Store

↣ ↣ example 2: The popular Instagram app on an Adroid devide is native.

____

🔘 Mobile Web 🔘 

↣ ↣ a.k.a. [PWA - Progressive Web Apps](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)

↣ ↣ accessed over a mobile browser

↣ ↣ easily accessed via built-in browsers, such as Safari on iOS and Chrome on Android

↣ ↣ browsers are primarily developed using tech such as HTML5 or JavaScript, which provide customization capabilties

↣ ↣ browsers are served from a server and not stored offline anywhere on a device

↣ ↣ common code base allows for access on any device with browsers, like any typical web app

↣ ↣ uses responsive design standards to cater to devices of different screen sizes and resolutions

↣ ↣ can access mobile-specific features, such as dialing a phone number or location-based mapping

↣ ↣ can only be accessed with a valid network (WiFi/5G/4G/3G)

↣ ↣ example 1: A mobile website of The New York Times can be opened with any mobile browser. The URL is http://mobile.nytimes.com. Can perform the same actions as web, such as browser refresh. Can open using the Safari app on an iPhone device or simulator running iOS.

↣ ↣ example2: Can also run the mobile site of The New York Times on an Android emulator running Adroid OS. Open the site on the default browser app.

____

🔘 Hybrid 🔘 

↣ ↣ a.k.a. [Cross-Platform](https://ionic.io/resources/articles/ionic-vs-react-native-a-comparison-guide)

↣ ↣ ↣ Cross-Platform *Web* Platforms: [Ionic](https://ionicframework.com/), [Cordova](https://cordova.apache.org/)

↣ ↣ ↣ [Cross-Platform *Native* Platforms](https://github.com/lana-20/native-reactnative-flutter#readme): [React Native](http://react-native.org/), [Xamarin](https://dotnet.microsoft.com/en-us/apps/xamarin), [Flutter](https://flutter.dev/), [NativeScript](https://nativescript.org/)

↣ ↣ consists of websites packaged in a native wrapper

↣ ↣ developed in web tech, such as HTML5, CSS, JavaScript, but run inside a native constainer, hence giving it the native app 'feel'

↣ ↣ relies on HTML rendering in the mobile browser, with a limitation that the browser is embedded within the app

↣ ↣ common code base for all the mobile OS, such as iOS and Android

↣ ↣ web-to-native abstraction layer enables access to device-specific capabilities - such as a camera, device local storage, and an accelerometer - which are nor accessible in Mobile Web apps otherwise

↣ ↣ Most favored approach for a company with a web page. The company often builds a hybrid app as a wrapper used over the web page.

↣ ↣ tools, such as PhoneGap and Sencha Touch, can be used to build a hybrid app

↣ ↣ can be downloaded via respective app stores

↣ ↣ example1: Evernote app is a hybrid app that can be downloaded from the respective app store.

____


🔵 [Architecture](https://github.com/lana-20/appium-architecture)

![image](https://user-images.githubusercontent.com/70295997/167332908-bf1758dd-1242-457b-9af9-3ecb1b42d636.png)


↣ XCUITest | Apple iOS

↣ UI Automator | Google Android

____


🔵 Pros

↣ open source

↣ cross platform

↣ no recompile/modify needed (e.g., to submit to an app store)

____


*12 Step Guide to configure and run Mobile Automation test cases using Appium* | 
------------ |
1.Download Java and set JAVA_HOME in environment variables. |
2.Download Android Studio from this [link](https://developer.android.com/studio). |
3.Check Android installation path on the machine. |
4.Set ANDROID_HOME environment variables path to SDK location and include bin folder paths in the PATH variable. |
5.Open Android Studio and configure an Emulator (AVD - Android Virtual Device). |
6.Open the Emulator and check if it’s working. |
7.Download Node.js from this [link](https://nodejs.org/en/download/). |
8.Set NODE_HOME environmental variables path. |
9.Download Appium Server from Node. |
10.Download Appium Java client library. |
11.Install Eclipse -- Create a Project in Eclipse -- Configure Appium libraries. |
12.Start Appium Server. |
