# Privacy Policy

**Last Updated:** September 28, 2026

This Privacy Policy describes how **Decoy — Live Break Assistant** ("we", "us", or "our") collects, uses, handles, stores, and shares information when you use the Decoy Chrome Extension ("Extension").

> **Important:** Use of Decoy is subject to our **[Terms of Service](terms)**. By installing or using the Extension, you agree to those Terms.

The Extension helps collectors follow live card breaks on supported livestream auction sites. While a live-break session is open, it reads visible listing and livestream text on that page and uses it to retrieve checklists, values, case hits, odds, and chat answers.

**Limited Use Disclosure:** Use of information received from Google APIs will adhere to the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/policies), including the **Limited Use** requirements. We do not sell user data, use it for advertising, or use it to determine creditworthiness.

## User data collection

We collect the following user data, and only what the Extension needs to run.

**Account and subscription data.** If you start a trial or subscribe, we collect your email address, subscription or trial plan, remaining usage (live breaks and Expert Answers), and the subscription identifiers from our payment processor. The payment processor collects your payment card number. We do not receive or collect the full card number.

**Live-break page text and page address.** When a live-break session is open on a supported livestream auction site, we collect the visible text on that page, such as the lineup, listings, and livestream details. We also collect the address of that tab, so the Extension can confirm the tab is a supported live-break page. Collection happens when the session starts and again while the session stays open. It does not run on other websites. Closing the Extension or leaving the session stops it. Visible text can include other words on that page, such as a chat overlay or a username.

**Chat and assistant messages.** When you use Decoy chat, we collect the messages you send, the replies generated for you, and the recent break text needed to answer.

**Usage and operational data.** We collect the number of live breaks and Expert Answers used, subscription or trial status, request timestamps, and error and performance logs. Hosting diagnostics can include your IP address.

**Data stored on your device.** The Extension collects and keeps, on your device, a payment-processor account key used to restore your subscription, theme and similar preferences, and in-session live-break chat state.

We do not collect your full browsing history, keystrokes, private messages from other sites (except text visible on the supported live page during a session), page contents from other sites, or a screenshot of the tab.

## User data handling

We handle and use each category of collected data as follows.

**Account and subscription data.** We use your email, plan, and usage counts to start a trial, recognize a paid subscription, and enforce live-break and Expert Answer limits. Requests that carry this data are sent to our API over HTTPS.

**Live-break page text and page address.** We use the visible text to identify the break. We use the page address to confirm the tab is a supported live-break page. The text is sent to our API over HTTPS. We use it to classify the break, retrieve checklists, values, case hits, and odds, and answer chat. We do not use it for advertising, and we do not use it to train Blue Luchador LLC models.

**Chat and assistant messages.** We use your message and the recent break text to produce a reply. That content is sent to our API over HTTPS and then to the model that writes the answer.

**Usage and operational data.** We use counts, timestamps, error logs, and IP address to run the service, enforce limits, and investigate failures.

**Data on your device.** The Extension reads the local account key to restore your subscription and reads local preferences to apply them. Chat state on the device is used only to continue the current browser session.

We do not sell personal data. We do not claim ownership of third-party platform content. You must follow the terms of any site you use with the Extension.

## User data storage

We store each category of collected data as follows.

**Account and subscription data.** Email, plan, usage counts, and subscription identifiers are stored in Microsoft Azure table storage for as long as your account is active, and for as long as we need them for taxes, billing disputes, or other legal duties. We do not store your full payment card number.

**Live-break page text and page address.** Page text is stored in the Extension for the current browser session so the assistant can follow the break. A copy is processed on our API to run that session. We do not keep a permanent transcript of page text on your account after the browser is closed. The page address is used to confirm the tab and is not stored as a browsing history.

**Chat and assistant messages.** Messages and recent break context are stored in the Extension until the browser restarts. They are not stored as a permanent account transcript after the browser is closed.

**Usage and operational data.** Usage totals are stored with your account record in Microsoft Azure. Error and performance logs, which can include IP address and the request that failed, are stored in Microsoft Azure for reliability and security monitoring.

**Data on your device.** The account key and preferences stay in the browser until you remove them or uninstall the Extension. In-session chat state is stored until the browser restarts.

We do not store tab screenshots, because the Extension does not capture them.

## User data sharing

We share user data only with the parties named below, and only to operate the Extension. We do not sell user data.

**ExtensionPay** receives your email and subscription identifiers to start a trial, log you in, and bill a subscription. ExtensionPay collects your payment card number. We do not receive the full card number.

**Microsoft Azure** hosts our API, account records, and operational logs. Account data, page text, chat messages, usage records, and logs are processed on Azure over HTTPS.

**Azure OpenAI**, operated by Microsoft, receives live-break page text and chat messages so it can classify the break and write answers. We do not send your email or payment information to Azure OpenAI.

**CardSight** receives structured break and search details, such as sport, product or release name, and card queries, so we can return checklists and catalog data. We do not send your email, payment information, or the page address to CardSight.

**Tavily** receives a limited search query when a question needs public web information. We do not send your email or payment information to Tavily.

**Firecrawl** receives a limited search query when a question needs public web information. We do not send your email or payment information to Firecrawl.

Each of these parties processes the data under its own privacy policy.

## Data security

We send user data to our API over HTTPS. Access to backend records is limited to people who operate the service. No system can guarantee absolute security.

## Your rights

You may request access, correction, or deletion of your personal data by contacting **[support@blueluchador.com](mailto:support@blueluchador.com)**.

## Platform independence

The Extension is not affiliated with, endorsed by, or sponsored by any marketplace, livestream platform, grading company, or card manufacturer.

## Changes to this policy

We may update this Privacy Policy. Continued use of the Extension after an update means you accept the revised policy.

## Contact

Blue Luchador LLC  
Email: **[support@blueluchador.com](mailto:support@blueluchador.com)**

---

Privacy \| [Terms](terms) \| [Refunds](refund-policy) \| [Acceptable Use](acceptable-use) \| [Support](support)
