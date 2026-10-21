# Privacy Policy — Cavila

**Last updated: 2026-10-21**

Cavila is a puzzle app for children aged 6 and up. This policy explains what the app keeps on the phone, what usage and crash data it sends, what for and how long it is kept. Revision of October 21, 2026: it adds the plans for a set time with no automatic renewal, paying on one phone and opening on another with a code, the family gift and what is newly measured (see "Changes to this policy").

---

## The short version

There are no accounts and no sign-up, we do not ask for the child’s name or any contact details, there are no ads and there is no chat. The child’s progress and profiles are kept on the phone.

To know how many families install Cavila, which sister app or ad of ours brought them, which parts they use and what they buy, the app sends usage data to Google Analytics for Firebase, without names and without the phone’s advertising ID. And if the app closes because of an error, or a purchase with Google Play does not go through (because of an error, a timeout or a cancellation), Firebase Crashlytics sends a technical report so we can fix it. Both are explained item by item under "Statistics and crashes".

The game works entirely in airplane mode: the challenges, the progress and the voice all come from the phone itself. Without a connection, usage data can wait and be sent later. Playing needs no network; paying for Premium, which Google Play charges for, does. And if an adult pays on their phone to open the app on another device, the app uses a code and a server of ours, only for that (see "Pay on one phone, open on another").

---

## What is stored on the phone

What the app stores lives in the phone’s own storage:

- Game progress (levels, stars, coins, streak, badges), so the child picks up where they left off.
- Each profile’s nickname and emoji, to tell apart siblings sharing a phone.
- The age range, which is optional, to adjust difficulty.
- Settings: sound, narration, language and reminder.
- A few dates and markers that only serve to decide what to show the adult: when the app was installed, when the 3-day Judgment Lighthouse trial started, which Premium offers were already shown, whether there is Premium access and, with a plan for a set time, when it ends and on what day the app reminded you that it ends.
- The Google Play listing of the plans (the name, the prices and the purchase options), to be able to pay even when Google Play is slow to answer (see "Payment").
- If an adult used the code to pay on one phone and open on another: that code, until when it is valid and a random device number (see "Pay on one phone, open on another"). And whether a payment attempt did not finish and whether the "We improved payments" notice was already shown, so it is not repeated.

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
- If the installation came from a link of ours —another app in the family or an ad of ours—, the name of that link (such as "promo-matibu"). The app reads it from the Google Play "install referrer", keeps only that name and discards the rest, including the click identifier. Separately, Google Analytics reads that same data on its own the first time the app is opened, to know which campaign the installation came from.
- The app language and whether it is on the free plan or which paid one.
- A closed list of usage events: that the welcome was finished or skipped; that a level was finished, from which island and with how many stars; that an island or the daily challenge was finished; that the 3-day Judgment Lighthouse trial opened or closed; that a free-plan limit was reached (profiles or the report); entering the Parents’ Area and going through the grown-up gate, which deleting a profile, restoring a purchase and anything that leaves the app ask for (whether it was passed, whether the fingerprint answered or whether a wrong number was tapped; never the fingerprint or the number); the locks tapped and from which screen; the plans screen, the plan chosen, how it was closed and after how many seconds, and whether the purchase started, failed or was restored; that a Google Play review was requested; and which other family app was seen or tapped in the Parents’ Area.
- If an adult buys Premium: the plan, the price and the currency, whether the payment was confirmed later (for example, a cash payment) and whether it was paid at the family gift price. No payment details.
- If a purchase did not complete: the reason and the code Google Play gave (for example, that it was cancelled, that it timed out or that the payment was declined for insufficient funds), at which step of the purchase it happened, whether the phone had internet and, about the connection, whether it was Wi-Fi or mobile data, whether Android was restricting the app’s data (for example, with Data Saver) and whether the phone has Google services.
- When the plans load: whether Google Play prices could be loaded (and whether on asking again or from ones saved a while ago), whether the app was installed from Google Play or from another source, whether it runs on a Google test device (Firebase Test Lab), whether there was internet, how many attempts the app made and how many seconds it took, and the same about the connection: whether it was Wi-Fi or mobile data, whether Android was restricting the app’s data and whether the phone has Google services. Never the network’s name, the phone carrier or any address. This separates automated tests from real families and shows what happens when prices do not load.
- Whether the app could save on the phone the Google Play listing of the plans (to open the payment even when Google Play is slow to answer) and, if a payment was opened with it, how it ended and whether it was paid straight away with the one already saved. The listing comes from Google Play and carries nothing about the child or the card.
- About the code to pay on one phone and open on another: that the QR code was shown and from where, that it was opened on the other phone, that it was paid for, that a device was opened with it, that one was created to open another device, that its link was tapped to send it and, if something failed, the reason and at which step. Never the code.
- About the family gift: that the discount on the pass of our other apps was seen, that the gift link was opened or sent and for which of them, that a family code gave the discounted price, which app it came from and how it arrived, or why not. Never the code.
- That the "We improved payments" notice was seen and whether "See the plans" was tapped or it was closed.

