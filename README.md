#### Upgrade Cordova's android basic webview to a better CrossWalk one

Direction
* Run the shell script from your cordova directory
* This will fetch the lib needed and install the and update ant
* When done you need to add permission in DIR : platforms/android/AndroidManifest.xml, as shown below
* By default It will install both arm & 64, you can change this by removing one or the other before a build , see DIR : platforms/android/CordovaLib/xwalk_core_library/libs/

#### Get more info on crosswalk at their website
[crosswalk-project]: https://crosswalk-project.org/

```xml

    <uses-sdk android:minSdkVersion="10" android:targetSdkVersion="19" />

	<uses-permission android:name="android.permission.ACCESS_WIFI_STATE" />
	<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />

</manifest>

```
