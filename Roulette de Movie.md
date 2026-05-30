# Privacy Policy — Roul

**Last updated:** May 30, 2026

This Privacy Policy describes how Roulette de Movie ("we", "our", or "the app") handles your information. We believe privacy is a right, so this policy is intentionally simple: we do not collect, share, or sell your personal data.

---

## 1. Overview

Roulette de Movie is a movie-picker app that lets you build a personal watchlist and spin a wheel to choose what to watch next. All data you create in the app stays on your device. We do not operate any servers, create any user accounts, or store any information about you remotely.

---

## 2. Information We Do Not Collect

We do not collect:

- Your name, email address, or any account credentials
- Location or GPS data
- Device identifiers (IDFA, IDFV, device name)
- Contacts, calendar, or health data
- Camera or microphone input
- Clipboard contents
- Crash reports or diagnostic data sent to us
- Usage analytics or behavioral data

The app requests **no device permissions** — it does not ask to access your camera, photos, location, contacts, microphone, Bluetooth, or any other sensitive capability.

---

## 3. Information Stored on Your Device

The following data is created when you use the app and is stored **only on your device**, never transmitted to us:

| Data | What it is | Where it's stored |
|------|------------|-------------------|
| Movie collection | Titles, release years, and watched/unwatched status for movies you add | On-device (CoreData) |
| Movie poster images | Cached artwork for movies in your collection | On-device (CoreData) |
| Date added | The date you added each movie to your collection | On-device (CoreData) |
| Onboarding status | Whether you have completed the introductory screen | On-device (UserDefaults) |

This data never leaves your device except as described in Section 4 below. You can delete all of it at any time from within the app, or by uninstalling Roulette de Movie.

---

## 4. Network Requests — Movie Search

When you search for a movie, the text you type is sent as a search query to a third-party movie metadata service in order to return matching results. This is the only outbound network request the app makes.

**Service used:** IMDB movie search API  
**What is sent:** Your search query text  
**What is received:** Movie titles, release years, and poster image URLs  
**Purpose:** To find and display matching movies so you can add them to your collection

Poster images are subsequently fetched over the network from the URLs returned by this service and cached locally on your device.

We do not control the third-party service and cannot guarantee its privacy practices. No personal information (name, device ID, account data, etc.) is included in these requests — only the text you type in the search field.

---

## 5. Third-Party Services

Roulette de Movie uses no third-party analytics, advertising, or crash-reporting SDKs. The app is built entirely on Apple's native frameworks (UIKit, CoreData, CoreHaptics, Metal). There are no CocoaPods, SPM packages, or external libraries integrated.

The only third-party interaction is the movie search API described in Section 4.

---

## 6. Children's Privacy

Roulette de Movie does not knowingly collect any information from children under the age of 13 (or the applicable age of digital consent in your jurisdiction). The app collects no personal data from anyone, making it safe for all ages.

---

## 7. Data Security

Because all your data is stored on your device, its security is governed by your device's built-in protections — screen lock, Face ID / Touch ID, and iOS data encryption. We recommend keeping your device and iOS up to date.

---

## 8. Your Rights

Since we store no data about you on any server, there is nothing for us to access, export, or delete on your behalf. To remove all data associated with the app:

- **Delete your movie collection**: Use the delete option within the Movie Collection screen to remove individual movies or clear your entire collection.
- **Remove all app data**: Uninstall Roulette de Movie from your device. This permanently removes all CoreData and UserDefaults entries associated with the app.

---

## 9. Changes to This Policy

If this policy changes materially, we will update the "Last updated" date at the top of this document and, where appropriate, notify users through an app update. Continued use of Roulette de Movie after a policy change constitutes acceptance of the updated terms.

---

## 10. Contact

If you have questions about this Privacy Policy, please contact:

**Vahid Ghanbarpour**  
vahidgr@yahoo.com

---

*Roulette de Movie is an independent app. The movie data and poster images displayed in search results are provided by a third-party API and sourced from publicly available movie databases.*