If the app closes because of an error, Firebase Crashlytics sends a technical report: the error trace, the phone model, the Android and app versions and the time. No data about the child. Also, when a purchase or a check with Google Play fails because of a store error, Crashlytics receives a report even though the app does not close, with the code and message Google Play gave, the purchase step, the product and the plan; it carries nothing about the child either.

What never goes into this data: a profile’s nickname or emoji, the age or age range, the answers to the challenges, anything typed in the app, or the advertising ID. Each event has a closed list of allowed values, and anything not on that list is discarded before it is sent; an automated test of the code checks this in every version.

What for: to know how many families install the app and stay, which parts are used, which sister app or ad of ours brings families who buy, and to find and fix crashes. Measuring where installs come from is what Google Play calls "advertising or marketing"; the app shows no ads. We do not sell this data and it is not shared with third parties for advertising. Analytics data is deleted automatically after 2 months and crash reports after 90 days. Google handles it as the Firebase provider: firebase.google.com/support/privacy

---

## What the app does NOT do

- It has no ads, of any kind or from any network, and there are no advertising profiles and no cross-app tracking.
- There are no accounts, no sign-up and no log-in. Usage data goes to Firebase, which belongs to Google; our only server is the one for the code to pay on one phone and open on another, and the app only talks to it if an adult uses that code.
- There is no chat, no content from other users, and no way for the child to write to anyone or receive messages.
- There are no items for sale inside the game: coins are earned by solving challenges and cannot be bought with real money. The only thing that is paid for is Premium, and no payment happens without Google Play’s payment window, which shows the price and asks you to confirm.
- It does not use artificial intelligence. There was an AI chat during development and it was removed before release; Gus’s dialogue is written by hand.
- It does not sell information to anyone.

---

## Payment

The app can be used without paying anything. Premium, which is optional, unlocks the rest of the content and is paid for a set time —one month, three months or one year, with a single payment and no automatic renewal— or with a one-time pass; in every case Google Play charges it to your account: we never see or receive your card, your name or your address.

To know whether there is Premium access, the app asks Google Play whether there is an active subscription or a purchased pass. That check carries no data about the child or their progress, and if the phone is offline the game keeps working just the same. When an adult buys, analytics records the plan, the price and the currency (see "Statistics and crashes"), never card details.

So that paying does not fail when Google Play stumbles, the app saves on the phone the Google Play listing of the plans (the name, the prices and the purchase options; nothing about the child or you) and pays with it. While it does not have it, it asks Google Play for it again from time to time —after 15 minutes, after an hour, after 6 hours and then once a day—, only with internet and even with the app closed, using Android’s task scheduler; once it has it, it stops asking, and if there is already Premium access it does not ask. That request carries nothing about the child or their progress.

No surprise purchases: the plans screen opens without the grown-up gate, but nothing is charged without Google Play’s payment window, which shows the price and asks you to confirm. If your child uses the phone alone, in Google Play settings you can require your password or fingerprint for every purchase, or use Google Family Link.

