# Privacy Policy

**Effective date: April 18, 2026**

## Introduction

Café Cal is a nutrition and meal tracking app that helps you log meals, monitor nutrition, track exercise, and stay on top of your health goals. Your privacy matters to us. This policy explains how we handle your information and the steps we take to keep it safe.

## Information We Collect

When you use Café Cal, we collect the following types of information to provide and improve our meal tracking experience.

### Account Information

When you create an account — whether through email/password, Apple Sign-In, or Google Sign-In — we collect your **name**, **email address**, **account creation date**, and **onboarding status**. This information is managed through Firebase Authentication.

### Meal & Nutrition Data

To help you track your diet, we collect the **food items** you log along with their nutritional details, including calories, protein, carbs, fats, sugar, fiber, and sodium. If you choose to attach photos — such as **meal photos** or **leftover photos** — we store those as well.

### Health & Fitness Data

Café Cal collects health-related data you provide, including:

- **Weight history** and **water intake**
- **Food quality scores**
- **Exercise entries** (type, duration, and calories burned)

With your permission, we also read data from **Apple HealthKit**, such as steps, active calories, walking/running distance, heart rate, and flights climbed. HealthKit data is never shared with third parties or used for advertising.

## Android Health Connect

With your permission, Café Cal connects to Android Health Connect:

- **Read** — your steps and active calories burned. We read today's totals to
  show your daily activity and calculate your calorie balance, and up to 30 days
  of step history to power your trends and analytics.
- **Write** — when you log a meal, we write it to Health Connect as a nutrition
  record (calories and macros), and beverages as a hydration record, so your
  Café Cal logs stay in sync with your other health apps.

Health Connect data is processed only on your device to power these in-app
nutrition and activity features. It is never shared with third parties, sold,
or used for advertising, and we do not transmit your Health Connect data to our
servers.

You can grant or revoke Health Connect access at any time in the Health Connect
app (Settings > Apps > Health Connect, or the standalone Health Connect app).
To delete data Café Cal has written, remove it in Health Connect or delete your
account and all associated data from Settings within the app.

### Daily Logs & Analytics

We generate **aggregated daily and weekly summaries** based on your logged data, including nutrition analytics and **streak tracking**, to help you monitor your progress over time.

### Voice Input

If you use voice-to-text to describe a meal, audio is processed using Apple's Speech Recognition framework. We prefer on-device transcription whenever the device and selected language support it (most English locales, German, French, Spanish, etc.). For languages where on-device recognition is not yet available — including some Indian-language locales such as Hindi and Tamil — Apple processes the audio on its servers under Apple's own privacy policy. We never receive or store the raw audio.

### Usage Data

We use **Firebase Analytics** to collect anonymous usage events — such as logins, signups, meal logging, exercise logging, and deletions. This helps us understand how the app is used and where we can make improvements. This data is not tied to your nutritional or health information.

## How We Use Your Information

We use the information we collect to:

- **Provide core features** — Log your meals, track nutrition and exercise, record weight history, and calculate daily/weekly analytics and streaks.
- **Analyze meals with AI** — When you submit a photo or text description, it is sent to our servers (Firebase Cloud Functions) and processed using the Gemini API to estimate nutritional content. Photos are transmitted solely for analysis and are not stored long-term.
- **Sync with Apple HealthKit** — With your permission, we read and write health data (steps, active calories, distance, heart rate, and flights climbed) to keep your fitness picture complete. This data is never sold or used for advertising.
- **Improve the app** — Firebase Analytics helps us understand how features are used so we can make Café Cal better. We do not build advertising profiles from this data.
- **Manage your account** — Authenticate your identity, maintain your preferences, and handle subscription billing.
- **Send notifications** — Deliver reminders, streak updates, and important account or subscription alerts you have opted into.

We process your data only as needed to deliver and improve the features described above. We do not sell your personal information to third parties.

## Data Storage & Sharing

**Where your data lives.** Your meals, nutrition logs, and account information are stored securely in Firebase Firestore, hosted on Google Cloud. Photos you upload are compressed and stored in Firebase Storage.

**AI meal analysis.** When you use the photo analysis feature, your image is sent to Google's Gemini API through our secure server — your device never communicates directly with the AI service. Photos are processed for analysis and are not retained afterward.

**Authentication.** We use Firebase Auth along with Google Sign-In and Apple Sign-In to manage your account. We only receive basic profile information (name, email) from these providers.

**We do not sell your data.** Period. Your personal information and meal data are never sold to third parties.

**Third-party services we rely on:**

- **Firebase** (Auth, Firestore, Storage, Analytics, Cloud Functions) — infrastructure and app analytics
- **Firebase Crashlytics** — collects crash reports and basic diagnostic data (device model, OS version, app version) to help us fix bugs. Reports are tagged with your Firebase user ID so we can correlate crashes with the affected account during incident triage. No personal content (meals, photos, emails, names) is included.
- **Google Sign-In / Apple Sign-In** — account authentication
- **Google Gemini API** — AI-powered meal analysis (server-side only)
- **Firebase App Check** — verifies that requests come from the genuine Café Cal app

These services have their own privacy policies and may process data as described in their respective terms. We share only the minimum information each service needs to function.

**Business transfers.** If Café Cal is acquired or merged with another company, your data may be transferred as part of that transaction. We will notify you before your data becomes subject to a different privacy policy.

## Your Rights & Choices

You have control over your data in Café Cal. Here is what you can do:

- **Delete your account:** You can delete your account and all associated data at any time from Settings within the app.
- **HealthKit permissions:** You can grant or revoke HealthKit access anytime through iOS Settings > Privacy & Security > Health.
- **Analytics:** You can opt out of analytics collection in the app's Settings.
- **Notifications:** You can manage notification preferences in the app or through iOS Settings.
- **Device permissions:** You can manage app permissions (Camera, Photos, Notifications) anytime in iOS Settings > Café Cal.
- **Sign-in access:** You can revoke Google or Apple sign-in access through your Google Account or Apple ID settings at any time.
- **Request your data:** You can request a copy of your data in a structured format (such as CSV or JSON) by contacting us at the email listed below.

### For Users in the EU/EEA and California

Under the GDPR and CCPA, you have the right to:

- **Access** the personal data we hold about you
- **Correct** inaccurate or incomplete data
- **Delete** your personal data
- **Port** your data in a commonly used, machine-readable format

To exercise any of these rights, please contact us using the information in the "Contact Us" section.

## Children's Privacy

Café Cal is not intended for children under the age of 13. We do not knowingly collect personal information from children. If we learn that we have inadvertently gathered data from a child under 13, we will take steps to delete it promptly. If you believe a child has provided us with personal information, please contact us so we can address it.

## Changes to This Policy

We may update this privacy policy from time to time. When we do, we will notify you through the app. Your continued use of Café Cal after any changes means you accept the updated policy. We encourage you to review this page periodically.

## Contact Us

If you have questions or concerns about this privacy policy, reach out to us at:

**inandha97@gmail.com**
