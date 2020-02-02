![ƀ](/images/screen.jpg)  ![ƀ](/images/screen2.jpg)  ![ƀ](/images/screen3.jpg) 
![ƀ](/images/screen4.jpg)  ![ƀ](/images/screen5.jpg) ![ƀ](/images/screen6.jpg)


For build DangerWallet need to install:
 
1. Java 7 or up
2. SdkVersion = 26
3. buildToolsVersion = '26.0.3' (android 8.0.0)
4. NDK r15c (or r16b) (https://developer.android.com/ndk/downloads/older_releases.html)
5. gradle-4.1
6. Clone this repo:
   git clone https://github.com/dngrcoin/DangerWalletAndroid.git
7. Create a local.properties file, specify the path to the NDK and SDK in it, for example:

   ndk.dir=/home/android/ndk/android-ndk-r15c

   sdk.dir=/home/android/sdk

8. RUN:
  ./gradlew assembleDebug
9. APK file will be located: /DangerWalletAndroid/app/build/outputs/apk/loaf/debug/

==========================================================
Can be assembled using Android studio

1. Download and install Java 7 or up
2. Download and install the Android studio
3. Download NDK r15c (or r16b) from the [NDK Archives](https://developer.android.com/ndk/downloads/older_releases.html)
4. Clone this repo:
   git clone https://github.com/dngrcoin/DangerWalletAndroid.git
5. Open the project with Android Studio
6. Change `Android NDK Location with the path to NDK r15c that you downloaded earlier
7. Go to SDK Manager and download the SDK Platforms "26" and SDK Tools '26.0.3'
9. Build -> Rebuild Project

==========================================================
The MIT License (MIT)

Copyright (c) 2015 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



