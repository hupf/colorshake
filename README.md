# Color Shake

A Cordova demo App that changes the background color depending on accelerator values.


## How to build the app?

Ensure [Node and NPM are installed](https://docs.npmjs.com/getting-started/installing-node) on your system. Also install the SDK of the mobile platform you want to build the app for, e.g. [Android SDK](https://developer.android.com/sdk/installing/index.html).

Then install Cordova:

```
npm install -g cordova
```

Now, from within the project directory, add the platform:

```
cordova platform add android
```

And build the App:

```
cordova build android
```

Or run it on your device (make sure the device is connected, has [USB debugging enabled](https://developer.android.com/tools/device.html) and and you see it with the ```adb devices``` command):

```
cordova run android
```
