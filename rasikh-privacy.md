---
layout: rasikh
title: Privacy Notice
eyebrow: Privacy
description: What happens to your information in Rasikh. Your location and your record of practice never leave your device.
effective: 21 August 2026
updated: 16 September 2026
permalink: /rasikh-privacy.html
---

Rasikh is made by TJB Ventures FZE, a company registered in Ajman Free Zone, United Arab Emirates ("we", "us"). This notice explains what information the Rasikh iOS app handles, what stays on your phone, what reaches us or a company working for us, and what you can do about it. It covers the app only, not our websites.

> **The short version.** Your location, your prayer times and your record of practice stay on your phone. We never receive them, and neither does any company we work with. The app requires an account, which holds your email address and little else. It sends a short, fixed list of usage events to an analytics service, which you can switch off. It uses an attribution service to learn which advertisement or link brought you to the app. Each of these is described below, with the name of the company involved.

---

## 1. Overview

- Your location, prayer times, record of practice, tasbīḥ counts and widget data stay on your phone. Nobody receives them. (Section 2)
- Your account holds your email address, a random account identifier, the date it was created, and your name if Apple supplied one. Supabase stores it in India. (Section 3)
- A fixed list of usage events goes to PostHog in the European Union, with your account identifier attached when you are signed in. You can switch it off. (Section 4)
- AppsFlyer, in the United States, learns that the app was installed or opened and which link or advertisement led to it. Your advertising identifier is included only if you allow tracking when iOS asks. (Section 5)
- RevenueCat, in the United States, holds your account identifier so a paid tier could work later. There is nothing to buy in this version. (Section 6)
- Kit, in the United States, holds your email address only if you subscribe to email updates. (Section 7)

| Information | Where it is processed | Why | Legal basis | Kept for |
| --- | --- | --- | --- | --- |
| Your location, prayer times, record of practice, tasbīḥ counts and widget data | On your phone only. Never sent to us or to anyone else | To show prayer times, schedule alerts, point to the qibla and keep the record you asked the app to keep | Not received by us. Stored on your phone because you asked for a feature that needs it | Until you delete it or remove the app |
| Your email address, your name if Apple gives us one, and an account identifier | Supabase, our sign-in provider (India) | So you can sign in, and so a future version can restore your settings on a new phone | Providing the service you asked for (GDPR Article 6(1)(b)), and your explicit consent when you create the account (Article 9(2)(a)) | Until you delete the account |
| A fixed list of usage events (which screens you opened, which features you used, that a log entry happened) with your account identifier attached when you are signed in | PostHog, our analytics provider (European Union) | To see which parts of the app are used and where people get stuck | Your consent (Articles 6(1)(a) and 9(2)(a)) | 12 months |
| That the app was installed or opened, the device identifier iOS gives our app (the IDFV), and, only if you allow it when asked, your advertising identifier (the IDFA) | AppsFlyer, our attribution provider (United States) | To learn which advertisement or link brought you to the app, and to open the right screen when you follow a link | Your consent (Article 6(1)(a)) | Up to 12 months |
| Your account identifier | RevenueCat, our subscription provider (United States) | So that a paid tier, if we build one, works without moving your account | Providing the service you asked for (Article 6(1)(b)) | Until you delete the account |
| Your email address, if you subscribe to email updates | Kit, our mailing provider (United States) | To send you occasional updates about the app | Your consent | While you are subscribed |

We make no automated decisions about you and we do not profile you. Streaks and statistics shown in the app are calculated on your phone, from what you entered, for you alone.

## 2. What stays on your phone

**Your location.** Rasikh asks for location permission so it can calculate prayer times where you are. It asks for "While Using the App" access only, never "Always". It takes a fresh reading each time you open the app. If you choose your city by hand instead, it takes no readings at all. Coordinates are rounded to about 110 metres before they are stored. They are used only by calculations running on your phone and are never sent to us or to any provider. The only location-related value the app can record anywhere is a two-letter country code, recorded once if you choose a city by hand. You can withdraw the permission at any time in iOS Settings under Privacy & Security, then Location Services, then Rasikh.