A plan for a set time does not renew on its own: there is nothing to cancel. The app stores on the phone when it ends and, a few days before (fifteen for the one-year plan, three for the one-month and three-month plans), opens the plans screen to remind you and offer to extend it; if it is not extended, access closes on its own when it ends. Anyone who still has an older subscription that renews manages or cancels it from Google Play, not from here; and if they buy a plan for a set time, Google Play replaces the subscription with that plan, so there are never two charging. Restoring a purchase is still in the Parents’ Area, behind the grown-up gate.

---

## Pay on one phone, open on another

You can pay for the full version from your own phone: your child’s device shows a QR code, you open it on your phone, pay there with your Google Play account, and your child’s device unlocks by itself. The 8-letter code can also be typed by hand, and from the Parents’ Area, with “Open on another device”, one purchase opens the full version on up to 3 devices.

For this, and only when an adult uses the code, the app talks to an activation-code server of ours (gusmar-activacion), which runs on Google’s Cloud Functions and Firestore, as a provider. What that server keeps: the code; the product and the purchase receipt Google Play provides, which contains no name, email or payment details; a random device number the app creates, which is not the advertising ID, the ANDROID_ID or any other data from the phone; the date of each step (when the code was shown, opened, paid for and activated); and, to cap requests and stop abuse, a digest of the IP address of each request, deleted within a day at most (Google Cloud’s technical logs keep the IP address for up to 30 days). A device that only shows the code sends the code and that number; the one that paid also sends the Google Play receipt. On each device, the app remembers its code and its number to pick up where it left off, and a device opened with a code asks that server, at most once a day, whether it is still valid.

What for: to check with Google Play that the purchase is valid and still active (if it is refunded, it stops opening the full version), to open it on up to 3 devices and to prevent abuse. That number is an identifier used only to make the service work: it is not used for advertising, to build profiles or to contact anyone, and it is not shared or sold.

How long it is kept: a code nobody pays for is deleted after 2 days; one tied to a purchase, while the purchase stays active and up to 90 days after; and a device not seen for 60 days frees up its slot. If you want us to delete it sooner, write to contacto@gusmarstudios.com with the code.

The family gift: whoever has the lifetime pass of one of our apps buys the pass of the others at 70% off. For that, the same server gives that purchase a family code, tied to the Google Play receipt and without your name, your email or payment details, which the app shows in the Parents’ Area so you can send it to the others; the app that receives it (through the link, through Google Play when installing it, or typed by hand) checks it with the server using its device number, keeps it on the phone and checks it again once a day. Also, once a day the app asks the server whether the gift is switched on and in which apps, sending nothing but that number. The family code is kept while the pass stays active and up to 90 days after a refund.

---

## Permissions the app asks for

- Fingerprint or face recognition (optional, can be turned off): it lets an adult confirm what the grown-up gate asks for —deleting a profile, restoring a purchase, opening something outside the app— without tapping the numbers. The phone’s operating system verifies it; the app never sees or stores your fingerprint, it only receives a "yes" or a "no".
- Notifications (optional, off by default): a single daily reminder scheduled by the phone itself, without going through any server.

The app does not ask for microphone, camera, location, contacts or access to your files. The approximate location under "Statistics and crashes" does not come from any permission: Google infers it from the IP address.

To know whether there is internet —and tell the adult to connect, instead of showing a Google Play error, and ask for the prices again when it comes back—, the app checks the phone’s network status, with the normal Android permission that asks nothing at install time: whether there is a connection, whether it is Wi-Fi or mobile data and whether Android is restricting the app’s data. It does not read which network you are on or where you are. And to know whether the phone has Google services and the Play Store (some, like Amazon Fire tablets, do not, and there Google Play cannot charge), the app asks the system only about those two apps, without seeing which other apps you have.

---

## The notification library and the identifiers

