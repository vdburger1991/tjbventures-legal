---
layout: rasikh
title: Privacy Notice
eyebrow: Privacy
description: What happens to your information in Rasikh. Your location and your record of practice never leave your device.
effective: 21 August 2026
updated: 10 September 2026
permalink: /rasikh-privacy.html
---

TJB Ventures FZE is a free zone establishment incorporated in Ajman Free Zone, United Arab Emirates ("**we**", "**us**", "**our**"). We publish the Rasikh mobile application ("**Rasikh**", "**the app**").

This Privacy Notice (the "**Notice**") describes how we collect, process, use and disclose your personal data as a "data controller". "Personal data" means any information that relates to an identified or identifiable individual.

**In this Notice, "we" means the company and "Rasikh" means the software on your phone.** That distinction matters more here than it usually does, because much of what this Notice describes is something the app does on your device without us, and we have said which is which throughout.

**This Notice changed substantially on 10 September 2026, and it changed in the direction that costs us something.** Earlier versions said that Rasikh had no account, no analytics, and exactly one thing that could leave your device. That was true of every version published up to and including 1.0. It is not true of this one. This version of the app adds an **optional account**, **product analytics**, and a **link-attribution service**, and the sections below say plainly what each of them receives. We have written the change into this document before the version that makes it true is released, which is what section 21 promises and this is us keeping it.

> **What did not change, and is now the load-bearing promise rather than a background assumption: your record of practice and your location never leave your device.** Not to us, not to any company we work with, not in an analytics event, not in a crash report, not in an account. There is no code path by which a prayer you logged, a tasbīḥ count, or a coordinate can reach a network, and an automated check run before every release fails the build if one appears.

---

## 1. What this Notice covers

We have developed this Notice, which:

- sets out the types of personal data Rasikh handles, and which of them we receive;
- explains how and why it is used;
- explains who else receives any of it;
- explains how it is protected; and
- explains the rights and choices available to you, and how to use them.

**This Notice applies to the Rasikh iOS app.** It does not cover our websites, our landing pages, or any advertisement you may have arrived from — those carry their own notice, because a website and an app are different things and a single document claiming to cover both would end up inaccurate about one of them.

**Four companies now receive something, and each is named.** Supabase holds your account if you create one (section 8). PostHog receives a short, fixed list of things you did in the app (section 9). AppsFlyer tells us which advertisement or link an install came from (section 10). RevenueCat holds an account identifier so that a paid tier, if we ever build one, works without moving anyone's account (section 11). Kit holds your email address if you subscribe to updates (section 7).

**Rasikh is fully usable without an account.** Nothing is withheld from you for not creating one, no screen blocks on it, and no reminder asks you again.

## 2. Personal data we handle, and why

| What | Where it is processed | Why | Our legal basis | How long |
| --- | --- | --- | --- | --- |
| Your location, prayer times, record of practice, dhikr counts and widget data | On your device only. We never receive it, and neither does anyone we work with | To show prayer times, schedule alerts, point to the qibla, and keep the record you asked the app to keep | We are not a recipient of this data. The app stores it on your device because you asked for a feature that requires it — storage strictly necessary for a service you explicitly requested | Until you delete it or remove the app |
| Your email address, your name if a sign-in provider gives us one, and an account identifier — **only if you create an account** | Supabase, our authentication provider | So that you can sign in, and so that a future version can restore your settings on a new phone | Performance of the service you asked for (Article 6(1)(b)) and, because being a Rasikh account holder indicates a religious affiliation, **your explicit consent** (Article 9(2)(a)) given when you create the account | Until you delete the account. See section 17 |
| A fixed, short list of things you did in the app — which screens you opened, which features you used, that a log entry happened — with an account identifier attached if you are signed in | PostHog, our analytics provider | To see which parts of the app are used and where people get stuck, so that we fix the right things | **Your consent** (Articles 6(1)(a) and 9(2)(a)) | See section 16 |
| The fact that an install came from a particular advertisement or link, and the device-level identifier iOS gives us for our own app (the IDFV) | AppsFlyer, our attribution provider | To know which advertisement or link brought someone to the app, and to open the right screen when you follow a link to it | **Your consent** (Article 6(1)(a)); we do not rely on legitimate interests for this | See section 16 |
| An account identifier and, in future, a purchase receipt | RevenueCat, our subscription provider | So that a paid tier, if we build one, does not require moving anyone's account | Performance of the service you asked for (Article 6(1)(b)) | Until you delete the account |
| Your email address, if you subscribe to updates | Kit, our mailing provider, in the United States | To send you occasional updates about the app | Your explicit consent | See section 16 |