**Prayer times.** Calculated on your phone from your coordinates and the calculation method you choose. The calculation, the calendar and the method tables are all inside the app. Nothing is fetched from a server, which is why Rasikh works without a signal.

**Your record of practice.** If you use the tracker to record which prayers you prayed, that record is information about your religious practice. It is stored on your phone at the strongest protection level iOS offers: it cannot be read while your phone is locked, and it is excluded from device backups. It is not uploaded to your account, not synced, and not backed up to any server. Creating an account does not change this. The only thing analytics can learn about it is that a log entry happened, with no detail attached: not which prayer, not when, not how many.

**Export and delete.** The Tracker screen has an Export control that writes a copy of your record to a file and hands it to the iOS share sheet. That copy is then an ordinary file under your control; we cannot see or delete it. The Delete control on the Tracker's data screen removes the record from the app. Because the storage is excluded from backups, there is no backup copy to restore.

**Notifications and the adhan.** Prayer-time alerts are scheduled by iOS on your phone from times your phone calculated. No server is involved. The adhan recording is inside the app and is played from there. Tapping "Log this prayer" on an alert writes to the record described above, on your phone.

**The widget.** To draw a home screen or Lock Screen widget, the app writes the prayer times for today and tomorrow, their time zone, your language and region setting, and the time of writing into a storage area shared between the app and its widget. It contains no coordinate, no calculation method and nothing you logged. It is written whenever the app calculates prayer times, whether or not you have added a widget. It stays on your phone and is removed with the app. It is not held at the strongest protection level, because a Lock Screen widget has to draw while the phone is locked.

## 3. Your account

Rasikh requires an account. After you have chosen your location, calculation method and alerts, the app asks you to sign in and does not continue until you have. Once you are signed in, the app works offline exactly as before.

**How you sign in.** With an email address and a password, or with Sign in with Apple. If you use Sign in with Apple and choose to hide your email address, Apple gives us a relay address and we never see your real one.

**What the account holds.** Supabase, our sign-in provider, stores your login: your email address, your password in hashed form (we cannot read it), and the link to your Apple ID if you used one. Alongside it we keep one record with four fields: a random account identifier, your email address, the date the account was created, and your name if Apple supplied one when you first signed in. Signing up with an email address gives us no name. There is no table for prayers, tasbīḥ counts, locations, settings or reading history.

**Who can read it.** The database enforces that a signed-in person can read and change only their own record. The key inside the app cannot reach anyone else's.

**Where it is stored.** Supabase hosts our project in Mumbai, India. Section 9 describes the safeguards for that transfer.

**What Supabase also sees.** Your phone's IP address when you sign in or your session is refreshed, as any server does.

**What the account is for.** So that a future version can restore your settings on a new phone, and so that a paid tier, if we build one, does not require moving your account. In this version it does little more than let you sign in.

**Deleting it.** Open Settings, then Account, then Delete account. The login and the account record are deleted together, immediately. Section 10 has the details.

## 4. Usage analytics

Rasikh sends a short, fixed list of usage events to PostHog, our analytics provider, hosted in the European Union. We are one person building this app, and without these events the choice of what to fix next is a guess.

**The complete list.** The app cannot send anything that is not on it.

- a screen was opened, and which one, from a fixed set of screen names;
- onboarding finished;
- a feature was opened, and which one, from a fixed set of names;
- what you answered when iOS asked about notifications: allowed, refused, or asked later;
- you chose a city by hand, recorded as a two-letter country code;
- you signed in, and by which method;
- you signed out;
- a practice-log entry was made, with nothing attached;
- an adhkār occasion was opened: morning, evening or before sleep;
- the full adhan was played.

