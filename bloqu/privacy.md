---
title: Bloqu Privacy Policy
permalink: /bloqu/privacy/
---
# Bloqu Privacy Policy

**Effective date:** 6 November 2026

Türkçe sürüm: [Gizlilik Politikası (Türkçe)](/bloqu/privacy-tr/)

This policy explains what information the mobile game **Bloqu** (iOS and Android) handles, why, who it is shared with, and the choices you have. Bloqu is made by an individual developer, Alipaşa Karataş ("the developer of Bloqu", "we", "us").

Contact for any privacy question or request: **support@alpateknoloji.com**

## 1. Summary

- Bloqu has **no account and no sign-in**. We do not ask for your name, email address, phone number, contacts, photos or precise location. For the Endless leaderboards the game creates an **anonymous player ID** for your device (no personal details), and shows your Endless scores with a **nickname** (a random one such as "Player1234" unless you choose your own).
- Your game progress is stored **only on your device**.
- The game is free and funded by **ads (Google AdMob)** and optional **in-app purchases**. Ads use device identifiers; personalised ads are shown only where you have allowed them.
- We use **Google Firebase** to understand how the game is played and to fix crashes.
- We do not sell your personal information for money.

## 2. Information stored on your device

Bloqu keeps a save file in the app's private storage on your device. It contains:

- game progress (scores, Adventure levels, coins, missions, daily streak, unlocked themes, tutorial status);
- settings (sound, music, vibration, language);
- ad pacing counters (for example when the last ad was shown, so ads are not shown too often);
- what you have bought (Remove Ads; earlier purchases of themes or the Starter Pack, which are no longer on sale) and the store's **transaction IDs** for those purchases, so a purchase is never delivered twice.

This file is not sent to us. It may be included in your device's own backup (iCloud or Google backup) depending on your device settings. Deleting the app deletes the file.

## 3. Advertising (Google AdMob)

Bloqu shows banner, interstitial and rewarded video ads through **Google AdMob**, provided by Google LLC / Google Ireland Limited. If you buy "Remove Ads", banner and interstitial ads stop; rewarded ads you choose to watch remain available.

When ads are requested, the Google Mobile Ads SDK collects and processes, on Google's behalf:

- the device's **advertising identifier** (IDFA on iOS, only if you allow tracking; Android Advertising ID on Android);
- your **IP address** (also used to estimate your approximate location, such as country or city);
- **device and app information** (device model, operating system and version, language, app version);
- **ad interaction data** (ads shown, taps, rewarded completions);
- **diagnostic data** about the ads SDK (crashes and performance).

Google uses this information to deliver, measure and limit the frequency of ads, prevent fraud, and, **only where you have consented**, to personalise ads.

**Your choices:**

- **EEA, UK and Switzerland:** on first launch Bloqu shows Google's consent message (Google User Messaging Platform, an IAB TCF certified consent tool). You can accept, refuse or choose purposes and partners. You can change your choice at any time from **Settings > Privacy choices** in the game. If you refuse, you may see non-personalised (contextual) ads or no ads.
- **iOS:** Bloqu asks for your permission through Apple's App Tracking Transparency prompt before the IDFA can be used. If you choose "Ask App Not to Track", ads are not personalised with the IDFA. You can change this in iOS **Settings > Privacy & Security > Tracking**.
- **Android:** you can reset or delete your advertising ID, or opt out of ads personalisation, in your device's **Settings > Google > Ads** (or **Settings > Privacy > Ads**).

More information:

- How Google uses information from apps that use its services: https://policies.google.com/technologies/partner-sites
- Google Privacy Policy: https://policies.google.com/privacy
- Ad technology providers that may work with AdMob: https://support.google.com/admob/answer/9012903

## 4. In-app purchases

The only item on sale is Remove Ads; themes are unlocked with coins earned by playing.

Purchases are processed by **Apple (App Store)** or **Google (Google Play)** under their own terms and privacy policies. We never receive your payment card details, name or billing address. The store tells the game which product was bought and gives it a transaction ID, which the game verifies and keeps on your device (see section 2). The game also reports the purchase event (product and result, without any payment details) to Firebase Analytics (section 5).

- Apple Privacy Policy: https://www.apple.com/legal/privacy/
- Google Privacy Policy: https://policies.google.com/privacy

## 5. Analytics, crash reports and remote settings (Google Firebase)

Bloqu uses **Google Analytics for Firebase**, **Firebase Crashlytics** and **Firebase Remote Config**, provided by Google.

