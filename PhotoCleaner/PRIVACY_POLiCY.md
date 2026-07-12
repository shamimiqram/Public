# Privacy Policy — Photo Cleaner

**Last updated:** July 2026  
**App name:** Photo Cleaner  
**Package name:** com.kazisoft.photocleaner  
**Developer:** KaziSoft  
**Developer contact:** shamimeakram@gmail.com

---

## 1) Overview

Photo Cleaner is an **offline** Android app that helps you find duplicate and similar photos, score photo quality, and free storage on your device. This Privacy Policy explains what information is handled when you use the app.

All scanning, AI analysis (MediaPipe / on-device models), and cleanup logic run **on your device**. The app does **not** declare an `INTERNET` permission and does not send your photos to our servers.

---

## 2) Data We Collect

### 2.1 We do not collect personal data on our servers

Photo Cleaner does **not** require an account and we do **not** operate our own server to collect or store your personal information, photos, or usage analytics.

### 2.2 Data stored locally on your device (offline)

The app stores some information **only on your device** so cleaning features work:

- **Photo / video library index:** metadata needed to detect duplicates and similar photos (for example content hashes, similarity embeddings, quality scores, folder info), derived from media you grant access to via Android MediaStore
- **Settings:** language, theme, match threshold, keep rule, and related preferences
- **Cleanup history / soft-trash records:** what you deleted or moved and when (for history and restore-related features where the system supports them)
- **Compressed copies you create:** if you use Resize & compress, new files may be saved under a Photo Cleaner folder on your device (for example `Pictures/PhotoCleaner`)

This information stays in the app’s local storage (and, for media you keep or export, in your device gallery folders). It is not sent to us.

### 2.3 Photos and videos on your device

To scan and clean your gallery, the app requests **Photos and videos** access (or legacy storage access on older Android versions). The app reads media through Android’s **MediaStore** APIs.

- Photos and videos are processed **on-device** only.
- We do not upload your media to the cloud.
- Deleting media uses Android’s system confirmation / delete flows where available; you control what is removed.

---

## 3) Third‑Party Services

Photo Cleaner’s core product is designed to work **without** accounts, ads, or analytics SDKs.

- **No advertising SDK** is included for the core offline cleaner experience described in this policy.
- **No separate analytics / crash-reporting backend** of ours receives your photos.

On-device machine learning uses **MediaPipe / TensorFlow Lite models bundled with the app**. Model inference runs locally; those libraries do not require sending your images to Google for Photo Cleaner’s scan features.

If a future build adds optional third-party services (for example ads or cloud backup), that version’s store listing and an updated Privacy Policy will describe them. Google’s policies (when such services apply):

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Ads technologies](https://policies.google.com/technologies/ads)

---

## 4) How We Use Data

We use locally stored data only to:

- Scan and group duplicate / similar photos and related media
- Score quality and suggest which items to keep or delete
- Remember your settings and language
- Show cleanup history and related in-app tools
- Create compressed copies when you choose Resize & compress

---

## 5) Data Sharing

We do not sell your data.

We do not share your photos or personal data with third parties for Photo Cleaner’s offline cleaning features, because processing stays on your device and we do not operate a collection server for this app.

---

## 6) Data Retention

- **On-device index, settings, and history** remain until you clear the app’s storage or uninstall the app.
- **Gallery media** remains under your control in the system gallery / MediaStore until you delete it (or the system trash restores/expires items, where applicable).
- Clearing app data removes Photo Cleaner’s local database and preferences; it does not by itself delete your original gallery photos unless you used an in-app delete action.

---

## 7) Children’s Privacy

Photo Cleaner is suitable for a general audience. We do not knowingly collect personal information from children on our servers. If you believe a child has provided personal information to us, contact us at **shamimeakram@gmail.com**.

---

## 8) Your Choices and Controls

- You can deny or revoke **Photos and videos** (or storage) permission in Android Settings; without access, scanning and cleaning features will be limited or unavailable.
- You can change language, theme, match threshold, and keep rules in Settings.
- You choose which items to delete; the system may ask you to confirm.
- You can delete all locally stored app data by clearing the app’s data from Android Settings or uninstalling the app.

---

## 9) Changes to This Policy

We may update this Privacy Policy from time to time. The “Last updated” date will be changed when we update it.

---

## 10) Contact

If you have questions about this Privacy Policy, contact:  
**shamimeakram@gmail.com**

---

## Hosting note (Play Console)

For Google Play, host a public URL to this policy (for example on GitHub Pages or your Public docs repo), then paste that URL into Play Console → App content → Privacy policy.

Suggested raw GitHub URL pattern (after you publish the file):  
`https://raw.githubusercontent.com/shamimiqram/Public/main/PhotoCleaner/PRIVACY_POLICY.md`  
or a rendered blob URL such as:  
`https://github.com/shamimiqram/Public/blob/main/PhotoCleaner/PRIVACY_POLICY.md`
