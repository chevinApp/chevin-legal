# Privacy Policy for Chevin

**Last updated: October 25, 2026**

This Privacy Policy explains how Chevin ("we", "us", or "our") handles your information when you use our mobile application.

**1. On-Device Processing**
Chevin is an AI-powered photo curation tool designed with privacy as a fundamental priority. **All photo processing and AI analysis (blur, exposure, aesthetic score, face detection, duplicate grouping) runs entirely on your device.**
We do not upload, store, or transmit your photos, face data, or the results of the analysis to any server. We do not have servers that receive your data, we do not require an account, and we do not use advertising or analytics services of our own.

**2. Permissions We Request**
* **Photos (`READ_MEDIA_IMAGES` / `READ_MEDIA_VISUAL_USER_SELECTED`):** used only to show your photos inside the app and analyze them on your device. On Android 14 and later you can give access to your whole gallery or only to the photos you choose, and change this at any time in the system settings.
* **Notifications (`POST_NOTIFICATIONS`):** used only to show the progress of an analysis while it runs in the background.
* **Foreground service:** lets an analysis continue when you leave the app; it is always visible as a notification and stops when the analysis ends or you cancel it.

**3. Your Photos Stay Under Your Control**
Chevin only suggests which photos to keep or discard. Nothing is changed in your gallery until you confirm an action, and Android always asks for your confirmation:
* **Move to trash:** photos are moved to the system trash, where you can restore them for about 30 days before the system deletes them permanently.
* **Add to favorites** and **Export album:** mark photos as favorites or copy the selected photos into a new album on your device.

**4. Third-Party Services**
Chevin uses the following third-party libraries. All of them run on your device and none of them receives your photos:
* **Google ML Kit (face detection):** used to detect whether a photo contains faces, so that important photos are not mistakenly flagged as low quality. It does not identify people and does not send images or biometric data to Google.
  However, ML Kit sends Google some **technical diagnostic and usage data**: device information (model, operating system version), app information (package name and version), a random per-installation identifier, performance metrics (such as processing time), the configuration used (such as the format and resolution of the analyzed images), event types and error codes. Google uses this data to monitor and improve ML Kit; it is encrypted in transit (HTTPS) and does not reveal the content of your photos. More information: [ML Kit data disclosure](https://developers.google.com/ml-kit/android-data-disclosure) and [Google Privacy Policy](https://policies.google.com/privacy).
* **OpenCV and TensorFlow Lite:** used on your device for image quality assessment and feature extraction. They do not send any data.

**5. Data Stored on Your Device**
The app stores on your device only:
* the results of your analyses (scores, groups, analysis history) in a local database;
* your preferences (language, theme, sound volume, tutorial status);
* the personal taste model, built from the choices you correct, so that future suggestions match your taste.

This data never leaves your device: we never receive it, and it is excluded from Android backups and device-to-device transfers. You can delete it at any time from the app's settings (clear cache and history), by clearing the app's data in the system settings, or by uninstalling the app.

**6. Children**
Chevin is not directed at children under 13 and does not knowingly collect personal information from anyone.

**7. Changes to This Privacy Policy**
We may update this Privacy Policy from time to time. Changes are published on this page with a new "Last updated" date.

**8. Contact Us**
If you have any questions or suggestions about this Privacy Policy, contact us at: chevin.feedback@gmail.com
