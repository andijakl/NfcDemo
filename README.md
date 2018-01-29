# NfcDemo
Example App: NFC Demo for Android with Kotlin

Finished demo app, implements the following NFC features for Android with Kotlin:

- Register for NDEF tags containing a URI / URL record
- Analyze the NDEF tag contents and print these into a list
- Handle NFC tags in app startup (intent delivered through onCreate()) and when the app is already running (onNewIntent())
- Set a pending intent for enabling foreground dispatch to read and analyze all NFC tags tapped while the app is running

To work through the tutorial in the blog post (article coming soon), download the [starting app](https://www.andreasjakl.com/08-android-nfcdemo-start/) and then follow the instructions in the article.

## Related Information

Released und MIT License. See the LICENSE file for details.

Developed by Andreas Jakl
* https://www.andreasjakl.com/
* https://twitter.com/andijakl