The optional daily reminder uses Android’s notification component, which bundles a Google library —Firebase Cloud Messaging— that other apps use to receive messages sent from a server and which, in order to do so, registers a device identifier.

Cavila does not use that feature: there are no messages from any server, the app never requests that sending identifier, the library’s automatic start is switched off and the permission to receive that kind of message is blocked. The reminder is built entirely inside the phone and works in airplane mode.

What the app does use are two technical Firebase identifiers: the Analytics instance ID and the installation ID that Crashlytics uses to group crash reports. Both are random numbers created by the app, they are not tied to any name, they are not the advertising ID, and they are reset if you uninstall the app. That is why we declare "Device or other IDs" in Google Play’s data safety form.

The app also uses the Google Play library for in-app updates: when it opens, it asks Google Play, on the phone itself, whether there is a new version, and if it is an important one it opens Google Play’s screen to install it, at most once a day. Google Play answers that check with the available version; it carries nothing about the child or their progress, and the app only stores on the phone the day it asked.

---

## Reading aloud

The app can read texts aloud using the text-to-speech engine already installed on the phone. The only thing handed to that engine is the app’s own text —the challenges and the facts in Gus’s Nest—: never anything the child has written.

That engine is part of the operating system and is governed by the phone manufacturer’s privacy policy.

---

## Children

Cavila is made for children and follows the Google Play Families policies. We do not collect the child’s name, email, precise location or age: analytics measures how the app is used with a random installation number, without knowing who uses it, and their progress stays on the phone. There are no ads, no advertising profiles, no cross-app tracking, no content generated by other users, and no way for a child to contact a stranger inside the app.

The Parents’ Area opens without a gate: seeing the report and changing the settings is nothing delicate. What cannot be undone or leaves the app —deleting a profile, restoring a purchase, emailing us, opening another of our apps in Google Play, sending the link that opens the app on another device, or opening and sending the family gift link— asks for a gate that requires tapping the largest number or confirming with a fingerprint. The plans screen has no such gate, but no payment happens without Google Play’s window (see "Payment").

---

## How to delete the data

From the profiles screen you can delete a profile along with all of its progress. To delete everything on the phone, uninstall the app: the progress, the profiles and the settings have no copy anywhere else, so they are deleted completely. Uninstalling also resets the Firebase identifiers: if you install again, new ones start. If the code to pay on one phone and open on another was used, what our server keeps is deleted on its own within the periods in that section, or sooner if you write to us with the code.

What was already sent to Firebase is not deleted by uninstalling, but it expires on its own: Analytics data after 2 months and crash reports after 90 days. If you want to ask for it to be deleted sooner, or have any question, write to contacto@gusmarstudios.com. Because that data carries no name, email or anything that says whose it is, we may have no way to find the data from one particular phone; that is why it expires on its own.

---

## Changes to this policy

If a future version changes any of this, this text and the date above are updated before that version reaches Google Play. The revision of October 1, 2026 added Google Analytics for Firebase and Firebase Crashlytics, which the app did not use before. The one of October 15, 2026 added that paying no longer goes through the grown-up gate, the reason for a purchase that does not complete, the loading of Google Play prices along with the installation source and the test device, the store errors sent to Crashlytics, and that Google Analytics reads the installation link on its own. What is collected is the same: it is just better explained. The revision of October 21, 2026 added the plans for a set time with no automatic renewal (with the reminder before they end and what the app stores to give it); in-app updates with the Google Play library; paying on one phone and opening on another with a code, and the family server that makes it possible; the family gift; that the Parents’ Area is entered without a gate (deleting, restoring and anything that leaves the app ask for it); that the Google Play listing of the plans is saved on the phone and, while it is missing, requested in the background with the app closed; and, in the measurements, the network type (Wi-Fi or mobile data, and whether Android was restricting the app’s data), whether the phone has Google services, how long the prices took to load and the new events for the QR code and the "We improved payments" notice.

---

## Contact

For any privacy question, write to contacto@gusmarstudios.com.
