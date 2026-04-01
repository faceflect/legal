# FaceFlect Privacy Policy

**Effective Date:** March 16, 2026  
**Developer:** AuraKin Solutions  
**Contact:** faceflect@gmail.com

Thank you for using FaceFlect! Your privacy is of utmost importance to us. This Privacy Policy outlines how we collect, use, and protect your information when you use our mobile application ("FaceFlect"). By using FaceFlect, you agree to the terms described in this policy.

## 1. Information We Collect

FaceFlect is designed to process and store your data **locally on your device**. We prioritize your privacy through completely offline, on-device processing. **We do not collect, transmit, or store any of your data on external servers.**

### 1.1 Facial Data and Biometrics
FaceFlect uses your device's camera to detect and recognize faces for profile enrollment and the "Aura Scanner" feature. **All facial recognition data and biometric representations (mathematical embeddings) are encrypted and stored exclusively on your local device.** These embeddings are generated using a local on-device machine learning model (TensorFlow Lite) and do not contain recognizable image data. No facial data is ever transmitted off your device.

### 1.2 User-Provided Content
Profile names, life journey details, relationship connections, tags, and dates you enter to build your family tree are stored locally.

### 1.3 Images and Photos
Photos you capture or select from your gallery for user profiles are stored locally on your device.

### 1.4 Diagnostic Data (Crash Logs)
If the app encounters an unexpected error, a local crash log is generated and stored on your device. This log contains technical information about the error (such as stack traces and device model) and **does not include any personal, facial, or family tree data.** You may choose to share this log with us via a manual export for troubleshooting purposes. We do not automatically collect or transmit crash reports.

## 2. Permissions We Request

To provide our core features, FaceFlect requests the following Android permissions:

- **Camera:** Required to capture photos for enrolling profiles, verifying identity, and using the real-time Aura Scanner for face recognition.
- **Storage / Photos / Media:** Required to select profile pictures from your gallery and to import or export your encrypted family tree backups. On Android 13 and above, only the granular `READ_MEDIA_IMAGES` permission is requested.
- **Biometric Authentication (USE_BIOMETRIC):** Used optionally to secure your account login natively on your device using fingerprint or face unlock.
- **Notifications (POST_NOTIFICATIONS):** Used on Android 13 and above to send you optional birthday reminders for family members you have added to your family tree. You can disable these notifications at any time in your device settings.

## 3. How We Use Your Information

The data processed is used **strictly** to provide the on-device features of FaceFlect:

- To map and visualize your family tree and relationships.
- To enable face recognition and the Aura Scanner to identify enrolled family and friends.
- To generate "Relationship Insights" based on logged interactions.
- To facilitate secure on-device biometric login.
- To send optional birthday reminder notifications for family members.

## 4. Data Sharing and Transfer

**We do not sell, rent, or share your personal data, facial data, or family tree information with any third parties.**

- **No Server Communication:** FaceFlect does not connect to any remote servers. All data remains entirely on your device.
- **User-Initiated Export:** You have the option to export your family tree data (as an encrypted `.ffb` backup file). This export is fully initiated and controlled by you, and you can secure it with a passcode. FaceFlect is not responsible for the security of data once exported by the user to external storage or sharing services.

## 5. Third-Party Libraries and SDKs

FaceFlect utilizes third-party tools for processing that operate **entirely locally on your device**. These libraries do not transmit any data off your device:

- **Google ML Kit (Face Detection):** Used locally to detect faces within the camera frame. No image or facial data processed by ML Kit is transmitted off the device by this SDK.
- **TensorFlow Lite (On-Device Model):** Used to generate encrypted mathematical representations (embeddings) from detected faces. This processing happens entirely within the app's local sandbox.
- **Android Biometric Prompt (AndroidX):** Used for securely authenticating the account owner using the device's built-in biometric hardware (fingerprint, face unlock). Authentication is handled entirely by the Android operating system.
- **Android Room Database with SQLCipher:** Used to store all application data in a locally encrypted database on the device.
- **Google Protobuf:** Used for efficient local data serialization of family tree structures.

## 6. Data Security

We take the security of your data seriously:

- **Encryption at Rest:** All sensitive data, including facial embeddings, is stored in a locally encrypted database (SQLCipher with AES-256 encryption).
- **No Network Access:** FaceFlect does not request the `INTERNET` permission. The app cannot connect to any external server, ensuring your data cannot be leaked through network traffic.
- **Backup Exclusion:** Sensitive data files are excluded from Android's automatic cloud backup mechanisms via `data_extraction_rules.xml`, ensuring that your facial data is not inadvertently backed up to Google Drive or other cloud services.

## 7. Data Retention and Deletion

Your data is retained only as long as you keep it on your device.

- **Profile Deletion:** You can delete individual profiles and their associated facial data at any time within the app.
- **Account Deletion:** You can delete your entire account and all associated data (including all facial embeddings, photos, and family tree structures) via the app's Settings screen. Doing so securely and permanently erases all related data from your local storage.
- **BIPA Retention Schedule:** In accordance with the Illinois Biometric Information Privacy Act (BIPA), FaceFlect will destroy your biometric data (facial embeddings) after the earlier of (a) the date your account is deleted, or (b) within three years of your last interaction with the app.
- **App Uninstallation:** If you uninstall FaceFlect, all local application data will be automatically deleted by the Android operating system.

## 8. User Consent and Explicit Opt-In

To satisfy global biometric privacy standards, FaceFlect requires your explicit, informed consent before any biometric processing occurs:

- **Biometric Processing Opt-In:** At first launch, you will be presented with a "Privacy Gate" where you must explicitly consent to the collection and on-device processing of facial biometric data. You can withdraw this consent at any time by deleting your account.
- **Camera Permission:** FaceFlect will request your explicit consent before accessing the camera. You can revoke this permission at any time through your device's system settings.
- **Biometric Authentication:** You may opt in or out of biometric login at any time within the app settings.
- **Notification Permission:** On Android 13 and above, FaceFlect will request your explicit consent before sending any notifications. You can revoke this permission at any time.

## 9. Children's Privacy

FaceFlect is not directed at children under the age of 13. The app allows the device owner to add profiles for family members, which may include children. However, all data processing is local and under the direct control of the device owner. It is the account owner's responsibility to manage profiles reflecting children's data. We do not knowingly collect personal information from children under 13.

## 10. International Users and Legal Compliance

FaceFlect is designed to comply with applicable data protection laws, including but not limited to:

- **GDPR (General Data Protection Regulation):** Since all data is processed and stored locally on the user's device and no data is transmitted to external servers, FaceFlect operates as a purely local tool. Users have full control over their data, including the right to access, modify, and delete it at any time.
- **CCPA (California Consumer Privacy Act):** FaceFlect does not sell personal information. All data is stored locally and is under the sole control of the user.
- **India's DPDP Act (Digital Personal Data Protection Act, 2023):** All personal data processing occurs exclusively on the user's device. No data is collected, stored, or processed by AuraKin Solutions on any external server.

## 11. Changes to this Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top. We encourage you to review this Privacy Policy periodically for any changes.

## 12. Contact Us

If you have any questions, concerns, or suggestions about our Privacy Policy, do not hesitate to contact us at:

**AuraKin Solutions**  
**Email:** faceflect@gmail.com