**You do not have to give us anything.** Every feature of Rasikh works without an account, without an email address, and without location permission if you choose your city by hand. Nothing is withheld from you for declining any of them.

**No automated decision-making.** We make no decisions about you by automated means and we do not profile you. Any streaks or statistics shown in the app are calculated on your device, from what you entered, for you to look at. No one else sees them and nothing follows from them.

**No data protection officer.** We are not required to appoint one, and we have not. Privacy questions go to the address in section 22 and are answered by the company's principal.

## 3. Your location

Rasikh asks for permission to use your location once, so that it can calculate prayer times where you are. It then takes a fresh reading each time you open the app, because prayer times depend on where you are now rather than where you were when you installed it. If you set a city by hand instead, it stops taking readings altogether.

**What happens to it.** Your coordinates are used on your device, by calculations that run on your device, to produce the times shown on your screen and the alerts scheduled on your phone.

**Where it goes.** Nowhere. Your coordinates are not sent to us and are not sent to Supabase, PostHog, AppsFlyer, RevenueCat or Kit. This is a structural property rather than a policy: the code that handles your location and the code that can reach the network live in separate parts of the app, an automated check run before every release fails the build if a location value becomes reachable from the part that can transmit, and the list of things the app is permitted to record contains no coordinate, no city name, and no postcode. The most precise location any of it can carry is a **two-letter country code**, recorded once if you choose a city by hand.

**What the internet sees anyway.** Any company whose server your phone contacts sees the internet address (IP) your phone is using at that moment, as every website and every app does. An IP address is a rough indication of country or city and is not your coordinates. Where a provider allows it to be discarded, we ask it to be.

**The permission.** Rasikh requests only "While Using the App" location. It never requests background or "Always" access, which is the version of the permission that allows an app to record your location when you are not using it. You may change or withdraw the permission at any time in iOS Settings, under Privacy & Security, then Location Services, then Rasikh.

**Precision.** Your coordinates are rounded before the app stores them, to approximately 110 metres. The app does not need to know which building you are in.

## 4. Prayer times and the calendar

Prayer times are computed on your device from your coordinates and the calculation method you select. Nothing is fetched from a server: the calculation, the calendar and the method tables are all contained in the app. This is why Rasikh works with no signal, on a plane, and in a country you have never opened it in before.

## 5. Your record of practice

If you use the tracker to record which prayers you have prayed, that record is data about your religious practice. Most privacy laws treat information of that kind as requiring greater protection than ordinary data — the GDPR calls it a special category, California calls it sensitive personal information, and Malaysia's law names religious belief specifically. We treat it as the most sensitive thing in the app, and we built the app so that we never receive it.

**Where it is stored.** On your device, in the app's own storage, at the strongest protection level iOS offers. The record is unreadable even to the app itself while your phone is locked, and its storage is excluded from device backups.

**Who can see it.** You. We cannot, and nor can Supabase, PostHog, AppsFlyer, RevenueCat or Kit. It is not uploaded to an account, it is not backed up to a server, and it is not synced. **Creating an account does not change this.** An account holds your email address and a name; it does not hold what you have logged, and there is no table for it to go into.

**What analytics knows about it.** One thing, and only one: that a log entry happened. Not which prayer, not whether it was on time, not the date, not how many. That single fact carries no detail attached to it, by construction — the app has no way to attach one. Section 9 explains the whole list.

