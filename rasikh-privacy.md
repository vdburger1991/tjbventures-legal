---
layout: rasikh
title: Privacy Notice
eyebrow: Privacy
description: What happens to your information in Rasikh. Your location and your record of practice never leave your device.
effective: 21 August 2026
updated: 21 August 2026
permalink: /rasikh-privacy.html
---

## 1. What this Notice covers

We have developed this Notice, which:

- sets out the types of personal data Rasikh handles, and the one type we receive;
- explains how and why it is used;
- explains who else receives any of it;
- explains how it is protected; and
- explains the rights and choices available to you, and how to use them.

**This Notice applies to the Rasikh iOS app.** It does not cover our websites, our landing pages, or any advertisement you may have arrived from — those carry their own notice, because a website and an app are different things and a single document claiming to cover both would end up inaccurate about one of them.

**Rasikh has no account, no login, and no server operated by us that holds anything about you.** There is exactly one feature in the app that transmits anything anywhere, it is optional, and it only acts when you tap Subscribe. Section 7 describes it. Everything else in this Notice describes information that stays on your device.

## 2. Personal data we handle, and why

There are only two rows in this table, and only one of them involves us at all.

| What | Where it is processed | Why | Our legal basis | How long |
| --- | --- | --- | --- | --- |
| Your location, prayer times, record of practice, dhikr counts and widget data | On your device only. We never receive it | To show prayer times, schedule alerts, point to the qibla, and keep the record you asked the app to keep | We are not a recipient of this data. The app stores it on your device because you asked for a feature that requires it — storage strictly necessary for a service you explicitly requested | Until you delete it or remove the app |
| Your email address, if you subscribe | Sent to Kit, our mailing provider, in the United States | To send you occasional updates about the app | Your explicit consent | See section 13 |

**You do not have to give us anything.** Every feature of Rasikh works without an email address, and the app works without location permission if you choose your city by hand. Nothing is withheld from you for declining either.

**No automated decision-making.** We make no decisions about you by automated means and we do not profile you. Any streaks or statistics shown in the app are calculated on your device, from what you entered, for you to look at. No one else sees them and nothing follows from them.

**No data protection officer.** We are not required to appoint one, and we have not. Privacy questions go to the address in section 19 and are answered by the company's principal.

## 3. Your location

Rasikh asks for permission to use your location once, so that it can calculate prayer times where you are. It then takes a fresh reading each time you open the app, because prayer times depend on where you are now rather than where you were when you installed it. If you set a city by hand instead, it stops taking readings altogether.

**What happens to it.** Your coordinates are used on your device, by calculations that run on your device, to produce the times shown on your screen and the alerts scheduled on your phone.

**Where it goes.** Nowhere. There is no server of ours to send it to, and it is not sent to any other company. The app contains exactly one piece of code that can reach the internet — the email signup in section 7 — and it is not the code that handles your location. The two live in separate parts of the app, and an automated check run before each release fails the build if any other file acquires the ability to make a network request.

**The permission.** Rasikh requests only "While Using the App" location. It never requests background or "Always" access, which is the version of the permission that allows an app to record your location when you are not using it. You may change or withdraw the permission at any time in iOS Settings, under Privacy & Security, then Location Services, then Rasikh.

**Precision.** Your coordinates are rounded before the app stores them, to approximately 110 metres. The app does not need to know which building you are in.

## 4. Prayer times and the calendar

Prayer times are computed on your device from your coordinates and the calculation method you select. Nothing is fetched from a server: the calculation, the calendar and the method tables are all contained in the app. This is why Rasikh works with no signal, on a plane, and in a country you have never opened it in before.

## 5. Your record of practice

If you use the tracker to record which prayers you have prayed, that record is data about your religious practice. Most privacy laws treat information of that kind as requiring greater protection than ordinary data — the GDPR calls it a special category, California calls it sensitive personal information, and Malaysia's law names religious belief specifically. We treat it as the most sensitive thing in the app, and we built the app so that we never receive it.

**Where it is stored.** On your device, in the app's own storage, at the strongest protection level iOS offers. The record is unreadable even to the app itself while your phone is locked, and its storage is excluded from device backups.

**Who can see it.** You. We cannot. It is not sent to any server we operate, because we operate none, and it is not included in anything the app sends — the only thing the app can send is the email address in section 7.