**What is attached to each event.** The kind of device, the iOS version, the app version and your language setting, added by PostHog's software. PostHog also records when the app was installed, opened, sent to the background or updated. If you are signed in, your account identifier is attached so that your sessions are recognised as one person's. If you are not, PostHog assigns a random identifier. We have told PostHog not to derive a location from your IP address.

**Crash reports.** If the app fails, PostHog receives a technical description of the failure: where in the code it happened and what kind of failure it was. It contains nothing you entered or logged. Crash reports are attached to the same identifier as the events above.

**Session replay.** This version of Rasikh does not record session replays.

**Never sent.** Your coordinates. Your city name. Which prayers you logged, when, or in what state. Your tasbīḥ counts. Your calculation method. Which adhkār or religious text you read. Your email address. Your name. Any advertising identifier.

**What it still reveals.** That a person, identified by an account, uses a Muslim daily-practice app, and roughly how often. Under UK and EU law that is information about religious belief. That is why our legal basis is your consent, and why you can withdraw it at any time without losing any feature.

**On or off.** If your phone's region is set to a country in the European Economic Area, the United Kingdom, Guernsey, Jersey, the Isle of Man or Gibraltar, analytics are off until you turn them on. Everywhere else they are on until you turn them off. The switch is in Settings, under Privacy: "Share usage analytics". Turning it off stops new events immediately. To have past events deleted, see section 10.

**Kept for.** 12 months, then deleted.

## 5. Links and attribution

Rasikh uses AppsFlyer for two things: opening the right screen when you follow a link to the app, and telling us which advertisement or link an install came from.

**What AppsFlyer receives.** That the app was installed or opened. The identifier iOS gives an app for the device it is on, called the identifier for vendor (IDFV); it is specific to our app and is reset when you delete the app. Your IP address, the kind of device and the iOS version. The parameters carried by a link you followed. Your account identifier, if you are signed in. And, only if you allowed tracking when asked, your advertising identifier (IDFA).

**The tracking question.** After you finish setting up the app and sign in, a screen explains what the answer is for, and then iOS asks whether to allow the app to track you across apps and websites. If you allow it, AppsFlyer reads your advertising identifier and uses it to tell us which advertisement or link brought you to Rasikh. If you refuse or never answer, no advertising identifier is read, and every feature of the app works exactly the same. You are not asked again. You can change your answer in iOS Settings under Privacy & Security, then Tracking.

**What we do not do with it.** We do not sell it, give it to a data broker, build an advertising profile of you, or use it to aim advertisements at you anywhere. The consent Rasikh sends to AppsFlyer refuses personalised advertising for everyone, in every country, whatever you answered.

**Never sent to AppsFlyer.** Your coordinates, your record of practice, your tasbīḥ counts, your email address, anything you read in the app.

**Clipboard.** AppsFlyer's clipboard-based link matching is switched off. Rasikh does not read your clipboard.

**Switching it off.** The "Share usage analytics" switch in Settings also covers attribution: with it off, AppsFlyer is not started at all. iOS's tracking question covers the advertising identifier separately.

**Kept for.** No longer than 12 months from the install.

## 6. Purchases

This version of Rasikh has no purchases, no subscription and no payment. RevenueCat, the service that would manage a subscription, is included now so that a paid tier later does not require moving anyone's account. It receives your account identifier and nothing else: no email address, no name, no usage events. If a paid tier is ever offered, prayer times, notifications, qibla, the tracker and the core adhkār will stay free, and this notice will be updated before any payment feature is released.

## 7. Email updates

Settings has an optional "Email updates" screen. Nothing is sent until you type your address and tap Subscribe. What is sent is your email address and nothing else. It goes to Kit, our mailing provider in the United States, which also sees your IP address at that moment, as any server does. Kit may use your address only to send the updates we write. The app works the same whether or not you subscribe.

