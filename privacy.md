---
layout: default
title: Privacy Policy
permalink: /privacy/
---

# **Privacy Policy for FamilyFund**

**Last Updated: October 8, 2026**


## **1. Introduction**

FamilyFund ("we," "us," "our," or "App") is a budgeting and expense-tracking app for Apple devices.

For privacy and data protection purposes, FamilyFund is operated by **Petro Kulakov**.

This Privacy Policy explains how we process information when you use FamilyFund, contact support, or purchase premium features through Apple platforms.

FamilyFund is designed so that your financial records stay on your device and, if you enable sync, in iCloud using Apple's CloudKit infrastructure. Shared-household records can also be accessible to the participants you choose through CloudKit sharing. FamilyFund does not operate its own backend for storing your financial ledger.

***


## **2. Data We Process**

### **2.1 Financial Data**

When you use FamilyFund, the app processes the financial information you choose to enter, such as:

- Transactions

- Budgets and category limits

- Categories and related settings

- App preferences related to your budgeting workflow

This data is:

- **Stored locally on your device** (using Apple on-device persistence frameworks)

- **Synced through Apple CloudKit** if enabled; shared-household records may be accessible to invited participants

- **Stored locally on your device or, if sync is enabled, in Apple's iCloud/CloudKit infrastructure rather than on a FamilyFund-operated backend**


### **2.2 Subscription Data (StoreKit)**

If you subscribe to FamilyFund Premium:

- Apple processes your payment directly using the App Store and StoreKit

- The app receives subscription-related status information from Apple, such as product identifiers, transaction identifiers, and entitlement status

- **We do not receive your full payment card details or billing address from Apple**


### **2.3 Currency Conversion Requests**

If you use features that require exchange-rate data, the app requests rates from `open.er-api.com`.

These requests may include:

- Base or target currency codes requested by the app

- Ordinary network metadata handled by the service or your network provider, such as IP address, headers, and timing information

We do not intentionally send your full transaction ledger to that service.


### **2.4 Support Communications and Optional Diagnostics**

If you contact us for support, we may process the information you choose to send, such as:

- Email messages

- Screenshots or attachments

- App version and operating system details

- Optional diagnostics you choose to include to help us investigate a problem


### **2.5 Receipt Capture and Recognition**

Where available, you can photograph a receipt or select an existing image to prefill an expense. The current recognition flow uses Apple Vision and the bundled SaviloReceiptKit on your device. FamilyFund does not upload the image or recognized text to its analytics endpoint or an external AI recognition service.

Receipt images and recognition results are used temporarily for review and editable prefill; the current flow does not attach the original image to the saved transaction. Images you select from Photos remain subject to your Photos settings. Only the fields you confirm and save become financial records, following the storage and sharing rules above. Recognition can be inaccurate: review the amount, date, currency, and other fields before saving. Camera access is requested when you use the camera; refusing analytics does not prevent receipt recognition.

### **2.6 Optional Product Analytics**

FamilyFund offers optional first-party usage analytics to improve the app for users and make it easier to use. This feature is available in app versions that include the analytics consent screen. Events are collected and sent only after you explicitly allow analytics.

Collection is off by default. A separate screen asks whether you want to allow analytics; refusal or closing the screen does not restrict app features. You can change your decision in **Profile > Privacy controls**. Accepting terms, buying a subscription, or permitting camera access is not analytics consent.

With your permission, events can describe feature use, such as onboarding completion, budgeting actions, subscription flows, camera use, receipt-recognition success or failure, and saving an expense after receipt prefill. Each upload contains:

- An event name and timestamp
- A random installation identifier, hashed by our service before storage
- App version and build number, operating-system major version, and language
- The consent-notice version

The identifier is **pseudonymous, not anonymous**. Event counts measure actions, not necessarily different people. Analytics does not include amounts, currency or category selections, transaction descriptions, merchant or household names, receipt images, recognized receipt content, contacts, payment details, advertising identifiers, or precise location.

Events are sent to a FamilyFund endpoint hosted on **Cloudflare Workers**, with **Cloudflare D1** used for event storage and aggregated counts. Cloudflare also processes network information, such as IP addresses and request metadata, to deliver and protect the service. This infrastructure processing is separate from the event fields listed above.

### **2.7 Advertising and Cross-App Tracking**

FamilyFund does not use these analytics for advertising, cross-app tracking, or selling personal information. It does not integrate advertising SDKs or third-party analytics SDKs for marketing profiling.

***


## **3. How We Use Your Data**

We use data to provide the functions you request, support users, and, with your permission, improve the app and its usability.

**Financial Data:** To let you log transactions, create budgets, track spending, and sync your data through your personal iCloud account when enabled.

**Subscription Data:** To validate Premium status and unlock paid features.

