---
layout: rasikh
title: Privacy Notice
eyebrow: Privacy
description: What happens to your information in Rasikh. Your location and your record of practice never leave your device.
effective: 21 August 2026
updated: 9 October 2026
permalink: /rasikh-privacy.html
---

Rasikh is made by TJB Ventures FZE, a company registered in Ajman Free Zone, United Arab Emirates ("we", "us"). This notice explains what information the Rasikh iOS app handles, what stays on your phone, what reaches us or a company working for us, and what you can do about it. It covers the app only, not our websites.

> **The short version.** Your location, your prayer times and your record of practice stay on your phone. We never receive them, and neither does any company we work with. The app requires an account, which holds your email address and little else. It sends a fixed list of usage events to an analytics service: which screens you open and for how long, and which features you use. In some countries it asks first; everywhere you can switch it off. It uses an attribution service to learn which advertisement or link brought you to the app. If you send us feedback, we keep your message with your account. If you buy Rasikh Plus, Apple takes the payment and our subscription provider receives the purchase record. Each of these is described below, with the name of the company involved.

---

## 1. Overview

- Your location, prayer times, record of practice, tasbīḥ counts and widget data stay on your phone. Nobody receives them. (Section 2)
- Your account holds your email address, a random account identifier, the date it was created, and your name if Apple supplied one. Supabase stores it in India. (Section 3)
- A fixed list of usage events goes to PostHog in the European Union, with your account identifier attached when you are signed in. In the European Economic Area, the United Kingdom, Saudi Arabia and Turkey the app asks you first. You can switch it off. (Section 4)
- AppsFlyer, in the United States, learns that the app was installed or opened and which link or advertisement led to it. Your advertising identifier is included only if you allow tracking when iOS asks. If you do not, AppsFlyer still passes the install or open to Meta and TikTok, with your IDFV and IP address, marked as not opted in to tracking. (Section 5)
- Rasikh Plus is optional. Apple takes the payment. RevenueCat, in the United States, holds your account identifier and, if you buy Plus, the purchase record Apple sends it. (Section 6)
- Kit, in the United States, holds your email address only if you subscribe to email updates. (Section 7)
- If you send feedback from the app, Supabase stores your message with your account, in India. (Section 8)

| Information | Where it is processed | Why | Legal basis | Kept for |
| --- | --- | --- | --- | --- |
| Your location, prayer times, record of practice, tasbīḥ counts and widget data | On your phone only. Never sent to us or to anyone else | To show prayer times, schedule alerts, point to the qibla and keep the record you asked the app to keep | Not received by us. Stored on your phone because you asked for a feature that needs it | Until you delete it or remove the app |
| Your email address, your name if Apple gives us one, and an account identifier | Supabase, our sign-in provider (India) | So you can sign in, and so a future version can restore your settings on a new phone | Providing the service you asked for (GDPR Article 6(1)(b)), and your explicit consent when you create the account (Article 9(2)(a)) | Until you delete the account |
| A fixed list of usage events (which screens you opened and for how long, which features you used, the steps of setup and of the Plus screen) with your account identifier attached when you are signed in | PostHog, our analytics provider (European Union) | To see which parts of the app are used and where people get stuck | Your consent (Articles 6(1)(a) and 9(2)(a)) | 12 months |
| That the app was installed or opened, the device identifier iOS gives our app (the IDFV), and, only if you allow it when asked, your advertising identifier (the IDFA). Without it, your IP address and IDFV still go on to Meta and TikTok, marked as not opted in to tracking | AppsFlyer, our attribution provider (United States), which passes install and open events to Meta and TikTok | To learn which advertisement or link brought you to the app, and to open the right screen when you follow a link | Your consent (Article 6(1)(a)) | Up to 12 months |
| Your account identifier and, if you buy Rasikh Plus, the purchase record from Apple: the product, its price and currency, the dates, the subscription status and Apple's transaction identifiers | RevenueCat, our subscription provider (United States) | To unlock Plus, and to count purchases in aggregate, such as how many free trials become subscriptions. Never for advertising | Providing what you bought (Article 6(1)(b)), and your explicit consent when you created the account (Article 9(2)(a)) | As long as the record exists at RevenueCat. Deleting your account does not remove it; write to us and we will (section 11) |
| Your email address, if you subscribe to email updates | Kit, our mailing provider (United States) | To send you occasional updates about the app | Your consent | While you are subscribed |
| Feedback you send from the app: your message, your answers, and whether we may reply, with your account identifier | Supabase, our sign-in provider (India) | To read what you tell us and improve the app, and to reply if you asked us to | Your consent, given by sending it (Articles 6(1)(a) and 9(2)(a)) | 24 months, or until you delete your account |

