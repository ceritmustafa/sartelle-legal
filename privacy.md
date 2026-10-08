---
title: Privacy Policy
permalink: /privacy/
---

# Sartelle Privacy Policy

**Effective date: 8 October 2026 — policy version 2026-10-08**

Sartelle ("the App", "we", "us") is an AI personal stylist and digital
wardrobe application operated by Mustafa Cerit ("the Operator"). This policy
explains what personal data we process, why, where, and what rights you have.
It applies to the Sartelle mobile application and its backend services.

If you do not agree with this policy, please do not use the App.

## 1. Who is responsible

The data controller is the Operator, reachable at
**mustafa@mustafacerit.com**. For users in Türkiye, this policy also serves
as the information notice under the Personal Data Protection Law No. 6698
(KVKK). For users in the European Economic Area and the United Kingdom, the
GDPR / UK GDPR applies.

## 2. Data we collect

### 2.1 Account data
- **Sign-in identity.** We support Sign in with Apple and Google Sign-In
  only. We receive a unique identifier and, subject to your choice at
  sign-in, your name and email address (Apple lets you hide your email; we
  fully support relay addresses). We never receive your Apple or Google
  password.
- **Locale and preferences** you set in the App (for example language,
  onboarding answers, style preferences).

### 2.2 Wardrobe content
- **Photos you upload** of your garments, and derivative images we generate
  from them (background-removed cutouts, previews, outfit renders).
- **Portrait and full-body reference photographs** you choose to provide for virtual try-on, and the try-on images generated from them. These remain private to your account.
- **Garment metadata** produced by AI analysis (category, colors,
  attributes) and any edits you make to it.

Wardrobe photos are yours. We process them only to provide the App's
features to you. We do not use your photos to train AI models, we do not
sell them, and we never show them to other users.

### 2.3 Optional context and conversations
- **Stylist messages and saved conversation history**, with the wardrobe items and preferences selected for a styling request. You can delete conversations from the history screen; clearing only the local chat view is not necessarily deletion of server history.
- **Fit preferences and self-reported measurements** (silhouette, height and weight) you optionally enter. With your fit permission, these help the proportions of a try-on. We do not infer health diagnoses or score your body. Withdrawing fit permission removes stored fit fields.
- **Calendar context:** when you connect your calendar, Sartelle reads titles and times for the week you are planning. With AI permission, selected event context is sent for classification. Sartelle does not edit your calendar or keep an event-history database; derived outfit plans may be saved in your account.
- **Approximate location:** only when you enable weather, approximate coordinates are sent for a forecast through Apple WeatherKit. Sartelle does not continuously track you. Forecast results may be temporarily cached; operational request logs are retained for a limited period.

### 2.4 Usage and billing data
- **AI usage records** (job type, timestamps, token/cost accounting) kept
  for quota enforcement, abuse prevention and billing integrity.
- **Purchase and subscription state** from Apple In-App Purchase, processed
  through RevenueCat. RevenueCat also processes your app user identifier and paywall interactions (such as impressions, selections and purchase/restore outcomes) for subscription functionality and product analytics. These are not used for cross-company advertising tracking. We never see your card details; payment is handled
  entirely by Apple.

### 2.5 Technical data
- **Logs** containing request identifiers, timestamps, coarse device/app
  version information and error details. Our logging policy forbids
  photographs, tokens and message contents in logs.
- We do **not** collect advertising identifiers and we do **not** use
  third-party advertising or tracking SDKs.

## 3. Why we process your data (legal bases)

| Purpose | Data | Legal basis (GDPR / KVKK) |
| --- | --- | --- |
| Providing sign-in and your account | Account data | Contract performance |
| Digital wardrobe and saved content | Wardrobe content and conversations | Contract performance |
| AI processing, optional fit and calendar context | The selected content and optional context | Explicit in-app permission; applicable contractual/legal basis |
| Subscription/paywall product analytics | User identifier, purchase state, paywall interactions | Legitimate interest where applicable; no advertising tracking |
| Quotas, fraud and abuse prevention | Usage records, logs | Legitimate interest |
| Subscriptions and entitlements | Billing data | Contract performance; legal obligation |
| Security monitoring and audit | Logs, audit records | Legitimate interest; legal obligation |

We do not carry out automated decision-making that produces legal or
similarly significant effects. AI features only produce styling suggestions.

