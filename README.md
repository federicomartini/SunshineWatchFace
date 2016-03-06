# SunshineWatchFace
Watch Face for Sunshine APP developed by Udacity

# Build
To build this application you need to install the following project dependencies:
 classpath 'com.android.tools.build:gradle:1.3.0'
 classpath 'com.google.gms:google-services:1.3.1'

For the App module you need to have in your environment the following build tool version:
 compileSdkVersion 21
 buildToolsVersion "21.1.2"

and all the following dependencies:
 compile 'com.github.bumptech.glide:glide:3.5.2'
 compile 'com.android.support:support-annotations:22.2.0'
 compile 'com.android.support:gridlayout-v7:22.2.0'
 compile 'com.android.support:cardview-v7:22.2.0'
 compile 'com.android.support:appcompat-v7:22.2.0'
 compile 'com.android.support:design:22.2.0'
 compile 'com.android.support:recyclerview-v7:22.2.0'
 compile 'com.google.android.apps.muzei:muzei-api:2.0'
 compile 'com.google.android.gms:play-services-wearable:8.3.0'
 compile 'com.google.android.gms:play-services-gcm:8.3.0'

For the Wearable module you need to have in your environment the following build tool version:
 compileSdkVersion 23
 buildToolsVersion "23.0.2"

and the following dependencies:
 compile 'com.google.android.support:wearable:1.3.0'
 compile 'com.google.android.gms:play-services-wearable:8.3.0'

# Install
To install the App module on your device/emulator, you have to ensure your Android API versione is 10 or above.
To install the Wearable module on your device/emulator, you have to ensure your Android API versione is 21 or above.

The following permissions will be needed:
android.permission.INTERNET
android.permission.READ_SYNC_SETTINGS
android.permission.WRITE_SYNC_SETTINGS
android.permission.AUTHENTICATE_ACCOUNTS
android.permission.ACCESS_NETWORK_STATE
android.permission.WAKE_LOCK
com.google.android.c2dm.permission.RECEIVE
com.example.android.sunshine.app.permission.C2D_MESSAGE
com.google.android.permission.PROVIDE_BACKGROUND