We make no automated decisions about you and we do not profile you. Streaks and statistics shown in the app are calculated on your phone, from what you entered, for you alone.

## 2. What stays on your phone

**Your location.** Rasikh asks for location permission so it can calculate prayer times where you are. It asks for "While Using the App" access only, never "Always". It takes a fresh reading each time you open the app. If you choose your city by hand instead, it takes no readings at all. Coordinates are rounded to about 110 metres before they are stored. They are used only by calculations running on your phone and are never sent to us or to any provider. The only location-related value the app can record anywhere is a two-letter country code, recorded once if you choose a city by hand. You can withdraw the permission at any time in iOS Settings under Privacy & Security, then Location Services, then Rasikh.

**Prayer times.** Calculated on your phone from your coordinates and the calculation method you choose. The calculation, the calendar and the method tables are all inside the app. Nothing is fetched from a server, which is why Rasikh works without a signal.

**Your record of practice.** If you use the tracker to record which prayers you prayed, that record is information about your religious practice. It is stored on your phone at the strongest protection level iOS offers: it cannot be read while your phone is locked, and it is excluded from device backups. It is not uploaded to your account, not synced, and not backed up to any server. Creating an account does not change this. Analytics learn nothing about it: not that you logged a prayer, not which prayer, not when, not how many.

**Export and delete.** The Tracker screen has an Export control that writes a copy of your record to a file and hands it to the iOS share sheet. That copy is then an ordinary file under your control; we cannot see or delete it. The Delete control on the Tracker's data screen removes the record from the app. Because the storage is excluded from backups, there is no backup copy to restore.

**Notifications and the adhan.** Prayer-time alerts are scheduled by iOS on your phone from times your phone calculated. No server is involved. The adhan recording is inside the app and is played from there. Tapping "Log this prayer" on an alert writes to the record described above, on your phone. The morning and evening adhkār reminders, if they are on, are scheduled by iOS on your phone in the same way. The times you choose for them stay on your phone.

**The widget.** To draw a home screen or Lock Screen widget, the app writes the prayer times for today and tomorrow, their time zone, your language and region setting, and the time of writing into a storage area shared between the app and its widget. It contains no coordinate, no calculation method and nothing you logged. It is written whenever the app calculates prayer times, whether or not you have added a widget. It stays on your phone and is removed with the app. It is not held at the strongest protection level, because a Lock Screen widget has to draw while the phone is locked.

## 3. Your account

Rasikh requires an account. After you have chosen your location, calculation method and alerts, the app asks you to sign in and does not continue until you have. Once you are signed in, the app works offline exactly as before.

**How you sign in.** With an email address and a password, or with Sign in with Apple. If you use Sign in with Apple and choose to hide your email address, Apple gives us a relay address and we never see your real one.

**What the account holds.** Supabase, our sign-in provider, stores your login: your email address, your password in hashed form (we cannot read it), and the link to your Apple ID if you used one. Alongside it we keep one record with four fields: a random account identifier, your email address, the date the account was created, and your name if Apple supplied one when you first signed in. Signing up with an email address gives us no name. Feedback you send is kept with the account (section 8). There is no table for prayers, tasbīḥ counts, locations, settings or reading history.

**Who can read it.** The database enforces that a signed-in person can read and change only their own record. The key inside the app cannot reach anyone else's.

**Where it is stored.** Supabase hosts our project in Mumbai, India. Section 10 describes the safeguards for that transfer.

**What Supabase also sees.** Your phone's IP address when you sign in or your session is refreshed, as any server does.

