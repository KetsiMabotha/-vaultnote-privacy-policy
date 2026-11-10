# Privacy Policy for VaultNote Editor

**Effective Date:** November 10, 2026  
**Developer / Studio:** Driem Studio  
**Application Name:** VaultNote 
**Package Name:** `com.driemstudio.vaultnote`  
**Contact Email:** Vaultnote.support@gmail.com

VaultNote Editor ("the App", "we", "us", or "our") is committed to protecting your privacy. This Privacy Policy explains our practices regarding user data, permissions, and device storage.

---

## 1. Summary: 100% Offline, Zero Data Collection

- **No Data Collected:** We do not collect, transmit, sell, or share any personal information, usage analytics, crash logs, or identifiers.
- **No Advertisements:** VaultNote Editor contains zero advertisements, zero advertising SDKs, and zero tracking cookies.
- **No Network Connectivity Required:** The App operates completely offline and does not request or possess the Android `INTERNET` permission.
- **No User Accounts:** There is no registration, account creation, or login required.

---

## 2. Your Notes and Content Stay on Your Device

All notes, checklists, tags, draft edits, timestamps, colors, and settings created in VaultNote Editor are stored exclusively on your local device in a sandboxed, private SQLite database managed by Android Room. 

- We do not operate remote servers, cloud databases, or sync relays for your note content.
- We cannot access, view, read, analyze, or recover your notes.
- Your data never leaves your device unless you explicitly choose to share or export it yourself.

---

## 3. Information We Do NOT Collect

We do not collect or process any of the following:
- Personal Identifiable Information (name, email address, phone number, address).
- Device Identifiers or Advertising IDs (Google Advertising ID, Android ID, IMEI, MAC address).
- Location Data (GPS, coarse location, or IP address).
- Contacts, Photos, Camera, Microphone, or Media files.
- Analytical or Telemetry Data (we do not use Google Analytics, Firebase Analytics, Flurry, or similar trackers).

---

## 4. Advertising & Monetization Disclosures

VaultNote Editor is completely ad-free. The App does not integrate Google AdMob, Unity Ads, AppLovin, or any third-party ad networks.

When completing the Google Play Console **Data Safety Form** and **Ads Declaration**:
- **Contains Ads?** Select **"No"**.
- **Data Collection and Sharing?** Select **"No"** (the app does not collect or share any user data).

---

## 5. Device Permissions Requested

VaultNote Editor requests only the minimum Android system permissions necessary to provide user-requested offline functionality:

- **`android.permission.POST_NOTIFICATIONS`**: Used solely to display local reminder notifications for specific notes that you schedule, and optional daily writing prompts if enabled by you.
- **`android.permission.VIBRATE`**: Used solely for haptic feedback and vibrating alerts when a scheduled note reminder fires.
- **`android.permission.RECEIVE_BOOT_COMPLETED`**: Used solely to re-register your scheduled local reminders with Android's `AlarmManager` after your device reboots.

The App **does NOT** request:
- `INTERNET` or `ACCESS_NETWORK_STATE` (cannot communicate over the web).
- Storage or media permissions (`READ_EXTERNAL_STORAGE`, `READ_MEDIA_IMAGES`). File exports are handled directly through standard Android system shares and storage access frameworks.

---

## 6. Data Sharing, Export, and Backups

### User-Initiated Export
If you choose to export your notes (such as saving a ZIP archive, Markdown file, JSON file, or plain text note), VaultNote Editor uses Android's native system share sheet. The exported file is sent solely to the destination or application you select (such as local device storage, your private cloud drive, or messaging apps). We do not receive, inspect, or store any copy of exported files.

### Android System Backups
The App declares `android:allowBackup="true"` in its manifest. If you have Android's automated device backup enabled on your device (Google Drive Device Backup), your local app data may be included in your personal encrypted device backup tied to your Google Account. This process is managed entirely by Android OS and Google, not by Driem Studio.

---

## 7. Data Retention and Deletion

Because all your data is stored strictly on your local device:
- You retain complete control over your content at all times.
- Deleting a note inside the App moves it to the local Trash or permanently deletes it from the SQLite database.
- Tapping **"Clear all local data"** in Settings permanently deletes all local notes and settings.
- Clearing the App’s data in Android Settings or uninstalling the App permanently and immediately deletes all notes stored by the App. Because we run zero servers, deleted data cannot be retrieved or recovered by us. Always create an export backup before uninstalling or changing devices.

---

## 8. Children’s Privacy

VaultNote Editor is designed for general audiences and does not collect personal data from anyone, including children under the age of 13.

---

## 9. Compliance with Global Privacy Laws (GDPR, CCPA, UK GDPR)

Because VaultNote Editor does not collect, store, transmit, or process any personal data or personal identifiers on remote servers, no personal data processing or cross-context behavioral tracking takes place under the General Data Protection Regulation (GDPR), the California Consumer Privacy Act (CCPA), or UK GDPR.

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted to this page with an updated Effective Date.

---

## 11. Contact Information

If you have questions, feedback, or concerns regarding this Privacy Policy or VaultNote Editor, please contact us:

- **Developer / Studio:** Driem Studio
- **Contact Email:** Vaultnote.support@gmail.com
