# fbads
Ad formats - https://developers.facebook.com/docs/audience-network/overview/ad-formats

Library - https://github.com/callstack/react-native-fbads

Placement creation steps - https://www.facebook.com/business/help/1195459597167215?id=211412110064838

facebook business - https://developers.facebook.com/apps/

android/build.gradle
	repositories {
		mavenCentral()
	}

android/app/build.gradle
	dependencies{
		implementation 'com.facebook.android:facebook-android-sdk:5.4.0'

		implementation 'com.android.support:multidex:1.0.3'
	}

android/app/src/main/res/values/strings.xml
	<string name="facebook_app_id">APP_ID</string>
	
android/app/src/main/AndroidManifest.xml
		<activity
			android:name="com.facebook.ads.InterstitialAdActivity"
			android:configChanges="keyboardHidden|orientation" />
        <meta-data android:name="com.facebook.sdk.ApplicationId" android:value="@string/facebook_app_id"/>
	
package.json
	dependencies{
		"react-native-fbads": "^7.0.3", -> for ad
		"react-native-fbsdk": "^3.0.0", -> for ad
		"react-native-gesture-handler": "^1.10.3", - for app ui
		"react-native-reanimated": "^1.13.2",, - for app u
		"react-native-router-flux": "^4.2.0",, - for app u
		"react-native-screens": "^2.18.0", - for app u
	}