**Currency Request Data:** To provide currency conversion results inside the app.

**Receipt Images and Recognition:** To prepare an editable expense draft that you review before saving.

**Optional Analytics:** To understand which features work well, investigate recent failures, and compare adoption and seasonal usage trends.

**Support Information:** To respond to support requests, troubleshoot problems, and improve app reliability.

***


## **4. Data Storage and Security**

### **4.1 iCloud Sync (CloudKit)**

- Personal financial records can be stored in your **private iCloud database** if you enable sync

- If you create or join a shared household, shared records are stored through CloudKit sharing and accessible to the relevant participants according to their permissions

- Leaving a household or revoking future access does not recall exports or copies another participant has already made

- This data is handled through Apple CloudKit infrastructure tied to your Apple account

- We do not have our own server copy of your financial ledger


### **4.2 On-Device Storage**

- FamilyFund stores a local copy of your data on each device you use

- This data benefits from Apple device security features, including device-level encryption and access controls


### **4.3 No FamilyFund-Operated Ledger Backend**

FamilyFund does not operate its own backend server for storing your transaction history, budgets, or categories. When sync is enabled, storage is handled through Apple's iCloud and CloudKit services.

***


## **5. Data Sharing and Recipients**

We do not sell your personal data.

Depending on the feature you use, data may be processed by:

- **Apple**, for App Store billing, StoreKit subscription handling, CloudKit/iCloud sync, and Apple platform services

- **The exchange-rate provider used by the app** (`open.er-api.com`) when currency conversion data is requested

- **Cloudflare**, for optional analytics hosting, storage, and service security when you allow analytics

- **Participants you choose to share with**, for shared-household records and invitations through Apple CloudKit

- **Email providers and mail clients** when you contact support or send attachments

- **Public authorities or courts** if disclosure is required by law

***


## **6. Children's Privacy**

FamilyFund is a budgeting tool. An App Store age rating does not by itself establish a person's ability to enter a contract or consent to analytics. Optional analytics remains off unless permitted, and is not required to use budgeting or receipt recognition.

If you are below the age at which you can independently consent to this processing under your local law, do not enable analytics without the authorisation of a parent or guardian where required. Consent requirements vary by country. A consent button is not an age-verification system.

If you believe a child's information has been sent without the required authorisation, contact support. We will assess the processing and applicable deletion or restriction rights. Please do not include financial records or identity documents in the initial message.

***


## **7. Third-Party Services**

### **7.1 Apple Services**

FamilyFund uses Apple services including:

- **CloudKit (iCloud):** For optional personal data sync

- **StoreKit:** For subscription purchases and entitlement handling

- **SafariServices / system browser:** To display legal documents and web content when needed

For Apple's privacy practices, see: <https://www.apple.com/legal/privacy/>


### **7.2 Exchange-Rate Service**

FamilyFund may request exchange-rate data from: <https://open.er-api.com/>


### **7.3 Cloudflare Analytics Infrastructure**

