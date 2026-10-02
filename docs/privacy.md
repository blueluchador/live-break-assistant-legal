# Privacy Policy

**Last Updated:** October 2, 2026

## 1. Overview

This Privacy Policy describes how **Decoy — Live Break Assistant** ("we", "us", or "our") collects, uses, handles, stores, and shares information when you use the Decoy Chrome Extension ("Extension").

> **Important:** Use of Decoy is subject to our **[Terms of Service](terms)**. By installing or using the Extension, you agree to those Terms.

The Extension helps collectors follow a live card break. While a live-break session is open, it reads visible listing and livestream text on that page and uses it to retrieve checklists, values, case hits, odds, and chat answers.

We collect only the data necessary to operate the Extension.

### 1.1 Chrome Web Store Compliance

**Limited Use Disclosure:** The use of information received from Google APIs will adhere to the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies#userdata), including the Limited Use requirements.

That means:

* We use this data only to provide and maintain the live-break assistant.
* We share it only with the parties named in **User Data Sharing**, to provide that feature, to comply with law, to investigate abuse, or as part of a merger or sale of Blue Luchador LLC after we tell you.
* We do not sell user data.
* We do not use user data for advertising, including personalized, re-targeted, or interest-based ads.
* We do not use user data to determine creditworthiness or for lending.
* We do not allow people to read your page text or chat messages, except when you ask us to for support, when it is necessary to investigate abuse, or when the law requires it.

## 2. When The Extension Collects Data

The Extension runs on **Whatnot** (`whatnot.com` and `www.whatnot.com`). It does not run on other websites.

* On a Whatnot page, the Extension checks whether a livestream is on screen so it can show the control that opens Decoy. That check stays on your device.
* Page text is sent to our servers only after you open Decoy on a Whatnot live page and a live-break session starts.
* While that session stays open, the Extension reads the visible text again so it can follow the break.
* Closing Decoy or leaving the session stops that collection.

The Extension is not affiliated with, endorsed by, or sponsored by Whatnot.

## 3. User Data Collection

We collect the following user data.

### 3.1 Personally identifiable information

If you start a trial or subscribe, we collect:

* Your email address
* Your subscription or trial plan
* Remaining usage (live breaks and Expert Answers)
* Subscription identifiers from our payment processor

### 3.2 Financial and payment information

* ExtensionPay collects your payment card number when you pay.
* We do not receive or collect the full card number.

### 3.3 Authentication information

* An ExtensionPay account key, stored in Chrome sync storage, used to restore your subscription.
* A short-lived session token, kept in memory, used to call our API.

### 3.4 Website content

When a live-break session is open, we collect visible text on that Whatnot page, including:

* Lineup and listing text
* Livestream details
* Other words visible on that page, such as a chat overlay or a username

We do not collect a screenshot or image of the tab. We do not collect page contents from any site other than the Whatnot page where the session is open.

### 3.5 Web browsing activity

* We read the address of browser tabs to turn the assistant on only for Whatnot, and to read the live-page id from that address.
* We do not save a browsing history of other websites.
* We do not collect your full browsing history.

### 3.6 Personal communications and user-provided content

When you use Decoy chat, we collect:

* The messages you send
* The replies generated for you
* The recent break text needed to answer

### 3.7 User activity and operational data

We collect:

* The number of live breaks and Expert Answers used
* Subscription or trial status
* Request timestamps
* Error and performance logs
* Your IP address, when our host records it for diagnostics

### 3.8 Data stored on your device

The Extension keeps, on your device:

* The ExtensionPay account key
* Theme and similar preferences
* Whether you dismissed an in-product notice
* Whether the current tab is a Whatnot live page
* In-session live-break chat state

### 3.9 Data we do not collect

We do not collect:

* Health information
* Location
* Your full browsing history
* Keystrokes
* Private messages from other sites
* Page contents from sites other than the open Whatnot live page
* A screenshot or image of the tab
* The full payment card number

## 4. User Data Handling

We handle and use each category as follows.