**What the account is for.** So that a future version can restore your settings on a new phone, and so that Rasikh Plus, if you buy it, is attached to your account. Beyond that, in this version it does little more than let you sign in and send us feedback.

**Deleting it.** Open Settings, then Account, then Delete account. The login, the account record and any feedback you sent are deleted together, immediately. Section 11 has the details.

## 4. Usage analytics

Rasikh sends a fixed list of usage events to PostHog, our analytics provider, hosted in the European Union. We are one person building this app, and without these events the choice of what to fix next is a guess.

**The complete list.** The app cannot send anything that is not on it.

- a screen was opened, and which one, from a fixed set of screen names. This includes the adhkār, tasbīḥ, qibla and adhan screens, but never which dhikr or text you read. The time between one screen and the next is how long you spent there;
- the app was opened for the first time, and setup finished;
- a setup screen came into view, and which one, from a fixed set of names; and, once, how setup ended: whether you allowed location or chose a city, whether you allowed notifications, and whether the ringer step was shown;
- you agreed to share usage data;
- the sign-in screen came into view, and which sign-in method you tapped; you signed in, and by which method; you signed out;
- what you answered when iOS asked about notifications, and whether that permission later changed;
- what you answered when iOS asked about tracking;
- you chose a city by hand, recorded as a two-letter country code;
- a qibla visit ended: whether the direction was found, whether calibration was suggested, roughly how long it took to line up (in bands such as "under 5 seconds"), and which button opened it. Never a direction, a bearing or a coordinate;
- a setting that changes prayer times was changed: which setting (method, Asr, high latitude, an adjustment, or whether the place comes from your location or a city you chose), never its new value;
- an alert setting was changed: which one, and whether it was turned on or off, changed, or which bundled adhan sound was chosen. A time you choose for a reminder is never sent;
- your daily reminders were set at setup; the one-time offer to turn them on was shown, used or hidden; a reminder paused itself; and you opened a reminder or a notification about Jumuʿah, the end of a free trial or the alert safety check. Never an adhan or a prayer reminder;
- a Rasikh Plus feature was used: a widget added or removed (by widget type), a theme chosen, a countdown started or ended, a control used, the year review exported;
- the Rasikh Plus screen opened, and which locked feature led to it; which plan you selected; that you tapped the button to start a trial or buy, and whether a trial was offered; that you tapped Restore; how you left the screen without buying and roughly how long you looked (in bands); a page of the Plus preview came into view;
- a Plus purchase finished: which plan, and whether it was purchased, cancelled, pending or failed. No price and no amount;
- the first-week card: which item was shown, tapped or done, and whether you hid the card;
- you sent feedback: from where, your answer to the Plus question, and whether you wrote a message. Never the message itself;
- we asked iOS whether to show its rating window, and at which moment. Apple decides whether it appears, and never tells us whether or how you rated.

**What is attached to each event.** The kind of device, the iOS version, the app version and your language setting, added by PostHog's software, and whether the app came from the App Store, TestFlight or a developer build. PostHog also records when the app was installed, opened, sent to the background or updated. If you are signed in, your account identifier is attached so that your sessions are recognised as one person's, together with a few settings: your country setting, your calculation method, your notification mode, whether notifications are allowed, your Rasikh Plus status, which Rasikh widget types are installed, whether the daily reminders are on, whether your country is one where the app asks first, and whether the account belongs to our own team (worked out on your phone from the email address, which is never sent). If you are not signed in, PostHog assigns a random identifier. We have told PostHog not to derive a location from your IP address.

**Crash reports.** If the app fails, PostHog receives a technical description of the failure: where in the code it happened and what kind of failure it was. It contains nothing you entered or logged. Crash reports are attached to the same identifier as the events above.

**Session replay.** This version of Rasikh does not record session replays.

**Never sent.** Your coordinates. Your city name. Whether you logged a prayer, which prayers you logged, when, or in what state. Your tasbīḥ counts. Which dhikr or religious text you read. Fasting. The text of any feedback. A time you chose for a reminder. The value of any adjustment. Your email address. Your name. Any advertising identifier.