**Taking a copy with you.** The Tracker screen has an Export control. It writes a copy of your record to a file and hands it to iOS's share sheet, so you may save it, print it, or send it wherever you choose. That copy leaves the app's protected storage and becomes an ordinary file under your control: we cannot see it, reach it, or delete it, and deleting the record inside Rasikh does not delete a copy you have already exported. The temporary file is removed when the share sheet closes, and swept away at the next launch if the app closed before that happened.

This is also how you obtain a portable copy of your data. You do not need to ask us; the export is immediate and does not pass through us.

**iCloud.** This version of Rasikh does not sync. Apart from an export you asked for, your record exists in the storage described above and nowhere else. If a future version offers sync it will be off unless you turn it on, and this Notice will be updated before it appears.

## 6. Notifications and the home screen widget

**Notifications.** Prayer-time alerts are scheduled by iOS on your device, from times your device calculated. No server is involved in delivering them and no notification is sent to you from outside your phone. We cannot tell whether an alert reached you — iOS does not report that to apps, and Rasikh makes no claim about it.

**The adhan.** You can have Rasikh play the adhan in full when a prayer-time alert arrives. The recording is inside the app you installed. Nothing is streamed and no network request is made to play it.

**Logging from the alert.** A prayer-time alert carries a "Log this prayer" action. Tapping it writes to the record of practice described in section 5, on your device.

**The widget.** To display a home screen or Lock Screen widget, the app writes into a private storage area that the app and its widget both read. What it writes is: the prayer times for the current day and the next one, the time zone they were calculated for, your device's language and region setting and the digit style that follows from it, and the time it last wrote them. **It is written whether or not you have added the widget**, because it is produced whenever the app calculates your prayer times, so that a widget is correct the moment you add one. It contains no coordinate, no calculation method, and nothing you have logged.

That area is on your device. Nothing in it is transmitted anywhere and no other app can read it. Unlike your record of practice it is not held at the strongest protection level, because a Lock Screen widget must be able to draw while your phone is locked. Removing the app removes it.

## 7. Email updates

Rasikh includes an optional "Email updates" screen.

**It sends only when you tap Subscribe.** Never on launch, never in the background, never on a schedule. If you never open that screen, we never receive your email address through it.

**What is sent.** The email address you typed. One field. No name, no location, no prayer times, no record of practice, no device identifier, no advertising identifier.

**Where it goes.** To Kit, the mailing provider we use to send those emails. Kit receives your email address and, as with any request made over the internet, sees your device's IP address at the moment you tap Subscribe. Kit acts as our processor and is bound to use your address only for the purpose we have specified. Its privacy policy is at https://kit.com/privacy.

**What it is for.** Occasional updates about the app, and nothing else. Subscribing has no effect on any feature and the app is fully usable without it.

**Unsubscribing.** Every email carries an unsubscribe link. See section 16 for what happens to your address afterwards.

## 8. Your account — optional, and it holds four things

Rasikh offers an account. **It is optional and it is not a gate.** Every prayer time, every alert, the qibla, the tracker, the tasbīḥ and the adhkār work exactly the same whether you are signed in or not, and no screen asks you twice.

**What an account is for.** So that a future version can put your settings back on a new phone, and so that if we ever build a paid tier, buying it does not require moving your identity around. Today it does very little, and we would rather say that than dress it up.

**How you sign in.** With an email address and a password, with **Sign in with Apple**, or with Google. Sign in with Apple is offered wherever Google is. If you use Sign in with Apple and choose to hide your email address, Apple gives us a relay address instead of your real one and we never see your real one.

**Who holds it.** **Supabase**, our authentication provider. Supabase stores the login itself — your email address, your password in hashed form, and the link to your Apple or Google account. Alongside it we keep one row, in one table, containing exactly four fields:

- the account identifier (a random identifier, not derived from anything about you);
- your email address;
- the date the account was created;
- your name, **only if** Apple or Google gave us one when you signed in. Signing up with an email address gives us no name at all.