When you allow optional analytics, Cloudflare processes event and network data to provide the FamilyFund endpoint. See [Cloudflare’s privacy policy](https://www.cloudflare.com/privacypolicy/). Receipt recognition in the current flow is on-device; permission for analytics does not authorize uploading receipt content.

### **7.4 No Third-Party Advertising SDK**

FamilyFund does not integrate advertising SDKs or third-party analytics SDKs for marketing profiling in the released app.

***


## **8. Data Retention**

- **Financial Data on your device:** Kept until you delete it, delete the app, or reset app data

- **Financial Data in iCloud:** Kept until you delete it from the app and/or from your iCloud account, subject to Apple's systems

- **Optional raw analytics events:** Retained for 30 days from server receipt for analytics verification and investigating recent failures

- **Aggregate usage counts:** Retained for 12 calendar months for adoption and seasonal comparisons. Small counts are suppressed in reports; aggregation alone is not a guarantee of anonymity

- **Analytics expiry:** The configured deletion job runs daily, so physical removal can follow expiry by up to one scheduling interval. These periods apply to the analytics event tables and aggregate counts; infrastructure processing by providers is described separately in this policy

- **Receipt images:** Used temporarily for recognition and review rather than retained as transaction attachments by the current flow

- **Subscription Status used by the app:** Kept only as long as needed to determine access to premium features

- **Support Emails and Attachments:** Kept for up to 12 months after the last support interaction, unless a longer period is required by law or needed for an ongoing dispute

- **Optional Diagnostics sent with support requests:** Kept only as long as needed to investigate the issue and normally no longer than the related support case retention period

Deleting the app removes local on-device data, but it may not automatically remove data stored in your iCloud account or information already contained in support emails you previously sent.

***


## **9. Your Rights and Controls**

Depending on your location and applicable law, you may have the right to:

1. **Access:** Request access to personal data we process about you

2. **Correction:** Request correction of inaccurate information

3. **Deletion:** Request deletion where applicable

4. **Restriction or Objection:** Request restriction of certain processing or object where permitted by law

5. **Portability:** Request data portability where applicable

6. **Withdraw Consent:** Withdraw consent where processing relies on consent, including optional product analytics and diagnostic material you chose to send

Withdrawal does not affect the lawfulness of processing carried out with valid consent before withdrawal. Turning analytics off stops future collection, cancels pending uploads, and clears the installation identifier on the device. Resetting the identifier does not itself delete events already received by the service. Uninstalling the app also does not automatically erase previously sent events. For access or erasure requests, contact us using the details below. Because event records are pseudonymous and are not linked to your email or account, we may need additional information to locate them; we do not require you to send financial records or receipt images for this purpose.

You can also control much of your data directly in the app by editing or deleting your own financial records and by controlling iCloud sync in Apple settings.

We normally respond to data-rights requests within one month. Where law permits an extension because of complexity or number of requests, we will explain it within that initial period. Any verification will be proportionate; do not send passwords, receipt images, or complete transaction records to establish your identity.

If we cannot identify the person concerned from pseudonymous records, applicable law may limit our ability to fulfil a request unless you provide information enabling identification. We do not collect additional identity data solely to make otherwise unidentifiable events identifiable. Withdrawal and expiry remain separate from an erasure request. Where retention is legally necessary, for example for a specific legal claim or obligation, we will assess the applicable exception rather than promise unconditional deletion.

***


## **10. Changes to This Policy**

We may update this Privacy Policy to reflect legal, technical, or product changes and will update the date above. For material changes we will provide appropriate notice. A policy update or continued app use does not grant analytics consent or permit processing for a new consent-based purpose without the required permission.

***


## **11. Contact Us**

If you have questions about this Privacy Policy or your privacy rights, contact:

**Name:** Petro Kulakov

**Public Address / P.O. Box:** Rua Antas 12

**Public Phone:** +351930694202

**Email:** support@familyfund.app

Please use this dedicated support channel rather than unrelated personal accounts. Send only what is necessary for your enquiry and redact other people's information. We do not ask for passwords, payment-card details, or identity documents in an initial request. Provider identification is given for transparency and lawful contact; it does not limit your ability to complain to an authority or exercise your rights.

***


## **12. Additional Notice for Users in the EU/EEA and Similar Jurisdictions**

The controller for FamilyFund processing described here is Petro Kulakov, contactable at support@familyfund.app and through the contact details above. The legal basis depends on the processing:

| Processing | Purpose and legal basis, where GDPR applies |
| --- | --- |
| App functionality, receipt prefill, requested sync and sharing, subscription entitlement checks | Providing the functions you request under the contract, to the extent the provider is responsible for that processing. Apple may have its own role and legal basis for Apple services. |
| Optional product analytics | Your separate consent, to understand feature use, investigate recent failures and compare usage trends. Refusal does not limit functionality. |
| Support communications and voluntarily supplied diagnostic material | Contractual support where necessary to fulfil the contract; otherwise our legitimate interest in answering requests and investigating issues. Separate consent is used where the relevant processing requires it. Sending diagnostics is optional. |
| Endpoint security and abuse prevention | Our legitimate interest in keeping services available, preventing attacks and protecting users, subject to applicable law and a balancing of rights. |
| Legally required records and responses to authorities | Compliance with an applicable legal obligation; establishment or defence of legal claims where lawful and necessary. |

You choose the financial information to enter. Camera access is needed only for camera capture, network access for requested online functions, and the relevant Apple services for sync or purchases. Without the information or permissions necessary for a particular function, that function may not work; optional analytics and support attachments are not required for the rest of the app.

Some service providers connected to the app or to support communications, including Apple, Cloudflare, email providers, and the exchange-rate service used by the app, may process data outside your country or outside the EU/EEA. This policy does not promise EU-only processing. Applicable providers and transfer arrangements depend on the service used. Where we are responsible for a restricted transfer, an applicable lawful mechanism is required, such as a relevant adequacy decision or appropriate contractual safeguards. Contact support for the safeguards applicable to your processing and how to obtain a copy. This statement does not represent that every provider has the same arrangement or that consent to analytics waives transfer protections.

FamilyFund does not use automated decision-making or profiling that produces legal or similarly significant effects about you.

You may lodge a complaint with the competent data protection authority, including the authority in your habitual residence, place of work, or place of the alleged infringement where GDPR applies. In Portugal, the authority is the [Comissão Nacional de Proteção de Dados (CNPD)](https://www.cnpd.pt/). Contacting us first is optional and does not limit your right to complain.

***

_FamilyFund is developed by Petro Kulakov_