## 4. AI processing and permission

Sartelle uses **Microsoft Azure OpenAI** for garment analysis, catalog cutouts,
stylist answers, calendar-context classification and virtual try-on. Only the
content needed for a chosen request is sent: the relevant garment photographs,
selected outfit items and preferences, the stylist message, and — with the
related permissions — reference photographs, fit details or calendar context.

**Storage and AI processing are different.** Sartelle's wardrobe database and
image storage are hosted in Azure Sweden Central. The current AI deployments
use **Global Standard**: prompts, photographs and responses may be processed in
other Azure regions where Microsoft makes the model available. Storage in
Sweden does not mean every AI request is processed only in Sweden or the EU.
Authentication and billing providers have their own hosting arrangements.

Microsoft states that customer prompts and responses for these Azure models
are not used to train foundation models and are not shared with OpenAI, the
company. Sartelle does not use your photographs or conversations to train AI
models. Provider safety filtering and abuse monitoring remain subject to
Microsoft's data-processing terms; this policy does not promise zero provider
retention. See [Microsoft's data-processing explanation](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy)
and [deployment geography](https://learn.microsoft.com/en-us/azure/foundry/foundry-models/concepts/deployment-types).

AI permissions are separate from Apple camera/calendar/notification permissions
and from buying a plan. They can be reviewed or withdrawn in **Privacy & data →
Permissions**. Manual garment entry and organization remain available without
AI. Reference-photo and fit permissions are separate choices. Existing users
are asked to review the clarified AI notice rather than automatically treating
an older permission as acceptance of the current notice.

## 5. Where your data lives

- **Backend and images:** Microsoft Azure, Sweden Central (EU).
- **Authentication:** Supabase (managed Postgres/auth platform) hosting our
  auth records.
- **Subscriptions and product analytics:** RevenueCat processes app user identifiers, purchase/subscription state and paywall interactions. Apple processes payment; we do not receive payment-card data.
- **Weather:** Apple WeatherKit receives the approximate coordinates needed for a requested forecast.
- **Apple:** notarization of purchases and TestFlight/App Store delivery.

Where a provider processes data outside your jurisdiction, transfers rely
on the provider's standard contractual clauses or equivalent safeguards.

## 6. Retention

- Wardrobe content, reference photos, saved conversations and account data: kept while your account is active or until you use the relevant deletion control.
- Fit fields: removed when fit permission is withdrawn. Calendar titles/times used for classification are not kept as a calendar history.
- AI permissions: recorded with the policy version and decision time so we can respect your choices.
- Deleted garments and their derivatives: purged from storage by a
  scheduled retention job.
- Account deletion: removes your account data, wardrobe content, and
  derived images; anonymized usage/billing aggregates may be retained where
  required for accounting and abuse prevention.
- Logs: retained for a limited operational window, then deleted. Provider abuse-monitoring retention is governed by the provider terms linked above.
- Deleting the Sartelle account does not cancel an Apple subscription. The app warns active subscribers and offers Apple subscription management before deletion; immediate account deletion remains available.

## 7. Your rights

You can, at any time, from within the App:

- **Export your data** (a machine-readable snapshot of your account and
  wardrobe metadata) — Settings → Privacy → Export.
- **Delete your account and data** — Settings → Privacy → Delete account.

You also have the right to access, rectify, restrict, object, and lodge a
complaint with your supervisory authority (in Türkiye: KVKK Kurumu; in the
EEA: your national data protection authority). Contact us at
**mustafa@mustafacerit.com** for any request; we respond within 30 days.

## 8. Security

- Transport encryption (TLS) everywhere; storage encrypted at rest.
- Row-level security in the database: each account can only reach its own
  rows.
- Zero-trust service credentials: managed identities instead of shared
  keys wherever the platform supports it; no AI or storage credentials are
  ever embedded in the mobile app.
- Administrative access is limited to named, individually authenticated
  operators, and every administrative action is written to an audit log.

## 9. Children

Sartelle is not directed at children under 13 (or the higher minimum age in
your jurisdiction, e.g. 16 where applicable in the EEA). We do not
knowingly collect data from children; if you believe a child has created an
account, contact us and we will delete it.

## 10. Changes

We will post any changes to this policy in this repository and update the
effective date. Material changes will additionally be announced in the App
before they take effect.

## 11. Contact

**mustafa@mustafacerit.com**