Every email has an unsubscribe link. Unsubscribing stops the emails immediately, but your address remains stored at Kit until we instruct otherwise. If you want it erased, write to us (section 12) and we will have Kit delete it. We review the list once a year and delete any address that has not opened an email from us in 24 months.

## 8. What Rasikh does not do

- No advertising inside the app: no ad networks, no ad SDK, no advertisements for anyone's product, including our own. (Apple's privacy label lists "Developer's Advertising or Marketing" for the email list and the attribution service, because that is Apple's category for a company telling people about its own app.)
- No advertisement is aimed at you because of anything in this notice.
- No selling or renting of personal data.
- No combining of your record of practice, your location or your reading with data held by anyone else. Those never leave your phone.
- No prayer log, tasbīḥ count or coordinate in any analytics event, crash report, account or link.
- No cookies. The app is not a web page and contains none.
- No remote configuration. The app behaves as the version you installed; we can change it only by shipping an update through the App Store.
- No sync. Nothing you record is copied to a server, signed in or not.

The app contains one piece of open-source code that does arithmetic: Adhan, a prayer-time calculation library. It makes no network requests. The commercial services in this notice are Supabase, PostHog, AppsFlyer, RevenueCat and Kit, and the sections above say what each receives.

## 9. Who else receives your data, and where

We share personal data only with the five providers named in this notice, and only the items described in their sections. Each acts on our instructions as our processor and may not use what it receives for its own purposes. We have no group companies, no affiliates and no advertising partners with access to your data.

We may disclose personal data where the law requires it or to establish or defend legal claims. Your location and your record of practice cannot be disclosed to anyone, including a court, because we do not have them.

**Countries.** Supabase hosts our project in India. PostHog hosts our analytics in the European Union. AppsFlyer, RevenueCat and Kit are in the United States. Nothing that stays on your phone is transferred anywhere.

**Safeguards.** Kit is certified under the EU-U.S. and Swiss-U.S. Data Privacy Frameworks and the UK Extension. Our agreements with all five providers include each provider's data processing addendum and, where the transfer requires it, the European Commission's Standard Contractual Clauses and the UK International Data Transfer Addendum. Each binds the provider to process data only on our instructions, keep it confidential and secure, and remain responsible for any subcontractor. You can ask us for details of these safeguards, and Kit's addendum is at https://kit.com/dpa. Data held in another country may be subject to that country's laws, including requests from its authorities.

## 10. Deleting your data

**Your account.** Settings, then Account, then Delete account. After you confirm, the login is deleted at Supabase and the account record with it, immediately and without a waiting period. Deleting your account also instructs PostHog to delete the events attached to your account identifier and AppsFlyer to delete what it holds for your device. If you would rather we did it, write to us.

**Your record of practice.** Deleting your account does not delete it, because it was never in the account. Use the Delete control on the Tracker's data screen. Removing the app also removes it. No app can promise the underlying bytes are wiped from the phone's memory; what we can say is that the record is encrypted by iOS and unreadable while the phone is locked.

**Everything else on the phone.** Removing Rasikh removes your settings, the last coordinate it used and the widget data. Removing the app does not delete your account. Delete the account first, or write to us afterwards.

**Anything you exported** is yours and lives wherever you sent it.

**Usage events without an account.** Events recorded before you signed in are attached to a random identifier we cannot connect to you. Write to us and we will tell you what can and cannot be found.

**The email list.** Use the unsubscribe link, or write to us to have your address erased (section 7).

## 11. Security

Everything the app stores is protected by iOS device encryption. Your record of practice is additionally held under a key that iOS discards when you lock the phone, and is excluded from backups. Your account session is held in the iOS Keychain. Every connection the app makes is encrypted, and the app cannot be configured to talk to any of these services unencrypted. The account database enforces that a signed-in person can reach only their own record; the key that could bypass that rule exists only on our side and is in no copy of the app. No system is completely secure, but the most sensitive thing the app holds, your record of practice, is not somewhere we could lose it.

