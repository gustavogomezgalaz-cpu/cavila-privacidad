# Privacy Policy — Cavila

**Last updated: 2026-10-01**

Cavila is a puzzle app for children aged 6 and up. This policy explains what the app keeps on the phone, what usage and crash data it sends, what for and how long it is kept. Revision of October 1, 2026: the app started using Google Analytics for Firebase and Firebase Crashlytics, in child mode.

---

## The short version

There are no accounts and no sign-up, we do not ask for the child’s name or any contact details, there are no ads and there is no chat. The child’s progress and profiles are kept on the phone.

To know how many families install Cavila, which sister app or ad of ours brought them, which parts they use and what they buy, the app sends usage data to Google Analytics for Firebase, without names and without the phone’s advertising ID. And if the app closes because of an error, Firebase Crashlytics sends a technical report so we can fix it. Both are explained item by item under "Statistics and crashes".

The game works entirely in airplane mode: the challenges, the progress and the voice all come from the phone itself. Without a connection, usage data can wait and be sent later. Playing needs no network; paying for Premium, which Google Play charges for, does.

---

## What is stored on the phone

What the app stores lives in the phone’s own storage:

- Game progress (levels, stars, coins, streak, badges), so the child picks up where they left off.
- Each profile’s nickname and emoji, to tell apart siblings sharing a phone.
- The age range, which is optional, to adjust difficulty.
- Settings: sound, narration, language and reminder.
- A few dates and markers that only serve to decide what to show the adult: when the app was installed, when the 3-day Judgment Lighthouse trial started, which Premium offers were already shown and whether there is Premium access.

The nickname is written by the family and can be anything. We do not ask for a real name, surname, email, phone number, address, photo or date of birth: there is no account to create.

The Parents’ Area report —where the child is progressing and what is hardest for them— is calculated on the phone from that same progress. Analytics does not copy the nickname, the emoji, the age range or the progress: it only records the separate events listed under "Statistics and crashes", such as a level being finished and with how many stars, the app language and whether there is Premium.

Android’s automatic backup is switched off on purpose, so progress does not travel to your Google account.

---

## Statistics and crashes (Firebase)

Cavila uses Google Analytics for Firebase in child mode. It does not use the phone’s advertising ID (AdID) or the ANDROID_ID, it does not record screens on its own, and it does not allow ads to be personalized. Analytics works with an app instance ID: a random number created when the app is installed, which changes if you uninstall it.

What is sent:

- When the app is opened and how long it is used, and the first time it is opened.
- The phone model, its language and the Android and app versions.
- An approximate location (country or city), which Google infers from the IP address. There is no precise location and no location permission.
- If the installation came from a link of ours —another app in the family or an ad of ours—, the name of that link (such as "promo-matibu"). The app reads it from the Google Play "install referrer", keeps only that name and discards the rest, including the click identifier.
- The app language and whether it is on the free plan or which paid one.
- A closed list of usage events: that the welcome was finished or skipped; that a level was finished, from which island and with how many stars; that an island or the daily challenge was finished; that the 3-day Judgment Lighthouse trial opened or closed; that a free-plan limit was reached (profiles or the report); entering the Parents’ Area and going through the grown-up gate; the locks tapped and from which screen; the plans screen, the plan chosen and whether the purchase started, failed or was restored; that a Google Play review was requested; and which other family app was seen or tapped in the Parents’ Area.
- If an adult buys Premium: the plan, the price and the currency. No payment details.

If the app closes because of an error, Firebase Crashlytics sends a technical report: the error trace, the phone model, the Android and app versions and the time. No data about the child.

What never goes into this data: a profile’s nickname or emoji, the age or age range, the answers to the challenges, anything typed in the app, or the advertising ID. Each event has a closed list of allowed values, and anything not on that list is discarded before it is sent; an automated test of the code checks this in every version.

What for: to know how many families install the app and stay, which parts are used, which sister app or ad of ours brings families who buy, and to find and fix crashes. Measuring where installs come from is what Google Play calls "advertising or marketing"; the app shows no ads. We do not sell this data and it is not shared with third parties for advertising. Analytics data is deleted automatically after 2 months and crash reports after 90 days. Google handles it as the Firebase provider: firebase.google.com/support/privacy

