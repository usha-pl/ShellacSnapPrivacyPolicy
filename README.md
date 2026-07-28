# Privacy Policy for Shellac Snap

**Last updated: July 28, 2026**

This privacy policy describes how Shellac Snap ("the app", "we", "I") collects, uses, and handles your information.

---

## Who I am

Shellac Snap is an independent app developed by a private individual. If you have any questions about this policy, you can contact me at **jaysradiohour@gmail.com**.

---

## What data the app collects and why

### Photos you take
When you photograph a record label, that image is sent to a private backend server operated by the developer. The server forwards the image to Google's Gemini AI API to extract text (artist name, title, label, catalog number). The image is processed in memory and is **not stored** on the server or by Google beyond the duration of the API call.

### Your Discogs personal access token
When you connect your Discogs account, your personal access token is stored **locally on your device only**, using your device's secure keychain (iOS Keychain / Android Keystore). It is never transmitted to or stored on the developer's servers. The app uses it to communicate directly with Discogs on your behalf.

### Your Discogs user ID
Your numeric Discogs user ID (a public identifier, not your token) is sent to the developer's backend server with each scan request. This is used solely to enforce a daily scan limit and prevent abuse. It is stored in a simple quota log that resets daily and is not shared with any third party.

### Records you add to your collection
Information about records you add (title, artist, grade) is stored locally on your device in a recent scans list. This data is also written to your Discogs collection via the Discogs API — it is governed by Discogs' own privacy policy once transmitted.

### Donation payments
If you choose to support the app via donation, payments are processed by a third-party payment processor. The developer does not collect or store your payment card details. Please review the payment processor's own privacy policy for details.

---

## What data is NOT collected

- The app does not collect your name, email address, or any personally identifying information
- The app does not use advertising or analytics SDKs
- The app does not track your location
- The app does not share your data with advertisers or data brokers
- Photos of your records are not stored, sold, or used for any purpose other than the immediate label-reading request

---

## Third-party services

The app interacts with the following third-party services:

| Service | Purpose | Their privacy policy |
|---|---|---|
| Discogs | Collection management | discogs.com/privacy |
| Google Gemini API | AI label reading | ai.google.dev/terms |
| ngrok / hosting provider | Backend server tunnel | ngrok.com/privacy |

---

## Data retention

- **Photos**: not retained — processed in memory and discarded immediately
- **Discogs token**: stored on your device until you disconnect your account in Settings
- **Quota logs**: reset daily, not permanently stored
- **Recent scans list**: stored locally on your device, cleared if you uninstall the app

---

## Your rights

You can delete all locally stored app data at any time by disconnecting your Discogs account in Settings or uninstalling the app. To request deletion of any server-side quota data associated with your Discogs user ID, contact me at jaysradiohour@gmail.com.

If you are a California resident, you have rights under the California Consumer Privacy Act (CCPA) including the right to know what personal information is collected and the right to request deletion. Given the minimal data collection described above, the primary personal data held is your Discogs user ID in the quota log, which I will delete upon request.

---

## Children

Shellac Snap is not directed at children under 13 and does not knowingly collect personal information from children.

---

## Changes to this policy

If this policy changes materially, I will update the date at the top of this document. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## Contact

For any privacy-related questions or requests:

**Email:** jaysradiohour@gmail.com