**That is the whole list.** There is no table for prayers, no table for tasbīḥ counts, no table for locations, no table for settings, and no table for reading history. That row is protected by a rule enforced by the database itself rather than by our code: a signed-in person can read and change their own row and no other, and the key the app carries cannot be used to reach anybody else's.

**Which country it is stored in.** Supabase hosts each project in a single region chosen when the project is created. **Ours is the region shown in the project's settings page**, and we will name it in this Notice at the next revision rather than guess at it here. If you would like to know before then, write to us at the address in section 22 and we will tell you. Section 14 explains what protects the transfer regardless of which region it is.

**What your password does.** It is sent over an encrypted connection to Supabase, which converts it into a form that cannot be turned back into the password. We never see it and we could not tell you what it is.

**What Supabase sees that you did not type.** Your device's IP address at the moment you sign in or your session is refreshed, as any server does.

**Deleting it.** Section 17.

## 9. Product analytics — a fixed list, and you can say no

Rasikh sends a short, fixed list of records about how the app is used to **PostHog**, an analytics provider. This is new in this version and earlier versions of this Notice correctly said we had none.

**Why.** We are one person building this app. Without knowing which screens people reach and which they never find, the choice of what to fix next is a guess. This is the smallest amount of information we could think of that answers that question.

**The complete list.** These are all of them. There is no general-purpose recording function in the app: an entry that is not on this list cannot be sent, because the code has no way to express it.

- a screen came into view, and which one — from a fixed set of screen names we chose;
- onboarding finished;
- a feature was opened, and which one — from a fixed set of names we chose;
- what you answered when iOS asked about notifications: allowed, refused, or asked again later;
- you chose a city by hand — recorded as a **two-letter country code and nothing else**;
- you signed in, and by which method: email, Apple or Google;
- you signed out;
- **a practice-log entry was made — with nothing attached.** Not which prayer, not whether it was prayed on time, not the date, not the running total;
- an adhkār occasion was opened, and which occasion — morning, evening, before sleep;
- the full adhan was played.

**What is attached to each of them.** The name above, the one fixed value listed with it, and — added by PostHog's own software — the kind of device, the iOS version, the app version, and your language setting. If you are signed in, your account identifier is attached so that the records from one person's several sessions are recognised as one person's. If you are not signed in, PostHog assigns a random identifier that means nothing outside its own system.

**Screen views.** The list above includes which screens you opened. It does not include anything drawn on them.

**Crash and error reports.** If the app fails, PostHog receives a technical description of the failure — where in the code it happened and what kind of failure it was. It is not a copy of your screen and it carries nothing you entered or logged. These reports are attached to the same identifier as the records above, so if you are signed in they sit on your account.

**Session replay.** Where session replay is switched on, PostHog records a reconstruction of how the app looked and was used during a session, with **text and input fields masked** — replaced with blocks rather than transmitted. We treat this as the most invasive tool in this section and it is **off on any screen that can show your record of practice, your tasbīḥ counts, your city, or your coordinates**, because masking hides typed text and would not hide a grid of prayers drawn as shapes.

**What is never sent, under any circumstance.** Your coordinates. Your city name. Which prayers you logged, when, or in what state. Your tasbīḥ counts. Your calculation method or madhhab. Which adhkār or which religious text you read. Your email address. Your name. Any advertising identifier.

**What it nonetheless reveals, and we will not pretend otherwise.** That a particular person — identified by an account, if you have one — uses a Muslim daily-practice app, and roughly how often. Under UK and EU law that is information revealing religious belief, whatever we strip from it. That is why our lawful basis is your **consent** and not our own interest in improving the product, why you are asked before anything is recorded, and why you may withdraw at any time in the app's Settings without losing a single feature.

**How to say no.** Decline when asked, or turn it off later in Settings. Turning it off stops new records immediately. To have what was already recorded deleted, see section 17.

## 10. How you found the app — links and attribution

Rasikh uses **AppsFlyer** for two things: opening the right screen when you follow a link to the app, and telling us which advertisement or link an install came from.

