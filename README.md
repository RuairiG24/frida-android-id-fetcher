# Frida Android ID Fetcher
A Frida script which fetches the Android ID of any android application

### What is an Android ID?

An Android ID is a 64 bit number which is unique to every combination of app-signing key, user, and device.
See the **ANDROID_ID** constant described <a href="https://developer.android.com/reference/android/provider/Settings.Secure">here<a>.
  
Since the majority of users of android mobile phones will only have a single user account on their device, the Android ID can essentially be viewed as an ID which identifies a unique device-application pairing (even across installations of an app).

### Usage
  