- **Analytics** receives game events such as: session start, game start and end (mode, score, number of moves, duration), Adventure level start/complete/fail, missions, daily streak, power-ups used, themes unlocked, shop opened, tutorial steps, ads shown/rewarded/failed and the estimated ad revenue, and purchase events. Together with these it receives an app instance ID generated by Firebase, device and app information (model, operating system, language, app version), and your IP address (used to estimate your approximate location). We use this to understand which parts of the game work, balance difficulty and economy, and measure retention.
- **Crashlytics** receives crash reports: stack traces, device state (model, OS, free memory and disk space, orientation), the game's recent technical log lines (no personal data) and a Crashlytics installation ID. We use this only to find and fix bugs.
- **Remote Config** lets us adjust game balance values (rewards, ad intervals, difficulty) without an update. It uses a Firebase installation ID.

None of these is linked to your name or an account, and we do not use them to track you across other companies' apps or websites.

- Firebase privacy and security: https://firebase.google.com/support/privacy

## 5a. Leaderboards (Firebase Authentication, Cloud Firestore, Cloud Functions, App Check)

When the Endless leaderboards are available, Bloqu uses **Firebase Authentication** (anonymous sign-in), **Cloud Firestore**, **Cloud Functions** and **Firebase App Check**, provided by Google (servers in the EU, region europe-west1).

- **Anonymous player ID:** the first time the game talks to the leaderboard it signs in anonymously. Firebase creates a random user ID for this installation; it is not linked to your name, email, phone number or store account. It is kept on your device so your rows stay yours.
- **Nickname:** you get a random nickname (for example "Player1234" / "Oyuncu1234"); you can change it in Rankings. Nicknames are **public**: every player can see them next to scores. Please do not use your real name or anything personal. Nicknames are checked against a list of offensive words.
- **Scores:** at the end of each Endless game the game sends your final score with the number of moves, lines cleared, play time, a random game ID and the app version, so the server can check that the score is plausible and count each game once. Your best all-time score and your best score of each week (with your nickname and the time it was achieved) are stored and shown to all players on the leaderboards. Weekly boards are kept as history. Scores that could not be sent (no connection) wait on your device and are sent later.
- **App Check** sends an attestation from Apple (App Attest) or Google (Play Integrity) that the request comes from the genuine app; it contains no personal data.
- **Rules:** the first time you open Rankings you are asked to accept its rules (be respectful; offensive nicknames are removed and players can be banned). Only the fact that you accepted is stored, on your device.
- **Reports:** you can report another player from the "more" button on their Rankings row (reason: offensive nickname, cheating score or something else). The report stores your anonymous player ID, the reported player's anonymous player ID, the board, the reason, a copy of the reported nickname at that moment and the time. Reports are only readable by the developer, never by other players, and the reported player is not told who reported them.
- **Blocked players:** you can block a player from the same menu, and unblock them in **Settings > Blocked players**. The list of blocked players (their anonymous player IDs and a copy of each nickname at the time of blocking, at most 200) is stored on your device and in your player record on the server (`players/{your ID}`), so it comes back if you reinstall while the same anonymous account exists. Blocked players' scores are hidden only on your device; they are not told.
- **Moderation:** when several different players report the same nickname as offensive, it is reset to a default nickname and locked for a few days; when several report a score as cheating, that score is hidden from the boards until reviewed. The developer reviews reports within 24 hours and can remove nicknames or scores and ban an anonymous player ID from the leaderboards. A ban is stored with its reason and date. A daily summary of new reports is sent to the support mailbox.
- Server logs (for example the time, the player ID and whether a score was accepted) are kept for security and abuse prevention.

The leaderboard data is not used for advertising or tracking. To have your leaderboard rows and nickname deleted, contact us at support@alpateknoloji.com with your nickname; deleting the app stops further submissions but does not remove rows already on the boards.

## 6. Game engine

Bloqu is built with the Unity engine (Unity Technologies). Unity's cloud analytics, cloud diagnostics and ads services are turned off in Bloqu. The Unity runtime may still send limited, non-personal hardware information (such as device model and OS version) to Unity. See https://unity.com/legal/game-player-and-app-user-privacy-policy

## 7. Why we process data (legal bases, for users in the EEA, UK and Turkey)

