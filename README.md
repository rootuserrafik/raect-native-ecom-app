# React-Native-Ecommerce
A boilerplate for a ecommerce mobile app using React Native and Redux.
IOs and Android
## Features🔥
- Login 
- Signup
- Social Login
- Recover Account
- Cart (List)
- Add To Cart
- Remove Cart
- Category
- Best Selling
- Payment Processor (RazorPay)
- Profile
- Filters
- Product Review (Listing)
- Write Product Review
- Multiple Shipping address
- Order History
- Wish List (With Redux)
- Google Ads (Replace your app id in : AndroidManifest.xml and info.plist) 
- Search (Coming soon) 

#
## 
## ❤️ 
## Get Started


#### 1. Installation

On the command prompt run the following commands

```sh
$ git clone https://github.com/eramudeep/react-native-ecommerce.git

$ cd react-native-redux-starter/

$ npm install
```
#### 2. Simulate for iOS
```sh
$ cd ios && pod install
```

**Method One**

*	Open the project in Xcode from **ios/react_native_redux_starter.xcodeproj**.

*	Hit the play button.


**Method Two**

*	Run the following command in your terminal.

```sh
$ react-native run-ios
```

#### 3. Simulate for Android

*	Make sure you have an **Android emulator** installed and running.

*	Run the following command in your terminal.

```sh
$ react-native run-android
```
#### 4. How to Decide the Navigation

*	Navigation is decided By  **navigationTypeTabs** Key definend in [app.json](./app.json).
*	**navigationTypeTabs** :  true, will give you the bottom Tabs and vice versa.
## Debugger
- [React Native Debugger](https://github.com/jhen0409/react-native-debugger) : The standalone app based on official debugger of React Native, and includes React Inspector / Redux DevTools
- [redux-devtools-extension](https://github.com/zalmoxisus/redux-devtools-extension) `2.13.5`

## Rename Project
Rename react-native app with just one command

![react-native-rename](https://cloud.githubusercontent.com/assets/5106887/24444940/cbcb0a58-149a-11e7-9714-2c7bf5254b0d.gif)

> This package assumes that you created your react-native project using `react-native init`.

#### Installation
```
yarn global add react-native-rename
or
npm install react-native-rename -g
```

Switch to new branch first
>better to have back-up

```
git checkout -b rename-app
```

#### Usage
```
react-native-rename <newName>
```

> With custom Bundle Identifier (Android)
```
react-native-rename <newName> -b <bundleIdentifier>
```

#### Example
```
react-native-rename "Travel App"
```
> With custom Bundle Identifier
```
react-native-rename "Travel App" -b com.junedomingo.travelapp
```


