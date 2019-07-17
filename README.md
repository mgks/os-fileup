# Project FileUp for Android

<img src="Logotype primary.png" width="200" height="" />

Os-FileUp: WebView based project to help android developers understand how to upload and process images/videos for any hybrid app. This project explains the usage of gallery and camera intent.

## Getting Started
This project contains android application build files, that you can download and use directly with latest Android Studio. Follow further steps to get started in your personalised environment.

### Requirements
Minimum Android API 16+ (4.1 JellyBean) SDK *(it all works but looks kinda ugly in JB)*.
You can use any IDE of your choice but to be specific, I used latest Android Studio *(till the last project update)* with updated SDKs and Builds.

### Test Run
Just putting these basic steps to help starters:
1. `File > Open` choose project folder and let android studio download supportive libraries.
2. `Build > Clean Project` and `Build > Rebuild Project`
3. If everything goes alright, you can start testing
4. In case or any error, check Build and Logcat tab for details

### Permissions
Followings are permissions required for all the mentioned features to work.
```xml
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE"/>
<uses-permission android:name="android.permission.CAMERA"/>
```
`INTERNET` permission is required to access online content and `WRITE_EXTERNAL_STORAGE`+`CAMERA` permissions to take photo from camera and save it to gallery.

## About Project

This project is initially developed by **[Ghazi Khan](https://infeeds.com/u/mgks)**.

#### I'd appreciate even your little contribution to my work, it helps me keep such open-source projects updated. If this project helped you or your business and you feel like donating some change, you can Paypal me - getmgks@gmail.com or buy me a coffee from the button below.

<a href="https://ko-fi.com/Z8Z4BPQ6" target="_blank" title="Buy me a Coffee"><img width="150" style="border:0px;width:150px;" src="https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0" border="0" alt="Buy Me a Coffee at ko-fi.com" /></a>

## License
This project is published under the MIT License - check out [LICENSE.md](LICENSE.md) file or read [MIT license](https://opensource.org/licenses/MIT) for more details.

## Acknowledgment
You can post any issue(s) you are facing with regards to the project in the [Issues section](https://github.com/mgks/Os-FileUp/issues).
If you want to contribute to the project, you're most welcome to help make a smarter project than it is.

### Special Credits
Thanks [mansya](https://github.com/mansya) for the updated logo.

**PROJECT NOTE:** Android 4.4 doesn't support webview upload default method and it's a permanent bug as no more KitKat updates are going to be made. All other versions are working fine.

`A PERSONAL NOTE: You must keep up with programming. Sometimes it's difficult and other times easy but fun overall. You can create your own world with programming and that's what makes this job interesting. All the best for your next voyage.`
