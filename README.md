# SunshineWatchFace
Watch Face for Sunshine APP developed by Udacity

## Build
To build this application you need to install the following project 
dependencies:
 classpath 'com.android.tools.build:gradle:1.3.0'
 classpath 'com.google.gms:google-services:1.3.1'

For the App module you need to have in your environment the following 
build tool version:
```
 compileSdkVersion 21
 buildToolsVersion "21.1.2"
```

and all the following dependencies:
```
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
```

For the Wearable module you need to have in your environment the 
following build tool version:
```
 compileSdkVersion 23
 buildToolsVersion "23.0.2"
```

and the following dependencies:
```
 compile 'com.google.android.support:wearable:1.3.0'
 compile 'com.google.android.gms:play-services-wearable:8.3.0'
```

## Install
To install the App module on your device/emulator, you have to ensure 
your Android API versione is 10 or above. To install the Wearable 
module on your device/emulator, you have to ensure your Android API 
versione is 21 or above.

The following permissions will be needed:
```
android.permission.INTERNET
android.permission.READ_SYNC_SETTINGS
android.permission.WRITE_SYNC_SETTINGS
android.permission.AUTHENTICATE_ACCOUNTS
android.permission.ACCESS_NETWORK_STATE
android.permission.WAKE_LOCK
com.google.android.c2dm.permission.RECEIVE
com.example.android.sunshine.app.permission.C2D_MESSAGE
com.google.android.permission.PROVIDE_BACKGROUND
```

## Support
Patches are encouraged, and may be submitted by forking this project 
and submitting a pull request through GitHub. Please see 
CONTRIBUTING.md for more details.

## License
Copyright 2015 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more 
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership. 
The ASF licenses this file to you under the Apache License, 
Version 2.0 (the "License"); you may not use this file except in 
compliance with the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, 
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or 
implied.  See the License for the specific language governing 
permissions and limitations under the License.

## Contact
For any questions, complaints and so on, please contact me. 
Any contact info is available on my profile.