| Purpose | Legal basis |
| --- | --- |
| Storing your progress and purchases on your device | Necessary to provide the game you asked for |
| Personalised ads (AdMob), use of the IDFA | Your consent (Google consent message / Apple tracking prompt), which you can withdraw at any time |
| Non-personalised ads, frequency capping, fraud prevention | Our legitimate interest in funding a free game; where the law requires consent, we ask for it in the consent message |
| Analytics, crash reports and remote settings (Firebase) | Our legitimate interest in keeping the game stable and improving it; where the law requires consent, we ask for it |
| Verifying purchases | Necessary to perform the purchase contract |
| Leaderboards (anonymous player ID, nickname, scores, App Check) | Necessary to provide the leaderboard feature you use; our legitimate interest in fair rankings and preventing abuse |
| Reports, blocked players, moderation and bans | Necessary to provide the report and block features you use; our legitimate interest in keeping the leaderboards safe and complying with app store rules |

## 8. Retention and deletion

- **On your device:** kept until you delete the app (or clear its data on Android). Deleting the app deletes everything Bloqu stored locally, including progress and coins; purchases of Remove Ads (and earlier theme purchases) can be restored from the store with **Settings > Restore purchases**.
- **Google AdMob:** retained by Google as described in Google's policies above.
- **Leaderboards:** the anonymous player ID, nickname and best scores are kept while the leaderboards exist, or until you ask us to delete them; per-game submission records (used to reject duplicates) are kept for as long as needed to prevent abuse. Your blocked players list is kept on the server while your anonymous account exists (and on your device until you delete the app); unblocking a player removes them from it. Reports, bans and daily moderation summaries are kept as the moderation record for as long as the leaderboards exist, so repeated abuse can be recognised; ask us at support@alpateknoloji.com if you want reports you made removed.
- **Firebase Analytics:** user-level event data is kept for the retention period set in our Google Analytics settings (2 months by default, at most 14 months), then deleted. **Crashlytics:** crash reports are kept for up to 90 days.

Because Bloqu has no accounts, we cannot find your data by your name or email. If you want us to delete analytics data, contact us at support@alpateknoloji.com; we will explain how to find the app's identifier so we can locate it. You can also reset your advertising ID at any time (section 3).

## 9. Sharing

We share data only with the service providers named above (Google for ads and Firebase; Apple and Google for purchases), who process it for the purposes described. We do not sell your personal information for money and we do not share it with data brokers. We may disclose information if required by law.

Google may process data outside your country, including in the United States. Google relies on recognised safeguards for these transfers, such as the EU Standard Contractual Clauses and the EU-U.S. Data Privacy Framework.

## 10. Your rights

Depending on where you live, you have rights over your personal data:

- **EEA / UK (GDPR, UK GDPR):** access, rectification, erasure, restriction of processing, data portability, objection to processing based on legitimate interests, and withdrawal of consent at any time (without affecting earlier processing). You may also complain to your local data protection authority.
- **Turkey (KVKK, Law No. 6698):** the rights listed in Article 11, including learning whether your data is processed, requesting information, learning the purpose, knowing the third parties it is transferred to, correction, deletion, objection and compensation. See the Turkish version of this policy for details.
- **California (CCPA/CPRA) and other U.S. states:** the right to know, delete and correct personal information, and to opt out of the "sale" or "sharing" of personal information for cross-context behavioural advertising. AdMob's use of advertising identifiers may count as "sharing"; you can opt out by refusing tracking on iOS or deleting/resetting your advertising ID or opting out of ads personalisation on Android (section 3). We will not treat you differently for using these rights.

To use any right, email **support@alpateknoloji.com**. We will answer within 30 days. Since we do not hold an account for you, we may ask for information needed to locate your data (such as the app instance ID).

## 11. Children

Bloqu is a general-audience game and is **not directed at children under 13** (or the higher minimum age that applies in your country). We do not knowingly collect personal data from children, and ad requests are not marked as directed at children. If you believe a child has provided personal data through Bloqu, contact us and we will delete what we can.

## 12. Security

Your save file stays in the app's private storage. Data sent to Google is transmitted over encrypted connections (HTTPS). No method of storage or transmission is completely secure, but we use the protections offered by the operating system and our providers.

## 13. Changes to this policy

We may update this policy, for example when the game adds a feature or a service provider. The new version will be posted at this address with a new effective date. If a change materially affects how your data is used, we will also tell you in the game.

## 14. Contact

Alipaşa Karataş, developer of Bloqu
Email: **support@alpateknoloji.com**