**Taking a copy with you.** The Tracker screen has an Export control. It writes a copy of your record to a file and hands it to iOS's share sheet, so you may save it, print it, or send it wherever you choose. That copy leaves the app's protected storage and becomes an ordinary file under your control: we cannot see it, reach it, or delete it, and deleting the record inside Rasikh does not delete a copy you have already exported. The temporary file is removed when the share sheet closes, and swept away at the next launch if the app closed before that happened.

This is also how you obtain a portable copy of your data. You do not need to ask us; the export is immediate and does not pass through us.

**iCloud.** This version of Rasikh does not sync. Apart from an export you asked for, your record exists in the storage described above and nowhere else. If a future version offers sync it will be off unless you turn it on, and this Notice will be updated before it appears.

## 6. Notifications and the home screen widget

**Notifications.** Prayer-time alerts are scheduled by iOS on your device, from times your device calculated. No server is involved in delivering them and no notification is sent to you from outside your phone. We cannot tell whether an alert reached you — iOS does not report that to apps, and Rasikh makes no claim about it.

**The widget.** To display a home screen widget, the app writes a short list of upcoming prayer times, the time zone they were calculated for, and the time it last wrote them into a private storage area that the app and its widget both read. **It is written whether or not you have added the widget**, because it is produced whenever the app calculates your prayer times, so that a widget is correct the moment you add one. It contains no coordinate, no calculation method, and nothing you have logged.

That area is on your device. Nothing in it is transmitted anywhere and no other app can read it. Unlike your record of practice it is not held at the strongest protection level, because a Lock Screen widget must be able to draw while your phone is locked. Removing the app removes it.

## 7. Email updates — the one thing that leaves your device

Rasikh includes an optional "Email updates" screen. It is the only feature in the app that sends anything anywhere.

> **It sends only when you tap Subscribe.** Never on launch, never in the background, never on a schedule. If you never open that screen, Rasikh makes no network request at all.

**What is sent.** The email address you typed. One field. No name, no location, no prayer times, no record of practice, no device identifier, no app version, no advertising identifier.

**Where it goes.** To Kit, the mailing provider we use to send those emails. Kit receives your email address and, as with any request made over the internet, sees your device's IP address at the moment you tap Subscribe. Kit acts as our processor and is bound to use your address only for the purpose we have specified. Its privacy policy is at https://kit.com/privacy.

**What it is for.** Occasional updates about the app, and nothing else. Subscribing has no effect on any feature and the app is fully usable without it.

**Unsubscribing.** Every email carries an unsubscribe link. See section 13 for what happens to your address afterwards.

## 8. Purchases

This version of Rasikh contains no purchases, no subscription, and no payment of any kind. There is no payment provider in the app because there is nothing to pay for.

If a future version offers a paid tier, prayer times, notifications, qibla and the core adhkār will remain free, and this Notice will be updated before any payment feature is released.

## 9. What Rasikh does not do

**In this version of Rasikh all of the following are true. If any of them ceases to be true, we will change it here and say so in the app before the version that changes it is released — not after.**

- No advertising **inside the app**: no ad networks, no ad SDK, no advertising identifier, and no advertisements for anyone's product including our own. (The App Store label for the email list reads "Developer's Advertising or Marketing" because that is Apple's name for the category covering a company emailing its own users about its own app. That is what the list is for.)
- No analytics of any kind — no Google Analytics, no Firebase, no Mixpanel, and no equivalent.
- No crash-reporting or attribution software.
- No tracking of you across other companies' apps or websites.
- No sale or rental of personal data to anyone, for any purpose.
- No sharing of your location or your record of practice with data brokers, advertisers, or anyone else.
- No cookies, and no similar technologies. The app is not a web page and embeds none.
- No remote configuration. This version's behaviour is fixed in the version you installed; we cannot change what the app does without shipping an update through the App Store, which you can see and decline.

Rasikh contains one piece of third-party code: Adhan, an open-source astronomical calculation library. It performs arithmetic and makes no network requests.

## 10. Sharing your personal data

We share your email address with Kit, and with nobody else. We do not share it within any group of companies, because there is none; we have no affiliates, no partners with access, and no advertising relationships involving your data.

We may disclose personal data where we are required to do so by applicable law, or to establish or defend legal claims. In practice the only thing we hold that could be the subject of such a request is the subscriber list. **Your location, your prayer times and your record of practice cannot be produced to anyone — including a court or a government — because we do not have them and have no means of obtaining them.**

## 11. Transfer of your personal data to other countries

Nothing held on your device is transmitted, so there is no international transfer of your location, your prayer times or your record of practice, by us or by anyone else.