## 12. Your rights, and how to use them

You may have the right to access your personal data, correct it, erase it, restrict or object to our use of it, withdraw consent at any time, and receive a copy in a usable format.

**Most of these you can do yourself, in the app.** See, export and delete your record of practice on the Tracker. Delete your account in Settings. Switch analytics and attribution off in Settings, at no cost to any feature.

**For anything else, write to us** at rasikh@tjbventures.ai and say what you want: a copy of what we hold, a correction, or deletion. If you have an account, write from its email address; if you are asking about the email list, write from the subscribed address. If you write from another address we will ask you to confirm from the one on file, so that nobody else can delete your account or learn your address. We reply within one month. If a request is complex we may take up to two further months and will tell you why within the first month. We do not charge. If we refuse a request we will say why, and you may complain to a regulator or go to court. Please do not send us your record of practice; we do not need it, and if you send it we will delete the message after answering.

**Complaints.** You may complain to your data protection authority: in the United Arab Emirates the UAE Data Office; in the United Kingdom the Information Commissioner's Office (ico.org.uk); in the European Economic Area the authority where you live or work; in California the California Privacy Protection Agency. We would prefer to hear from you first, but you do not have to.

**United Arab Emirates.** We are registered in Ajman Free Zone, so the applicable law is Federal Decree-Law No. 45 of 2021 on the Protection of Personal Data. Its implementing regulations had not been issued at the date of this notice. We handle requests on the timetable above regardless.

**United Kingdom and European Economic Area.** Information about religious practice is special-category data under Article 9. Your record of practice, your location and your prayer times are processed only on your phone; we do not receive them. We treat the fact that you use Rasikh as special-category data too, because using a Muslim daily-practice app indicates a religious affiliation. Our legal basis for the account, the usage events, the attribution records and the email list is therefore your explicit consent (Articles 6(1)(a) and 9(2)(a)); for running the account we also rely on Article 6(1)(b). You may withdraw consent at any time, and withdrawing does not affect anything done before. We have no office in the EU or UK and have not appointed a representative under Article 27; we will appoint one, and name them here, if our processing of EU or UK data stops being occasional and small in scale.

**United States.** Most state privacy laws do not apply to us by their thresholds, but we offer these rights to everyone in the US. What we collect falls in the categories those laws call identifiers and internet activity: an email address, a name if Apple supplied one, an account identifier, a device identifier for our own app, and the usage events in section 4. We do not sell personal data and do not share it for cross-context behavioural advertising. We treat what we hold as sensitive personal information and use it only for the purposes stated. We do not discriminate against anyone for exercising a right.

**Indonesia and Malaysia.** Both countries' data protection laws treat information about religious belief as requiring particular protection and give you rights to see, correct and delete what a company holds. What the app records of your practice stays on your phone; what we hold is described above.

## 13. Retention

On your phone: until you delete it or remove the app. Your account: until you delete it. Usage events: 12 months. Attribution records: up to 12 months from the install. The email list: while you are subscribed, with inactive addresses deleted after 24 months. We keep a record of the fact and date of your consent for as long as we hold the data it covers and for one year afterwards.

## 14. Children

Rasikh is for a general audience and contains nothing directed at children. We do not knowingly create an account for, or collect an email address from, anyone under 13, or under the higher age some countries set for consenting to a service like this (16 in some European countries, 15 in France). If you believe a child has created an account or subscribed, write to us and we will delete it.

## 15. Changes to this notice

We change the date at the top whenever this notice changes. If a future version of the app collects or sends something this version does not, this notice will say so before that version is released. If a change would mean using your data for something you did not consent to, we will ask again rather than rely on the consent you gave. If any data described here is exposed, we will notify the relevant regulator within the period the law requires and tell the people affected what happened.

## 16. Contact

TJB Ventures FZE
Building C1, Ajman Free Zone, Ajman, United Arab Emirates
rasikh@tjbventures.ai