**What AppsFlyer receives.** That the app was installed or opened; the identifier iOS gives an app for the device it is on — Apple calls it the **identifier for vendor**, it is specific to our app alone, and it is regenerated when you delete the app; your device's IP address, and the kind of device and iOS version; the parameters carried by a link you followed; and, if you are signed in, your account identifier.

**What it does not receive, and this is the part that matters.** **No advertising identifier — no IDFA.** Rasikh does not ask for it, does not read it, and does not contain the Apple software component that would allow it to. The absence is verified against the built app before every release, not asserted. Because of that, **Rasikh never shows the "Allow this app to track you across apps and websites?" prompt** — there is nothing for it to ask about.

It also does not receive your coordinates, your record of practice, your email address, or anything you read in the app.

**What we do not do with it.** We do not combine it with data about you from other companies' apps or websites. We do not give it to a data broker. We do not use it to build an advertising profile of you or to have advertisements aimed at you elsewhere. It answers one question — *which advertisement or link brought this install* — and stops there.

**Clipboard.** AppsFlyer's clipboard-based method of recognising a deferred link is **switched off**. Rasikh does not read your clipboard, and you will never see iOS's paste banner because of it.

**How to say no.** Attribution is covered by the same consent choice as analytics in section 9 and by the same switch in Settings.

## 11. Purchases

This version of Rasikh contains no purchases, no subscription, and no payment of any kind. There is nothing to buy and no payment is taken.

**RevenueCat is nevertheless present.** RevenueCat is the service that would manage a subscription if we built one. In this version it is given your account identifier — the same random identifier described in section 8 — and nothing else: no email address, no name, no location, no record of practice, no event from section 9. It exists now so that a paid tier later does not require moving everyone's account, which is the kind of migration that loses people's purchases.

If a future version offers a paid tier, prayer times, notifications, qibla, the tracker spine and the core adhkār will remain free, and this Notice will be updated before any payment feature is released.

## 12. What Rasikh does not do

**In this version of Rasikh all of the following are true. If any of them ceases to be true, we will change it here and say so in the app before the version that changes it is released — not after.** Three items that were on this list until 10 September 2026 have been removed, because this version has analytics, error reporting and attribution. Removing them was the point of this revision; a list of promises is only worth reading if items leave it when they stop being true.

- No advertising **inside the app**: no ad networks, no ad SDK, no advertising identifier, and no advertisements for anyone's product including our own. (The App Store label for the email list reads "Developer's Advertising or Marketing" because that is Apple's name for the category covering a company emailing its own users about its own app. That is what the list is for.)
- **No advertising identifier and no tracking prompt.** The app does not contain Apple's advertising-identifier component at all, which is why it can never ask for it.
- No tracking of you across other companies' apps or websites, and no combining of anything in this Notice with data held by another company for advertising or measurement.
- No sale or rental of personal data to anyone, for any purpose.
- No sharing of your location or your record of practice with anyone at all — not with advertisers, not with data brokers, not with the providers named in this Notice, because they never receive it in the first place.
- **No prayer log, tasbīḥ count or coordinate in any analytics record, any crash report, any account, or any link.**
- No cookies, and no similar technologies. The app is not a web page and embeds none.
- No remote configuration. This version's behaviour is fixed in the version you installed; we cannot change what the app does without shipping an update through the App Store, which you can see and decline.
- No sync. Nothing you record is copied to a server, including when you are signed in.

Rasikh contains one piece of open-source third-party code that does arithmetic and nothing else: Adhan, an astronomical calculation library. It makes no network requests. The four commercial services in this Notice — Supabase, PostHog, AppsFlyer and RevenueCat — are named individually above rather than described as "our partners", because a company that will not name them is asking you to trust a category.

## 13. Sharing your personal data

We share personal data only with the providers named in this Notice — Supabase, PostHog, AppsFlyer, RevenueCat and Kit — and only the items each of their sections describes. Each of them acts as our processor, on our documented instructions, and none of them is permitted to use what it receives for its own purposes. We do not share personal data within any group of companies, because there is none; we have no affiliates, no partners with access, and no advertising relationships involving your data.

