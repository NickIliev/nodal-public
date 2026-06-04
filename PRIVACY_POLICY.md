# Nodal — Privacy Policy

**Effective date:** 4 June 2026
**App:** Nodal (`com.funspot.nodal.app`)
**Contact:** iliev.nick007@gmail.com

> **Note for the developer (delete before publishing):** This is an accurate, engineering-derived draft reflecting what the app actually does as of build 34. It is **not legal advice** — because Nodal collects **birth date/time/place** (which can be considered sensitive in some jurisdictions), have it reviewed before relying on it, and tailor the GDPR/CCPA wording to where you ship. Host the published version at a public HTTPS URL (e.g. GitHub Pages) and paste that URL into Play Console → Store presence → App content → Privacy policy.

---

Nodal is an astrology app. To produce a birth chart and readings it needs your birth details, and to sync them across devices it stores them in the cloud. This policy explains what we collect, why, who processes it, and how you can get it back or delete it.

## Who we are

Nodal is operated by the developer reachable at **iliev.nick007@gmail.com**. For users in the EU/UK, that developer is the data controller for the personal data described below.

## What we collect

We only collect what the app needs to function. We do **not** run advertising, behavioural analytics, or device-location tracking.

**You provide:**
- **Birth details** — birth date, birth time (optional), and birth place (city, country, and its latitude, longitude, and timezone). These are the core inputs used to compute your chart, transits, and readings. Your birth *place* is a city you type in — we do **not** read your device's GPS location.
- **Account email** — only if you create an account with email/password or sign in with Google. If you never sign in, you remain an anonymous user with no email on file.
- **Screen name** — an optional display name you choose.
- **Saved people** — if you add other people for compatibility, their name and birth details that you enter. You are responsible for having a basis to add another person's details.
- **Ask conversations** — for Pro users, the questions you type and the AI's replies are stored so you can revisit them.
- **App settings** — notification preferences, appearance/density, and similar choices.

**Created automatically:**
- **A user identifier** — a Firebase user ID assigned to your session (random for anonymous users; tied to your login once you sign in).
- **Subscription status** — whether you have an active Pro subscription or promotional grant, and related purchase history, handled through RevenueCat and Google Play.

## How we use it

- To compute and display your chart, transits, daily readings, themes, and compatibility.
- To sync your data across your devices when you sign in.
- To power the optional Pro **Ask** and **Pro-insight** AI features (see below).
- To manage subscriptions and promotional access.
- To send the local notifications you enable (these are scheduled on your device).

We do not sell your personal data, and we do not use it for advertising or behavioural profiling.

## AI features (Ask & Pro-insight) — important

When a Pro user uses **Ask** or receives a **Pro-insight** enrichment, the app's secure server sends the following to **Anthropic** (the provider of the Claude models) to generate a response:
- a summary of your natal chart (placements, current transits), and
- for Ask, the text of your question.

This text is processed by Anthropic to produce the reply. We do not send your name, email, or precise birth place coordinates for this purpose beyond what's in the chart summary. Per Anthropic's commercial API terms, API inputs and outputs are not used to train their models. Free users do not trigger these features.

## Who processes your data (sub-processors)

We use trusted providers to run the service. Each only receives what it needs:
- **Google Firebase** (Authentication, Cloud Firestore database, Cloud Functions) — stores your account, birth data, saved people, settings, and conversations, and runs our secure server logic. Operated by Google.
- **RevenueCat** — manages subscriptions; receives your app user identifier and purchase/entitlement status.
- **Google Play Billing** — processes purchases and trials.
- **Anthropic** — receives the chart summary and question text described above to power the AI features.

Data is transmitted over encrypted (HTTPS/TLS) connections.

## Data retention

We keep your data until you remove it. Specifically:
- You can **edit or delete** individual items (birth data, saved people) in the app at any time.
- You can **delete your entire account** in **Profile → Delete account**. This erases your data from our database and removes your authentication record. Conversations and saved people are deleted with it.
- Anonymous (not-signed-in) data is stored under your random user ID until you delete the app's data or your account.

## Your rights

- **Access / portability:** **Profile → Manage my data → export** produces a JSON copy of your data.
- **Deletion:** **Profile → Delete account** (above).
- **Correction:** edit your birth data, screen name, and saved people in the app.

Depending on where you live (e.g. EEA/UK under GDPR, California under CCPA/CPRA), you may have additional rights to access, correct, delete, or restrict processing, and to lodge a complaint with your local data-protection authority. To exercise any right, use the in-app tools above or email **iliev.nick007@gmail.com**. Our legal bases (GDPR) are: performance of the service you request (computing and syncing your chart), your consent (optional features like notifications and AI), and our legitimate interest in operating and securing the app.

## Children

Nodal is not directed to children under 13 (or the minimum age in your country), and we do not knowingly collect their data. If you believe a child has provided data, contact us and we will delete it.

## International transfers

Your data may be processed on servers (Google Cloud / our sub-processors) located outside your country, including the United States. Where required, transfers rely on appropriate safeguards such as Standard Contractual Clauses.

## Security

We rely on Firebase's managed infrastructure, encrypted connections, and security rules that restrict each user's data to their own account. No system is perfectly secure, but we work to protect your information and limit access to what the service requires.

## Changes to this policy

We may update this policy as the app evolves. We'll change the effective date above and, for material changes, surface a notice in the app.

## Contact

Questions or requests: **iliev.nick007@gmail.com**.