**What it still reveals.** That a person, identified by an account, uses a Muslim daily-practice app, which of its screens and features they use, and roughly how often and when. Under UK, EU, Saudi and Turkish law that is information about religious belief. That is why our legal basis is your consent, and why you can withdraw it at any time without losing any feature.

**On or off.** If your App Store country is in the European Economic Area, the United Kingdom, Guernsey, Jersey, the Isle of Man, Gibraltar, Saudi Arabia or Turkey, Rasikh asks you once, at the start of setup, whether to share usage data. Until the App Store has told the app your country, your phone's region setting decides. Nothing is sent, and nothing is stored on your phone for analytics, until you say yes, and saying no is one tap with no effect on any feature. If you used Rasikh in one of these countries before this version and were never asked, you are asked once, and nothing is sent until you answer. Everywhere else analytics are on from the first launch until you turn them off; the first setup screen says so. Either way the switch is in Settings, under Privacy: "Share usage analytics". Turning it off stops new events immediately. To have past events deleted, see section 11.

**Kept for.** 12 months, then deleted.

## 5. Links and attribution

Rasikh uses AppsFlyer for two things: opening the right screen when you follow a link to the app, and telling us which advertisement or link an install came from.

**What AppsFlyer receives.** That the app was installed or opened. The identifier iOS gives an app for the device it is on, called the identifier for vendor (IDFV); it is specific to our app and is reset when you delete the app. Your IP address, the kind of device and the iOS version. The parameters carried by a link you followed. Your account identifier, if you are signed in. And, only if you allowed tracking when asked, your advertising identifier (IDFA).

**The tracking question.** After you finish setting up the app and sign in, a screen explains what the answer is for, and then iOS asks whether to allow the app to track you across apps and websites. If you allow it, AppsFlyer reads your advertising identifier and uses it to tell us which advertisement or link brought you to Rasikh. If you refuse or never answer, no advertising identifier is read. AppsFlyer still sends Meta and TikTok that the app was installed or opened, together with your device's IDFV and your IP address (which gives an approximate location), marked as not opted in to tracking. Meta and TikTok use these only in aggregate to measure our advertisements; they do not build an advertising profile of you from them. Every feature of the app works exactly the same. You are not asked again. You can change your answer in iOS Settings under Privacy & Security, then Tracking.

**What we do not do with it.** We do not sell it, give it to a data broker, build an advertising profile of you, or use it to aim advertisements at you anywhere. The consent Rasikh sends to AppsFlyer refuses personalised advertising for everyone, in every country, whatever you answered.

**Never sent to AppsFlyer.** Your coordinates, your record of practice, your tasbīḥ counts, your email address, anything you read in the app.

**Clipboard.** AppsFlyer's clipboard-based link matching is switched off. Rasikh does not read your clipboard.

**Meta's app-events software.** Rasikh also contains Meta's own measurement software, because Meta requires it to measure app advertisements on iPhone. It starts at the same moment as AppsFlyer and never before, and sends Meta that the app was installed and opened, and any in-app purchase, with basic device information and your IP address; your advertising identifier only if you allowed tracking. It never receives your coordinates, your record of practice, your tasbīḥ counts, your email address or anything you read.

**Switching it off.** The "Share usage analytics" switch in Settings also covers attribution: with it off, neither AppsFlyer nor Meta's software is started at all. iOS's tracking question covers the advertising identifier separately.

**Kept for.** No longer than 12 months from the install.

## 6. Purchases

Rasikh Plus is an optional paid tier. Everything that was free stays free: prayer times, prayer alerts and the adhan, the qibla, the tracker and its export, the adhkār and the next-prayer widget. None of it needs Plus.

**Who takes the payment.** Apple does, through your Apple Account. We never take a payment. We never see your card details or your billing address. If you start a purchase from Rasikh's App Store page, the app finishes it after setup and sign-in, through Apple in the same way.

