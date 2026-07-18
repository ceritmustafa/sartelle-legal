---
title: Privacy Policy
permalink: /privacy/
---

# Sartelle Privacy Policy

**Effective date: 18 July 2026**

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
- **Garment metadata** produced by AI analysis (category, colors,
  attributes) and any edits you make to it.

Wardrobe photos are yours. We process them only to provide the App's
features to you. We do not use your photos to train AI models, we do not
sell them, and we never show them to other users.

### 2.3 Usage and billing data
- **AI usage records** (job type, timestamps, token/cost accounting) kept
  for quota enforcement, abuse prevention and billing integrity.
- **Purchase and subscription state** from Apple In-App Purchase, processed
  through RevenueCat. We never see your card details; payment is handled
  entirely by Apple.

### 2.4 Technical data
- **Logs** containing request identifiers, timestamps, coarse device/app
  version information and error details. Our logging policy forbids
  photographs, tokens and message contents in logs.
- We do **not** collect advertising identifiers and we do **not** use
  third-party advertising or tracking SDKs.

## 3. Why we process your data (legal bases)

| Purpose | Data | Legal basis (GDPR / KVKK) |
| --- | --- | --- |
| Providing sign-in and your account | Account data | Contract performance |
| Digital wardrobe, AI analysis, outfit generation | Wardrobe content | Contract performance |
| Quotas, fraud and abuse prevention | Usage records, logs | Legitimate interest |
| Subscriptions and entitlements | Billing data | Contract performance; legal obligation |
| Security monitoring and audit | Logs, audit records | Legitimate interest; legal obligation |

We do not carry out automated decision-making that produces legal or
similarly significant effects. AI features only produce styling suggestions.

## 4. AI processing

Garment analysis and image generation run on **Microsoft Azure OpenAI
Service** in the **EU (Sweden Central)** region. Under Microsoft's terms,
data submitted to Azure OpenAI is **not** used to train foundation models
and is not shared with OpenAI the company. Our services authenticate to
Azure with managed identities; no long-lived AI keys exist in the App or on
devices.

## 5. Where your data lives

- **Backend and images:** Microsoft Azure, Sweden Central (EU).
- **Authentication:** Supabase (managed Postgres/auth platform) hosting our
  auth records.
- **Billing state:** RevenueCat (subscription status only).
- **Apple:** notarization of purchases and TestFlight/App Store delivery.

Where a provider processes data outside your jurisdiction, transfers rely
on the provider's standard contractual clauses or equivalent safeguards.

## 6. Retention

- Wardrobe content and account data: kept while your account is active.
- Deleted garments and their derivatives: purged from storage by a
  scheduled retention job.
- Account deletion: removes your account data, wardrobe content, and
  derived images; anonymized usage/billing aggregates may be retained where
  required for accounting and abuse prevention.
- Logs: retained for a limited operational window, then deleted.

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
