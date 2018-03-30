YouTube Video Uploader for Android
===========

This code is Forked from "YouTube Direct Lite for Android". The code is a reference implementation for an Android OS application that captures video, uploads it to YouTube, and submits the video to a [YouTube Direct Lite](http://code.google.com/p/youtube-direct-lite/) instance.

For more information, you can check the original project although is no longer maintained [YouTube Direct Lite for Android](https://github.com/youtube/yt-direct-lite-android).

This application utilizes [YouTube Data API v3](https://developers.google.com/youtube/v3/) , [YouTube Android Player API](https://developers.google.com/youtube/android/player/), [YouTube Resumable Uploads](https://developers.google.com/youtube/v3/guides/using_resumable_upload_protocol?hl=en), [Google Play Services](https://developer.android.com/google/play-services/index.html) and [Plus API](https://developers.google.com/+/mobile/android/Google).

To use this application,

1.Create a project in your [Google Developers Console](https://console.developers.google.com),
1.  Enable the YouTube Data API v3 and Google+ API in the project you have created.
1.  Create a client ID for Android, using your SHA1 and package name. 
    Read here for more understanding [Register your Android app](https://developers.google.com/youtube/android/player/register)
1.  Plug in your Playlist Id into Constants.java and Android API Key into Auth.java
1.  Done! Enjoy the show!