**What RevenueCat receives.** RevenueCat, our subscription provider in the United States, receives your purchase record from Apple. That is which Plus product you bought, its price and currency, the dates of purchase, renewal and expiry, and the subscription's status: free trial, active, cancelled, refunded or in a billing grace period. It also receives Apple's transaction identifiers. The record is linked to the same account identifier RevenueCat already held. RevenueCat also sees the kind of device, the iOS version and the app version. To decide whether to show "free for 7 days", the app asks RevenueCat whether your Apple Account can still have the free trial.

**What we use it for.** To unlock Plus on your phone. And to count purchases in aggregate, for example how many free trials become subscriptions. We never use it for advertising.

**Never sent to RevenueCat.** Your location, your prayer times, your record of practice, your tasbīḥ counts, your email address, your name, or any usage event.

**Analytics.** If usage analytics are on, PostHog also learns the steps on the Plus screen, which plan a purchase was for and how it ended. It never receives a price or an amount. Section 4 has the list.

**Apple's privacy label.** The App Store page lists "Purchase History", linked to you, used for App Functionality, Analytics and Third-Party Advertising, and used for tracking. It means the record of what you bought in Rasikh: RevenueCat's copy, described above, is never used for advertising, but Meta's measurement software (section 5) learns of an in-app purchase so that Meta can measure our advertisements, with your advertising identifier only if you allowed tracking. It does not cover purchases in other apps.

**Trial reminder.** If you start a free trial, the reminder that it is ending is scheduled by iOS on your phone, like a prayer alert. No server is involved.

**Restoring a purchase.** Tap "Restore purchase" on the Plus screen. The app asks Apple for the purchases made with your Apple Account, and unlocks Plus if it finds one. This works on a new phone too.

**Cancelling.** On your iPhone, open Settings, tap your name (your Apple Account), then Subscriptions, then Rasikh. After you cancel, Plus stays on until the end of the period you paid for. We cannot cancel for you. Refunds are decided by Apple, at reportaproblem.apple.com. A lifetime purchase has nothing to cancel.

**Kept for.** RevenueCat keeps your purchase record for as long as it exists there. Deleting your Rasikh account signs you out of RevenueCat but does not delete that record. Write to us and we will have RevenueCat delete it (section 11). Apple keeps its own record of your purchase under Apple's privacy policy.

## 7. Email updates

Settings has an optional "Email updates" screen. Nothing is sent until you type your address and tap Subscribe. What is sent is your email address and nothing else. It goes to Kit, our mailing provider in the United States, which also sees your IP address at that moment, as any server does. Kit may use your address only to send the updates we write. The app works the same whether or not you subscribe.

Every email has an unsubscribe link. Unsubscribing stops the emails immediately, but your address remains stored at Kit until we instruct otherwise. If you want it erased, write to us (section 13) and we will have Kit delete it. We review the list once a year and delete any address that has not opened an email from us in 24 months.

## 8. Feedback and ratings

**Feedback.** Settings, then About, then "Send feedback", and sometimes a card on the Today screen, open a short form. Every question is optional, and nothing is sent until you tap Send. What is sent: your message if you wrote one, your answer to the question about Rasikh Plus if you chose one, whether you allow us to reply by email, and, to help us read it, the app version, whether it came from the App Store or TestFlight, your language setting, your Plus status and where you opened the form. It is stored by Supabase, in India, with your account identifier. It is sent whether or not you share usage analytics, because sending it is your own choice each time. Only we read it. Your message may contain anything you choose to write, including something about your faith or your health; we use it only to understand and improve the app, and to reply if you asked us to, from the email address on your account. We never share it, and it never goes to PostHog or any other provider.

**Kept for.** 24 months, then deleted. Deleting your account deletes your feedback with it, immediately.

**Ratings.** Rasikh may ask iOS to show Apple's own rating window, at quiet moments and never during prayer screens. Apple decides whether it appears, and never tells us whether, or how, you rated. The "Rate Rasikh on the App Store" row in Settings is a link to the App Store.

## 9. What Rasikh does not do