We may disclose personal data where we are required to do so by applicable law, or to establish or defend legal claims. **Your location and your record of practice cannot be produced to anyone — including a court or a government — because we do not have them and have no means of obtaining them.** What could be the subject of such a request is an account, an analytics record, or the subscriber list.

## 14. Transfer of your personal data to other countries

Nothing that stays on your device is transmitted, so there is no international transfer of your location, your prayer times or your record of practice, by us or by anyone else.

The providers named in this Notice may process personal data outside your country. **Kit, Inc.** is based in the United States. **AppsFlyer** and **RevenueCat** are United States companies. **PostHog** offers a European and a United States region, and **our analytics project is in the European Union region** — so the records described in section 9 are stored in the EU. **Supabase** hosts each project in one region, chosen when the project was created; ours is the one shown in the project's settings page and we will name it here at the next revision.

Kit complies with the **EU-U.S. and Swiss-U.S. Data Privacy Frameworks and the UK Extension**, and that is the mechanism its transfer relies on. Where additional safeguards are required, Kit's Data Processing Addendum provides for the European Commission's **Standard Contractual Clauses**, together with the **UK International Data Transfer Addendum** for data subject to the UK GDPR. Our agreements with Supabase, PostHog, AppsFlyer and RevenueCat likewise incorporate each provider's data processing addendum and, where the transfer requires it, the Standard Contractual Clauses and the UK Addendum. Each binds the provider to process what it receives only on our documented instructions, to keep it confidential and secure, and to remain responsible for any subcontractor it uses.

You may request details of these safeguards by writing to us at the address in section 22, or read Kit's Addendum yourself at https://kit.com/dpa.

In the event your personal data is transferred to a foreign jurisdiction it may be subject to the laws of that jurisdiction, and the recipient may be required to disclose it to courts, law enforcement or governmental authorities there.

## 15. How we protect your personal data

Everything the app stores relies on Apple's device encryption. Your record of practice is additionally held under a key that iOS discards when you lock the phone, and its storage is excluded from device backups.

Your account session is held in the iOS Keychain rather than in ordinary storage. Every connection the app makes is encrypted in transit, and the app cannot be configured to talk to any of these services unencrypted.

The account row is protected by rules enforced by the database itself: a signed-in person can reach their own row and no other. The key that ships inside the app grants only what a signed-in person is allowed; the key that would bypass those rules exists only on our side and is in no copy of the app.

The subscriber list is held by Kit under its own security arrangements. Analytics and attribution records are held by PostHog and AppsFlyer under theirs. We select providers with regard to their data protection measures.

No system is absolutely secure, and we cannot guarantee that no adverse event will occur. What we can say is that Rasikh is built so that the most sensitive thing it touches — your record of practice — is not somewhere we could lose it.

## 16. Retention

**On your device.** Everything is kept until you delete it or remove the app. Nothing expires on a schedule and nothing is retained for our benefit.

**Your account.** Kept until you delete it. See section 17.

**Analytics.** Records held by PostHog are deleted after **12 months**. We do not need a longer history than that to answer the question they exist for.

**Attribution.** Records held by AppsFlyer are kept for the shortest period the service provides for, and in any event no longer than **12 months** from the install they describe.

**The email list.** We keep your address for as long as you are subscribed. We review the list annually, and where you have not opened an email from us in twenty-four months we delete your address without waiting for you to ask.

When you unsubscribe you stop receiving emails immediately. Under our agreement with Kit, your address remains stored there until we instruct otherwise or until we stop using the service, at which point it is deleted or returned to us. Unsubscribing is therefore not by itself an erasure.

**If you want your address erased and not merely unsubscribed, say so** — write to us and we will instruct Kit to delete it. We will do that within the period in section 19. We mention the difference because most services do not, and the two are not the same thing.

**Consent records.** We keep a record of the fact and date of your consent for as long as we hold the data it covers and for one year afterwards, because we must be able to demonstrate that consent was given.

