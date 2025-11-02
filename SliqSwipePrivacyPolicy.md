# Privacy Policy for SliqSwipe

**Last Updated:** November 2, 2025  
**Effective Date:** November 2, 2025

## 1. Introduction

Welcome to **SliqSwipe**, We are committed to protecting your privacy and ensuring transparency about how we handle your data. This Privacy Policy explains what information we collect, how we use it, and your rights regarding your personal data.

SliqSwipe is a photo management application designed to help you organize and declutter your device's photo gallery through an intuitive swipe interface.

**Developer Information:**
- **App Name:** SliqSwipe
- **Developer:** Nitesh Ray
- **Contact Email:** niteshr070104@gmail.com

By using SliqSwipe, you agree to the terms outlined in this Privacy Policy. If you do not agree with these terms, please do not use the App.

---

## 2. Information We Collect

### 2.1 Local Storage Access

SliqSwipe requires access to your device's photo gallery to provide its core functionality. Specifically:

- **Photo Metadata:** We access metadata about your photos including:
  - File names
  - Creation/modification dates
  - File sizes
  - File locations (URIs)
  
- **Photo Content:** The app displays your photos to enable you to review and manage them through our swipe interface.

**Important:** All photo access happens **locally on your device only**. We do NOT upload, transmit, or store your photos on any external servers.

### 2.2 App Preferences

We store minimal preference data locally on your device using Android SharedPreferences:

- **Onboarding Status:** A single boolean flag indicating whether you've completed the onboarding tutorial
- **Storage Location:** `sliqswipe_prefs` (local device storage only)

This preference data is stored in `Context.MODE_PRIVATE`, meaning it is accessible only by SliqSwipe and cannot be accessed by other applications.

### 2.3 Information We DO NOT Collect

SliqSwipe does **NOT** collect, store, or transmit:
- ❌ Personal identifying information (name, email, phone number, etc.)
- ❌ Location data or GPS coordinates
- ❌ Device identifiers (IMEI, advertising ID, etc.)
- ❌ Analytics or usage statistics
- ❌ Crash reports or diagnostic data
- ❌ Network activity or browsing history
- ❌ Contact lists or communication data
- ❌ Any data from other apps
- ❌ Your actual photo files (we only access metadata locally)

---

## 3. How We Use Information

The limited data we access is used solely for the following purposes:

### 3.1 Core Functionality
- **Display Photos:** To show your photos in the swipe interface
- **Organize by Date:** To group photos by month and year for easier management
- **Delete Management:** To facilitate photo deletion based on your swipe decisions
- **Storage Calculation:** To calculate and display storage space reclaimed after deletions

### 3.2 User Experience
- **Onboarding:** To remember whether you've completed the initial app tutorial and avoid showing it repeatedly
- **Session Management:** To track your photo review progress within a session

All processing happens **entirely on your device**. No data is sent to external servers or third parties.

---

## 4. Data Storage and Security

### 4.1 Local Storage Only

All data accessed by SliqSwipe remains **exclusively on your device**:
- Photos are accessed through Android's MediaStore API
- Preferences are stored in Android's private app storage
- No cloud storage or external databases are used

### 4.2 Security Measures

We implement the following security practices:

- **Scoped Storage:** We use Android's modern scoped storage access (MediaStore API) which provides system-level security
- **Permission-Based Access:** We only access photos after you explicitly grant storage permissions
- **No Network Permissions:** The app does not request or use internet permissions
- **Private App Storage:** All preference data is stored with `MODE_PRIVATE` flag, preventing access by other apps

### 4.3 Data Retention