- No advertising inside the app: no ad networks, no ad SDK, no advertisements for anyone's product, including our own. (Apple's privacy label lists "Developer's Advertising or Marketing" for the email list and the attribution service, because that is Apple's category for a company telling people about its own app.)
- No advertisement is aimed at you because of anything in this notice.
- No selling or renting of personal data.
- No combining of your record of practice, your location or your reading with data held by anyone else. Those never leave your phone.
- No prayer log, tasbīḥ count or coordinate in any analytics event, crash report, account or link.
- No cookies. The app is not a web page and contains none.
- No remote configuration. The app behaves as the version you installed; we can change it only by shipping an update through the App Store.
- No sync. Nothing you record is copied to a server, signed in or not.

The app contains one piece of open-source code that does arithmetic: Adhan, a prayer-time calculation library. It makes no network requests. The commercial services in this notice are Supabase, PostHog, AppsFlyer, Meta, RevenueCat and Kit, and the sections above say what each receives.

## 10. Who else receives your data, and where

We share personal data only with the providers named in this notice, and only the items described in their sections. Each acts on our instructions as our processor and may not use what it receives for its own purposes. We have no group companies, no affiliates and no advertising partners with access to your data.

We may disclose personal data where the law requires it or to establish or defend legal claims. Your location and your record of practice cannot be disclosed to anyone, including a court, because we do not have them.

**Countries.** Supabase hosts our project, including feedback, in India. PostHog hosts our analytics in the European Union. AppsFlyer, RevenueCat and Kit are in the United States. Nothing that stays on your phone is transferred anywhere.

**Safeguards.** Kit is certified under the EU-U.S. and Swiss-U.S. Data Privacy Frameworks and the UK Extension. Our agreements with these providers include each provider's data processing addendum and, where the transfer requires it, the European Commission's Standard Contractual Clauses and the UK International Data Transfer Addendum. Each binds the provider to process data only on our instructions, keep it confidential and secure, and remain responsible for any subcontractor. You can ask us for details of these safeguards, and Kit's addendum is at https://kit.com/dpa. Data held in another country may be subject to that country's laws, including requests from its authorities.

## 11. Deleting your data

**Your account.** Settings, then Account, then Delete account. After you confirm, the login is deleted at Supabase and the account record and any feedback you sent with it, immediately and without a waiting period. Deleting your account also instructs PostHog to delete the events attached to your account identifier and AppsFlyer to delete what it holds for your device. It does not delete your purchase record at RevenueCat. Write to us and we will have it deleted. If you would rather we did all of this, write to us.

**Your record of practice.** Deleting your account does not delete it, because it was never in the account. Use the Delete control on the Tracker's data screen. Removing the app also removes it. No app can promise the underlying bytes are wiped from the phone's memory; what we can say is that the record is encrypted by iOS and unreadable while the phone is locked.

**Everything else on the phone.** Removing Rasikh removes your settings, the last coordinate it used and the widget data. Removing the app does not delete your account. Delete the account first, or write to us afterwards.

**Anything you exported** is yours and lives wherever you sent it.

**Usage events without an account.** Events recorded before you signed in are attached to a random identifier we cannot connect to you. Write to us and we will tell you what can and cannot be found.

**The email list.** Use the unsubscribe link, or write to us to have your address erased (section 7).

## 12. Security

Everything the app stores is protected by iOS device encryption. Your record of practice is additionally held under a key that iOS discards when you lock the phone, and is excluded from backups. Your account session is held in the iOS Keychain. Every connection the app makes is encrypted, and the app cannot be configured to talk to any of these services unencrypted. The account database enforces that a signed-in person can reach only their own record, and that feedback can be sent but never read back by the app; the key that could bypass those rules exists only on our side and is in no copy of the app. No system is completely secure, but the most sensitive thing the app holds, your record of practice, is not somewhere we could lose it.

## 13. Your rights, and how to use them

You may have the right to access your personal data, correct it, erase it, restrict or object to our use of it, withdraw consent at any time, and receive a copy in a usable format.

**Most of these you can do yourself, in the app.** See, export and delete your record of practice on the Tracker. Delete your account, and with it your feedback, in Settings. Switch analytics and attribution off in Settings, at no cost to any feature.