If you subscribe to email updates, your email address is handled by Kit, Inc., which is based in the United States.

Kit complies with the **EU-U.S. and Swiss-U.S. Data Privacy Frameworks and the UK Extension**, and that is the mechanism this transfer relies on. Where additional safeguards are required, Kit's Data Processing Addendum provides for the European Commission's **Standard Contractual Clauses**, together with the **UK International Data Transfer Addendum** for data subject to the UK GDPR. That Addendum forms part of our agreement with Kit and binds it to process your address only on our documented instructions, to keep it confidential and secure, and to remain responsible for any subcontractor it uses.

You may request details of these safeguards by writing to us at the address in section 19, or read Kit's Addendum yourself at https://kit.com/dpa.

In the event your personal data is transferred to a foreign jurisdiction it may be subject to the laws of that jurisdiction, and the recipient may be required to disclose it to courts, law enforcement or governmental authorities there.

## 12. How we protect your personal data

Everything the app stores relies on Apple's device encryption. Your record of practice is additionally held under a key that iOS discards when you lock the phone, and its storage is excluded from device backups.

The subscriber list is held by Kit under its own security arrangements. We select providers with regard to their data protection measures and we hold no copy of the list ourselves.

No system is absolutely secure, and we cannot guarantee that no adverse event will occur. What we can say is that Rasikh is built so that there is very little to secure: one field, once, only if you tap Subscribe, and for most people nothing at all.

## 13. Retention

**On your device.** Everything is kept until you delete it or remove the app. Nothing expires on a schedule and nothing is retained for our benefit.

**The email list.** We keep your address for as long as you are subscribed. We review the list annually, and where you have not opened an email from us in twenty-four months we delete your address without waiting for you to ask.

When you unsubscribe you stop receiving emails immediately. Under our agreement with Kit, your address remains stored there until we instruct otherwise or until we stop using the service, at which point it is deleted or returned to us. Unsubscribing is therefore not by itself an erasure.

**If you want your address erased and not merely unsubscribed, say so** — write to us and we will instruct Kit to delete it. We will do that within the period in section 16. We mention the difference because most services do not, and the two are not the same thing.

**Consent records.** We keep a record of the fact and date of your consent for as long as we hold your address and for one year afterwards, because we must be able to demonstrate that consent was given.

## 14. Deleting your information

**Your record of practice.** The Delete control on the Tracker's data screen removes your record from the app's storage. Afterwards the app can no longer read it, and because that storage is excluded from backup there is no copy in an iCloud or Finder backup to restore from.

We do not claim the underlying bytes are wiped from the phone's memory. No iOS app can promise that, and one that does is overstating what it controls. What we can tell you is that everything the app stores is encrypted by iOS, and your record of practice is held under a key iOS discards when you lock the phone.

**Everything else on the device.** Removing Rasikh from your device removes the rest of what it holds, including your settings, the last coordinate it used, and the prayer times shared with the widget. There is no single in-app control that erases all of it at once; removing the app is what does that.

**Anything you exported.** A copy you saved or sent is yours and lives wherever you sent it. The app cannot reach it, and deleting the record inside the app does not delete it.

**The email list.** That is the one thing not on your device. Use the unsubscribe link in any email, or write to us, and see section 13 for what happens next.

We cannot restore anything for you, because we never held it.

## 15. Your rights

Under applicable data protection laws you may have the right to: request **access** to your personal data; **rectify** information that is incomplete or inaccurate; **erase** your personal data; **restrict** our use of it; **object** to our use of it, including for direct marketing; **withdraw** any consent you have given, at any time; and receive your personal data in a usable electronic format and transmit it elsewhere (**portability**).

**Most of these you exercise without us.** Your records are on your device: you can see them in the app, take a copy with Export, and delete them with Delete. You do not need our permission and there is nothing for us to approve.

**The email list is the one thing you must ask us about.** Section 16 explains how.

**United Arab Emirates.** We are registered in Ajman Free Zone, which has no data protection law of its own, so the applicable regime is the federal law: Federal Decree-Law No. 45 of 2021 on the Protection of Personal Data. Its implementing regulations had not been issued at the date of this Notice, so some of its procedures are not yet settled. We are not waiting for them — write to us and we will handle your request on the timetable in section 16.

**United Kingdom and European Economic Area (UK GDPR / EU GDPR).**

*Your record of practice.* Data about religious belief or practice is a special category of personal data under Article 9. Your record of practice, your location and your prayer times are processed only on your own device, by software running on it. We do not receive them, we have no means of receiving them, and we operate no server that could hold them.