## 17. Deleting your information, and deleting your account

**Your account.** Open **Settings → Account → Delete account** inside the app. It asks you to confirm, and then it is gone: the login record is deleted at Supabase and the profile row described in section 8 is deleted with it automatically, because the two are joined so that neither can survive the other. There is no waiting period and you do not have to write to us. If you would rather ask us than tap it, write to the address in section 22 and we will do it for you.

Deleting your account does **not** delete your record of practice, because your record of practice was never in the account — it is on your device, and the paragraph below is how you delete that.

**Your analytics and attribution records.** Deleting your account also instructs PostHog to delete the records attached to your account identifier, and AppsFlyer to delete what it holds for your device. If you never had an account, those records are attached to a random identifier we cannot connect to you; write to us with the request and we will explain what can and cannot be found, honestly, rather than claim a deletion we cannot verify.

**Your record of practice.** The Delete control on the Tracker's data screen removes your record from the app's storage. Afterwards the app can no longer read it, and because that storage is excluded from backup there is no copy in an iCloud or Finder backup to restore from.

We do not claim the underlying bytes are wiped from the phone's memory. No iOS app can promise that, and one that does is overstating what it controls. What we can tell you is that everything the app stores is encrypted by iOS, and your record of practice is held under a key iOS discards when you lock the phone.

**Everything else on the device.** Removing Rasikh from your device removes the rest of what it holds, including your settings, the last coordinate it used, and the prayer times shared with the widget. There is no single in-app control that erases all of it at once; removing the app is what does that. **Removing the app does not delete your account** — an account outlives the app on this phone, which is the point of one. Delete the account first, or write to us afterwards.

**Anything you exported.** A copy you saved or sent is yours and lives wherever you sent it. The app cannot reach it, and deleting the record inside the app does not delete it.

**The email list.** Use the unsubscribe link in any email, or write to us, and see section 16 for what happens next.

## 18. Your rights

Under applicable data protection laws you may have the right to: request **access** to your personal data; **rectify** information that is incomplete or inaccurate; **erase** your personal data; **restrict** our use of it; **object** to our use of it, including for direct marketing; **withdraw** any consent you have given, at any time; and receive your personal data in a usable electronic format and transmit it elsewhere (**portability**).

**Several of these you exercise without us.** Your practice records are on your device: you can see them in the app, take a copy with Export, and delete them with Delete. Your account you can delete yourself, in the app. Analytics and attribution you can switch off in Settings. You do not need our permission and there is nothing for us to approve.

**Withdrawing consent costs you nothing.** Turning analytics off, or refusing it when asked, changes no feature of the app. We have deliberately built nothing that depends on it.

**The email list, and anything you want erased rather than switched off, is what you ask us about.** Section 19 explains how.

**United Arab Emirates.** We are registered in Ajman Free Zone, which has no data protection law of its own, so the applicable regime is the federal law: Federal Decree-Law No. 45 of 2021 on the Protection of Personal Data. Its implementing regulations had not been issued at the date of this Notice, so some of its procedures are not yet settled. We are not waiting for them — write to us and we will handle your request on the timetable in section 19.

**United Kingdom and European Economic Area (UK GDPR / EU GDPR).**

*Your record of practice.* Data about religious belief or practice is a special category of personal data under Article 9. Your record of practice, your location and your prayer times are processed only on your own device, by software running on it. We do not receive them, we have no means of receiving them, and no provider named in this Notice receives them.

*Your account, and the analytics attached to it.* **We treat the fact that you use Rasikh as special-category data**, because being a user of a Muslim daily-practice app indicates a religious affiliation even though an email address alone says nothing. That applies to the account, to the analytics records in section 9, to the attribution records in section 10, and to the subscriber list. Our lawful basis for the special-category aspect of every one of them is your **explicit consent** under Articles 6(1)(a) and 9(2)(a); for the mechanics of running an account we additionally rely on Article 6(1)(b), performance of the service you asked for. You may withdraw consent at any time; withdrawing does not affect the lawfulness of anything done before you withdrew.