**For anything else, write to us** at rasikh@tjbventures.ai and say what you want: a copy of what we hold, a correction, or deletion. If you have an account, write from its email address; if you are asking about the email list, write from the subscribed address. If you write from another address we will ask you to confirm from the one on file, so that nobody else can delete your account or learn your address. We reply within one month. If a request is complex we may take up to two further months and will tell you why within the first month. We do not charge. If we refuse a request we will say why, and you may complain to a regulator or go to court. Please do not send us your record of practice; we do not need it, and if you send it we will delete the message after answering.

**Complaints.** You may complain to your data protection authority: in the United Arab Emirates the UAE Data Office; in Saudi Arabia the Saudi Data and AI Authority (SDAIA); in Turkey the Personal Data Protection Authority (KVKK); in the United Kingdom the Information Commissioner's Office (ico.org.uk); in the European Economic Area the authority where you live or work; in California the California Privacy Protection Agency. We would prefer to hear from you first, but you do not have to.

**United Arab Emirates.** We are registered in Ajman Free Zone, so the applicable law is Federal Decree-Law No. 45 of 2021 on the Protection of Personal Data. Its implementing regulations had not been issued at the date of this notice. We handle requests on the timetable above regardless.

**Saudi Arabia and Turkey.** The Saudi Personal Data Protection Law and Turkey's Law No. 6698 treat information about religious belief as sensitive. If your App Store country is Saudi Arabia or Turkey, our legal basis for usage analytics, attribution and feedback is your explicit consent, which you can withdraw at any time in Settings at no cost to any feature. Your record of practice, your location and your prayer times stay on your phone.

**United Kingdom and European Economic Area.** Information about religious practice is special-category data under Article 9. Your record of practice, your location and your prayer times are processed only on your phone; we do not receive them. We treat the fact that you use Rasikh as special-category data too, because using a Muslim daily-practice app indicates a religious affiliation. Our legal basis for the account, the usage events, the attribution records, the feedback and the email list is therefore your explicit consent (Articles 6(1)(a) and 9(2)(a)); for running the account we also rely on Article 6(1)(b). You may withdraw consent at any time, and withdrawing does not affect anything done before. We have no office in the EU or UK and have not appointed a representative under Article 27; we will appoint one, and name them here, if our processing of EU or UK data stops being occasional and small in scale.

**United States.** Most state privacy laws do not apply to us by their thresholds, but we offer these rights to everyone in the US. What we collect falls in the categories those laws call identifiers, internet activity and, for Rasikh Plus, commercial information: an email address, a name if Apple supplied one, an account identifier, a device identifier for our own app, the usage events in section 4, feedback you send, and, if you buy Rasikh Plus, the record of that purchase (section 6). We do not sell personal data and do not share it for cross-context behavioural advertising. We treat what we hold as sensitive personal information and use it only for the purposes stated. We do not discriminate against anyone for exercising a right.

**Indonesia and Malaysia.** Both countries' data protection laws treat information about religious belief as requiring particular protection and give you rights to see, correct and delete what a company holds. What the app records of your practice stays on your phone; what we hold is described above.

## 14. Retention

On your phone: until you delete it or remove the app. Your account: until you delete it. Usage events: 12 months. Attribution records: up to 12 months from the install. Feedback: 24 months, or until you delete your account. Purchase records at RevenueCat: until you ask us to delete them (section 6). The email list: while you are subscribed, with inactive addresses deleted after 24 months. We keep a record of the fact and date of your consent for as long as we hold the data it covers and for one year afterwards.

## 15. Children

Rasikh is for a general audience and contains nothing directed at children. We do not knowingly create an account for, or collect an email address from, anyone under 13, or under the higher age some countries set for consenting to a service like this (16 in some European countries, 15 in France). If you believe a child has created an account or subscribed, write to us and we will delete it.

## 16. Changes to this notice

We change the date at the top whenever this notice changes. If a future version of the app collects or sends something this version does not, this notice will say so before that version is released. If a change would mean using your data for something you did not consent to, we will ask again rather than rely on the consent you gave. If any data described here is exposed, we will notify the relevant regulator within the period the law requires and tell the people affected what happened.

## 17. Contact

TJB Ventures FZE
Building C1, Ajman Free Zone, Ajman, United Arab Emirates
rasikh@tjbventures.ai