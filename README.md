# Firebase Cloud Messaging (FCM)
FCM is just a demo of Android Application which implements Firebase Cloud Messaging.  

## Prerequisites
* Supported Android 4.1 or newer
* Android Studio 3.3.2 or higher
* google-services.json in app-level folder

## Features
* Subscribe and Unsubscribe with topics
* Get token
* Send message with payload both **notification** and **data**
* Send message with **a token**, **token group**, **a topic**, **condition**
* Handle message both **foreground** and **background**
* Customize notification
* Support notification channel for Android 0 or newer

## Limitation in the message payload
* Notification : 2KB limit and a predefined set of user-visible keys
* Data : 4KB of custom key-value pairs

## Screenshots
<table width="70%">
	<tr>
	  <th width="30%"><img src="https://github.com/nishchaljs/InAppMsg/blob/main/result.png"></th>
	  <th width="30%"><img src="https://cloud.githubusercontent.com/assets/1763410/16553886/8f8af5da-41f5-11e6-85c4-cb6937c80bab.png"></th>
	</tr>
</table>
<table width="100%">
	<tr>
	  <th width="100%"><img src="https://github.com/nishchaljs/InAppMsg/blob/main/Firebase_console.png"></th>
	</tr>
</table>