* **Personally identifiable information.** We use your email, plan, and usage counts to start a trial, recognize a paid subscription, and enforce live-break and Expert Answer limits.
* **Financial and payment information.** ExtensionPay uses your card to bill the subscription. We use only the subscription status it reports to us.
* **Authentication information.** We use the account key to restore your subscription and the session token to authorize API requests.
* **Website content.** We use the visible text to identify the break, retrieve checklists, values, case hits, and odds, and answer chat. We do not use it for advertising. We do not use it to train Blue Luchador LLC models.
* **Web browsing activity.** We use the tab address only to confirm the tab is a Whatnot live page and to identify that live page.
* **Personal communications.** We use your message and the recent break text to produce a reply.
* **User activity and operational data.** We use counts, timestamps, error logs, and IP address to run the service, enforce limits, and investigate failures.
* **Data on your device.** The Extension reads the local account key, preferences, and chat state only to run the current session.

Requests that leave your device are sent to our API over HTTPS.

We do not sell personal data. We do not claim ownership of Whatnot's content. You must follow Whatnot's terms when you use the Extension there.

## 5. User Data Storage

We store each category as follows.

* **Personally identifiable information.** Email, plan, usage counts, and subscription identifiers are stored in Microsoft Azure table storage for as long as your account is active, and for as long as we need them for taxes, billing disputes, or other legal duties.
* **Financial and payment information.** We do not store your full payment card number. ExtensionPay stores payment details under its own policy.
* **Authentication information.** The account key stays in Chrome sync storage until you remove it or uninstall the Extension. The session token stays in memory and is discarded when the session ends.
* **Website content.** Page text is stored in the Extension for the current browser session. A copy is processed on our API to run that session. We do not keep a permanent transcript of page text on your account after the browser is closed.
* **Web browsing activity.** The Whatnot tab address is used to confirm the tab. It is not stored as a browsing history. We do not store the addresses of other sites.
* **Personal communications.** Messages and recent break context are stored in the Extension until the browser restarts. They are not stored as a permanent account transcript after the browser is closed.
* **User activity and operational data.** Usage totals are stored with your account record in Microsoft Azure. Error and performance logs, which can include IP address and the request that failed, are stored in Microsoft Azure for reliability and security monitoring.
* **Data on your device.** The account key and preferences stay in the browser until you remove them or uninstall the Extension. In-session chat state is stored until the browser restarts.

We do not store tab screenshots, because the Extension does not capture them.

## 6. User Data Sharing

We share user data only with the parties named below, and only to operate the Extension. We do not sell user data.

### 6.1 ExtensionPay

ExtensionPay (`extensionpay.com`) receives your email and subscription identifiers to start a trial, log you in, and bill a subscription. ExtensionPay collects your payment card number. We do not receive the full card number.

### 6.2 Microsoft Azure

Microsoft Azure hosts our API, account records, and operational logs. Account data, page text, chat messages, usage records, and logs are processed on Azure over HTTPS.

### 6.3 Azure OpenAI

Azure OpenAI, operated by Microsoft, receives live-break page text and chat messages so it can classify the break and write answers. We do not send your email or payment information to Azure OpenAI.

### 6.4 CardSight

CardSight receives structured break and search details, such as sport, product or release name, and card queries, so we can return checklists and catalog data. We do not send your email, payment information, or the page address to CardSight.

### 6.5 Tavily

Tavily receives a limited search query when a question needs public web information. We do not send your email or payment information to Tavily.

### 6.6 Firecrawl

Firecrawl receives a limited search query when a question needs public web information. We do not send your email or payment information to Firecrawl.

We may also disclose user data if the law requires it, if we need it to investigate abuse, or as part of a merger or sale of Blue Luchador LLC after we tell you.

Each of these parties processes the data under its own privacy policy.

## 7. Data Security

We send user data to our API over HTTPS. Access to backend records is limited to people who operate the service. No system can guarantee absolute security.

## 8. Your Rights

You may request access, correction, or deletion of your personal data by contacting **[support@blueluchador.com](mailto:support@blueluchador.com)**.

## 9. Platform Independence

The Extension is not affiliated with, endorsed by, or sponsored by Whatnot or any other marketplace, livestream platform, grading company, or card manufacturer.

## 10. Changes to This Policy

We may update this Privacy Policy. Continued use of the Extension after an update means you accept the revised policy.

## 11. Contact

Blue Luchador LLC  
Email: **[support@blueluchador.com](mailto:support@blueluchador.com)**

---

Privacy \| [Terms](terms) \| [Refunds](refund-policy) \| [Acceptable Use](acceptable-use) \| [Support](support)