---

## What the app does NOT do

- It has no ads, of any kind or from any network, and there are no advertising profiles and no cross-app tracking.
- There are no accounts, no sign-up and no log-in, and no servers of ours: usage data goes to Firebase, which belongs to Google.
- There is no chat, no content from other users, and no way for the child to write to anyone or receive messages.
- There are no purchases for the child: in-game coins are earned by solving challenges and cannot be bought with real money. Everything that is paid for sits behind the grown-up gate.
- It does not use artificial intelligence. There was an AI chat during development and it was removed before release; Gus’s dialogue is written by hand.
- It does not sell information to anyone.

---

## Payment

The app can be used without paying anything. Premium, which is optional, unlocks the rest of the content and is paid as a subscription, monthly or yearly, or with a one-time pass; in both cases Google Play charges it to your account: we never see or receive your card, your name or your address.

To know whether there is Premium access, the app asks Google Play whether there is an active subscription or a purchased pass. That check carries no data about the child or their progress, and if the phone is offline the game keeps working just the same. When an adult buys, analytics records the plan, the price and the currency (see "Statistics and crashes"), never card details.

The subscription is managed or cancelled from Google Play, not from here.

---

## Permissions the app asks for

- Fingerprint or face recognition (optional, can be turned off): it lets an adult open the Parents’ Area without tapping the numbers. The phone’s operating system verifies it; the app never sees or stores your fingerprint, it only receives a "yes" or a "no".
- Notifications (optional, off by default): a single daily reminder scheduled by the phone itself, without going through any server.

The app does not ask for microphone, camera, location, contacts or access to your files. The approximate location under "Statistics and crashes" does not come from any permission: Google infers it from the IP address.

---

## The notification library and the identifiers

The optional daily reminder uses Android’s notification component, which bundles a Google library —Firebase Cloud Messaging— that other apps use to receive messages sent from a server and which, in order to do so, registers a device identifier.

Cavila does not use that feature: there are no messages from any server, the app never requests that sending identifier, the library’s automatic start is switched off and the permission to receive that kind of message is blocked. The reminder is built entirely inside the phone and works in airplane mode.

What the app does use are two technical Firebase identifiers: the Analytics instance ID and the installation ID that Crashlytics uses to group crash reports. Both are random numbers created by the app, they are not tied to any name, they are not the advertising ID, and they are reset if you uninstall the app. That is why we declare "Device or other IDs" in Google Play’s data safety form.

---

## Reading aloud

The app can read texts aloud using the text-to-speech engine already installed on the phone. The only thing handed to that engine is the app’s own text —the challenges and the facts in Gus’s Nest—: never anything the child has written.

That engine is part of the operating system and is governed by the phone manufacturer’s privacy policy.

---

## Children

Cavila is made for children and follows the Google Play Families policies. We do not collect the child’s name, email, precise location or age: analytics measures how the app is used with a random installation number, without knowing who uses it, and their progress stays on the phone. There are no ads, no advertising profiles, no cross-app tracking, no content generated by other users, and no way for a child to contact a stranger inside the app.

The adult sections —the report, the settings, the plans and anything that is paid for— sit behind a gate that requires tapping the largest number or confirming with a fingerprint.

---

## How to delete the data

From the profiles screen you can delete a profile along with all of its progress. To delete everything on the phone, uninstall the app: the progress, the profiles and the settings have no copy anywhere else, so they are deleted completely. Uninstalling also resets the Firebase identifiers: if you install again, new ones start.

What was already sent to Firebase is not deleted by uninstalling, but it expires on its own: Analytics data after 2 months and crash reports after 90 days. If you want to ask for it to be deleted sooner, or have any question, write to contacto@gusmarstudios.com. Because that data carries no name, email or anything that says whose it is, we may have no way to find the data from one particular phone; that is why it expires on its own.

---

## Changes to this policy

If a future version changes any of this, this text and the date above are updated before that version reaches Google Play. The revision of October 1, 2026 added Google Analytics for Firebase and Firebase Crashlytics, which the app did not use before.

---

## Contact

For any privacy question, write to contacto@gusmarstudios.com.