- **Photos:** We never store copies of your photos. Access is temporary and in-memory only
- **Preferences:** Onboarding status is retained until you uninstall the app
- **Deleted Photos:** When you delete photos through the app, they are permanently removed from your device (subject to Android's system-level deletion mechanisms)

### 4.4 Data Deletion

You can delete all SliqSwipe data by:
1. **Uninstalling the App:** Removes all preference data automatically
2. **Clearing App Data:** Go to Settings > Apps > SliqSwipe > Storage > Clear Data
3. **Photo Deletion:** Photos deleted through the app are permanently removed from your device's gallery

---

## 5. Permissions Explained

SliqSwipe requests the following Android permissions:

### 5.1 Required Permissions

| Permission | Purpose | Why We Need It |
|------------|---------|----------------|
| **READ_MEDIA_IMAGES** (Android 13+) | To read and display your photos | Required to show photos in the swipe interface and organize them by date |
| **READ_MEDIA_VIDEO** | To access video files | Requested by Android's media access framework (currently unused) |
| **READ_EXTERNAL_STORAGE** (Android 12 and below) | To read photos on older Android versions | Legacy permission for accessing media files on devices running Android 12 or earlier |
| **WRITE_EXTERNAL_STORAGE** (Android 10 and below) | To delete photos on older Android versions | Required to delete photos on Android 10 and earlier devices |


### 6.1 Open Source Libraries

The app uses the following open-source libraries for UI and functionality:

- **Jetpack Compose:** Android's modern UI toolkit (Google)
- **Coil:** Image loading library for displaying photos
- **Accompanist Permissions:** Permission handling library (Google)
- **AndroidX Navigation:** Navigation framework (Google)

These libraries run **locally on your device** and do not transmit data externally.

---

## 7. Children's Privacy

SliqSwipe does not knowingly collect personal information from children under the age of 13. The app:

- Does not require age verification
- Does not collect personal information
- Does not have user accounts or profiles
- Does not have social features

Parents and guardians should supervise their children's use of the app, particularly when deleting photos.

---

## 8. Data Sharing and Disclosure

### 8.1 No Data Sharing

Since we do not collect personal data, we **do not share, sell, rent, or trade** any user information with third parties.

### 8.2 Legal Obligations

We may be required to disclose information if legally obligated to do so:

- In response to valid legal processes (subpoenas, court orders)
- To protect our rights, property, or safety
- To comply with applicable laws and regulations

**However, as we do not collect or store user data, there is effectively nothing to disclose.**

---

## 9. International Data Transfers

SliqSwipe operates entirely on your local device and does **not transfer data internationally** or across borders. All data remains within your device's storage.

---

## 10. Your Privacy Rights

Depending on your jurisdiction, you may have the following rights:

### 10.1 General Rights

- **Right to Access:** Request information about data we hold (in this case, minimal preference data)
- **Right to Deletion:** Delete all app data by uninstalling or clearing app data
- **Right to Rectification:** Modify preference settings within the app
- **Right to Object:** Revoke storage permissions at any time through device settings

### 10.2 California Privacy Rights (CCPA)

If you are a California resident:
- We do not sell personal information
- We do not collect personal information for commercial purposes
- You have the right to opt-out of data sales (not applicable as we don't sell data)

### 10.3 European Privacy Rights (GDPR)

If you are in the European Economic Area:
- **Legal Basis:** We process data based on your consent (granting permissions)
- **Data Minimization:** We collect only what's necessary for app functionality
- **Right to Withdraw Consent:** Revoke permissions in device settings at any time
- **No Profiling:** We do not engage in automated decision-making or profiling

### 10.4 Exercising Your Rights

To exercise any privacy rights:
1. **Revoke Permissions:** Go to device Settings > Apps > SliqSwipe > Permissions
2. **Delete Data:** Uninstall the app or clear app data
3. **Contact Us:** Email us at [Your Contact Email]

---

## 11. Updates to This Privacy Policy

We may update this Privacy Policy from time to time to reflect:

- Changes in app functionality
- Updates to legal requirements
- Improvements to our privacy practices

### 11.1 Notification of Changes

- **Material Changes:** We will update the "Last Updated" date at the top of this policy
- **Where to Find:** The latest version will always be available at [Your Privacy Policy URL]
- **App Updates:** Significant privacy changes will be communicated through app update notes on the Google Play Store

### 11.2 Your Continued Use

Your continued use of SliqSwipe after privacy policy updates constitutes acceptance of the revised policy.

---

## 12. Contact Information

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

**Email:** [Your Contact Email]  
**Developer:** Nitesh Ray  
**App Package:** xcom.niteshray.xapps.sliqswipe

We will respond to your inquiries within **7-14 business days**.

---

## 13. Compliance and Certifications

SliqSwipe is designed to comply with:

- ✅ **Google Play Store Developer Policies**
- ✅ **Android Privacy Best Practices**
- ✅ **GDPR** (General Data Protection Regulation - EU)
- ✅ **CCPA** (California Consumer Privacy Act - USA)
- ✅ **COPPA** (Children's Online Privacy Protection Act - USA)


---

## 15. Important Disclaimers

### 15.1 Photo Deletion

- Deleted photos are **permanently removed** from your device
- We recommend backing up important photos before using deletion features
- SliqSwipe is not responsible for accidental deletions
- Deleted photos cannot be recovered through the app

### 15.2 Data Backup

- If you have enabled Android's device backup features, your onboarding preference may be included in system backups
- Photo access and deletion logs are **not backed up** by SliqSwipe
- We do not control or access Android's backup mechanisms

### 15.3 Liability

SliqSwipe is provided "as is" without warranties. We are not liable for:
- Data loss due to user actions
- Device malfunctions
- Incorrect deletion operations
- Third-party access to your device

---

## 16. Transparency Commitment

We believe in complete transparency. Here's what makes SliqSwipe privacy-friendly:

✅ **Offline Operation:** Works without internet connection  
✅ **No Accounts:** No registration or login required  
✅ **No Tracking:** Zero analytics or tracking scripts  
✅ **No Ads:** Completely ad-free experience  
✅ **Open Permissions:** Clear explanation of why each permission is needed  
✅ **Local Processing:** Everything happens on your device  
✅ **No Server Communication:** No backend servers or databases  

---

## 17. Questions and Support

### 17.1 Privacy Questions

For privacy-specific inquiries:
- Email: [Your Contact Email]
- Subject Line: "SliqSwipe Privacy Inquiry"

### 17.2 App Support

For technical support or feature requests:
- Google Play Store Reviews
- Email: [Your Support Email]

### 17.3 Security Vulnerabilities

If you discover a security issue:
- Email: [Your Security Email]
- Subject Line: "SliqSwipe Security Report"
- We take security reports seriously and will respond promptly

---

## 18. Summary (TL;DR)

**SliqSwipe is built with privacy at its core:**

🔒 **What we access:** Your photos (locally only) to help you organize and delete them  
💾 **What we store:** One preference flag (whether you've seen the onboarding)  
🌐 **What we send:** Nothing. Zero. Nada. The app works completely offline  
🚫 **What we DON'T do:** Track you, sell data, show ads, or share information  
✨ **Your control:** Revoke permissions anytime. Delete all app data by uninstalling  

**Bottom Line:** Your photos stay on your device. We don't see them, store them, or know anything about you.

---

---

## 19. Acknowledgment

By downloading, installing, or using SliqSwipe, you acknowledge that you have read, understood, and agree to be bound by this Privacy Policy.

If you do not agree to this Privacy Policy, please do not use SliqSwipe.

---

**Thank you for trusting SliqSwipe with your photo management needs!** 📱✨

---

*This Privacy Policy is effective as of November 2, 2025 and was last updated on November 2, 2025.*
