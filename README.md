
# Rapport

I renamed the app to "SimpelWebApp" by editing the value assigned to 'app_name' in the 'strings.xml'
file. Internet access was enabled by changing the permissions in 'AndroidManifest.xml', 
this was done by adding this line: '<uses-permission android:name="android.permission.INTERNET"'/>.

In the 'activity_main.xml', I first deleted the TextView element and replaced it with a WebView.
I created the Webview and gave it an id with the following code:
```xml
<WebView
        android:id="@+id/my_webview"
        android:layout_width="match_parent"
        android:layout_height="match_parent" />
```