**United States.** Most state privacy laws do not apply to us by their own thresholds. We offer these rights to everyone in the US regardless. The personal data we collect is: an email address, a name if a sign-in provider supplied one, an account identifier, a device identifier for our own app, and the records of app use in section 9 — in the categories the laws call *identifiers* and *internet or other electronic network activity*. We do not sell personal data and we do not share it for cross-context behavioural advertising, as California defines those terms. Because using this app indicates a religious affiliation we treat what we hold as sensitive personal information and use it only for the purposes stated. We do not discriminate against anyone for exercising a right.

**Indonesia and Malaysia.** Indonesia's Personal Data Protection Law (Law No. 27 of 2022) and Malaysia's Personal Data Protection Act both treat information about religious belief as requiring particular protection, and both give you rights to see, correct and delete what a company holds about you. The same answer applies as everywhere else: what the app records of your practice stays on your device, and what we hold is described section by section above.

**Our representative in the EU and UK.** We are established in the United Arab Emirates and have no office in the European Union or the United Kingdom. Article 27 of the GDPR and of the UK GDPR requires a company in our position to appoint a local representative unless its processing of European data is occasional, small in scale and low in risk. We keep this under review, and because this version begins processing account and analytics data rather than only an optional mailing list, we will reassess it before the app is offered in EU or UK storefronts and will name a representative here if one is required.

## 19. How to exercise your rights

Write to us at the address in section 22 and tell us what you would like: a copy of what we hold, a correction, or deletion.

**How we verify it is you.** If you have an account, write from the address on it. If you do not, the only thing we can verify is that a request comes from the address itself, so write from the address you subscribed with. If you write from a different address we will ask you to confirm from the one on file, because acting on an unverified request would allow a stranger to delete your account or learn your address.

**How long we take.** Within one month. If a request is genuinely complex we may take up to two further months, and if we do we will tell you why within the first month. We do not charge for this.

**If we refuse.** We will tell you why, and tell you that you may complain to a regulator or go to court.

**Please do not send us your record of practice.** If you write to us with a question we do not need it and do not want it. If you send one anyway we will answer your question and then delete the message.

**Complaining.** You may lodge a complaint with your local data protection authority. In the United Arab Emirates that is the UAE Data Office; in the United Kingdom, the Information Commissioner's Office (ico.org.uk); in the EEA, the authority in the country where you live, where you work, or where you believe the problem occurred. In California, the California Privacy Protection Agency. We would rather you told us first, but you are not obliged to.

## 20. Children

Rasikh is made for a general audience and contains nothing directed at children.

The account and the email list are not for children. We do not knowingly create an account for, or collect an email address from, anyone under 13, and where local law sets a higher age for consenting to a service of this kind on your own — 16 in some European countries, 15 in France — we do not knowingly do so for anyone below that age either. If you believe a child has created an account or subscribed, write to us and we will delete it without asking you to prove anything.

## 21. Changes to this Notice

We will change the date at the top whenever this Notice changes.

If a change means we would use your personal data for something not described when you gave it to us, we will not rely on the consent you have already given. We will ask you again, and if you do not answer, nothing changes for you.

If a future version of the app collects or transmits something this version does not — sync, a purchase, a new provider — this Notice will say so **before** that version is released, not after. That is what happened on 10 September 2026, when accounts, analytics and attribution were added: this document changed first.

**If something goes wrong.** If we learn that any of the data described here has been exposed we will notify the relevant regulator within the period the law requires, and we will tell the people affected and say plainly what happened — including if what was exposed is no more than the fact that you use a Muslim prayer app, which for some of our users is the part that matters most.

## 22. How to contact us

If you have any question about this Notice, or if you become aware of any mishandling or breach of your personal data, please write to us.

TJB Ventures FZE
Building C1, Ajman Free Zone, Ajman, United Arab Emirates
rasikh@tjbventures.ai

We will endeavour to respond as soon as possible, and in any event within the period set out in section 19.