*Your email address, if you give it to us.* **We treat the subscriber list itself as special-category data**, because being on a list of Rasikh users indicates a religious affiliation even though the address alone says nothing. Our lawful basis is your explicit consent under Articles 6(1)(a) and 9(2)(a), given when you type your address and tap Subscribe. You may withdraw it at any time; withdrawing does not affect the lawfulness of anything done before you withdrew.

**United States.** Most state privacy laws do not apply to us by their own thresholds. We offer these rights to everyone in the US regardless, because the honest answer is short: the only personal data we collect is an email address you typed, in the category the laws call *identifiers*, obtained from you and no one else, used to send you updates about the app and nothing else, and kept as described in section 13. We do not sell personal data and we do not share it for cross-context behavioural advertising, as California defines those terms. Because being on this list indicates a religious affiliation we treat it as sensitive personal information and use it only to send the updates you asked for. We do not discriminate against anyone for exercising a right.

**Indonesia and Malaysia.** Indonesia's Personal Data Protection Law (Law No. 27 of 2022) and Malaysia's Personal Data Protection Act both treat information about religious belief as requiring particular protection, and both give you rights to see, correct and delete what a company holds about you. The same answer applies as everywhere else: what the app records stays on your device, and the only thing we hold is an email address you gave us.

**Our representative in the EU and UK.** We are established in the United Arab Emirates and have no office in the European Union or the United Kingdom. Article 27 of the GDPR and of the UK GDPR requires a company in our position to appoint a local representative unless its processing of European data is occasional, small in scale and low in risk. Ours is one optional mailing list, no server, and nothing collected from the app itself. On that basis we have not appointed a representative. We keep this under review and will appoint one, and name them here, if that changes.

## 16. How to exercise your rights

Write to us at the address in section 19 and tell us what you would like: a copy of what we hold, a correction, or deletion.

**How we verify it is you.** We operate no accounts and hold no passwords, so the only thing we can verify is that the request comes from the address itself. Write from the address you subscribed with and that is sufficient. If you write from a different address we will ask you to confirm from the subscribed one, because acting on an unverified request would allow a stranger to unsubscribe you or learn your address.

**How long we take.** Within one month. If a request is genuinely complex we may take up to two further months, and if we do we will tell you why within the first month. We do not charge for this.

**If we refuse.** We will tell you why, and tell you that you may complain to a regulator or go to court.

**Please do not send us your record of practice.** If you write to us with a question we do not need it and do not want it. If you send one anyway we will answer your question and then delete the message.

**Complaining.** You may lodge a complaint with your local data protection authority. In the United Arab Emirates that is the UAE Data Office; in the United Kingdom, the Information Commissioner's Office (ico.org.uk); in the EEA, the authority in the country where you live, where you work, or where you believe the problem occurred. In California, the California Privacy Protection Agency. We would rather you told us first, but you are not obliged to.

## 17. Children

Rasikh is made for a general audience and contains nothing directed at children. The app itself collects nothing from anyone of any age, because everything it records stays on the device.

The email list is the exception and it is not for children. We do not knowingly collect an email address from anyone under 13, and where local law sets a higher age for consenting to a service of this kind on your own — 16 in some European countries, 15 in France — we do not knowingly collect one from anyone below that age either. If you believe a child has subscribed, write to us and we will delete the address without asking you to prove anything.

## 18. Changes to this Notice

We will change the date at the top whenever this Notice changes.

If a change means we would use your email address for something not described when you gave it to us, we will not rely on the consent you have already given. We will ask you again, and if you do not answer, nothing changes for you.

If a future version of the app collects or transmits something this version does not — sync, an account, a purchase — this Notice will say so **before** that version is released, not after.

**If something goes wrong.** The realistic risk is not your phone but our mailing provider, which is the only place any of your data sits outside your device. If we learn that the subscriber list has been exposed we will notify the relevant regulator within the period the law requires, and we will email everyone on the list and say plainly what happened — including if what was exposed is no more than the fact that you use a Muslim prayer app, which for some of our users is the part that matters most.

## 19. How to contact us

If you have any question about this Notice, or if you become aware of any mishandling or breach of your personal data, please write to us.

TJB Ventures FZE
Building C1, Ajman Free Zone, Ajman, United Arab Emirates
rasikh@tjbventures.ai

We will endeavour to respond as soon as possible, and in any event within the period set out in section 16.
