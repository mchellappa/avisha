# Privacy Policy for KalviPal

**Last Updated:** February 21, 2026

---

## Introduction

KalviPal ("we," "our," or "us") is committed to protecting the privacy of children and their families. This Privacy Policy explains how we collect, use, and protect information when you use our educational mobile application.

KalviPal is designed for children ages 3-15 and complies with the Children's Online Privacy Protection Act (COPPA) and other applicable privacy laws.

**Important:** Our app uses automatic background sync (enabled by default) to download new educational content and backup learning progress to secure cloud storage. You can disable this at any time in Settings. See "How We Store Information" below for details.

---

## Information We Collect

### Personal Information
We collect the following information:

#### **Kid Profiles**
- Child's name (first name only)
- Age or age range (3-5, 6-9, 10-12, 13-15)
- Avatar selection (no photos)

#### **Account Information (Parent/Guardian)**
- Email address (for account creation)
- Account credentials (handled securely by Firebase Authentication)

#### **Learning Progress**
- Lessons completed
- Quiz scores and answers
- Time spent on activities
- Progress through educational content

#### **Parent-Uploaded Videos (Grandma's Corner)**
- Parents/guardians can upload videos for their children
- Videos are stored locally on the device only
- Videos are only accessible within that family's account on that device
- Parents/guardians can delete videos at any time

### Automatically Collected Information
- Device type and operating system
- Device ID (for sync tracking)
- App version
- Session duration
- Error logs and crash reports (anonymized)

### Information We Do NOT Collect
- ❌ Full names or surnames
- ❌ Photos of children for profile creation
- ✅ Videos may be uploaded by parents/guardians in Grandma's Corner and remain local to the device
- ❌ Location data
- ❌ Contact information for children
- ❌ Social security numbers
- ❌ Payment information (app is free)

---

## How We Use Information

We use collected information for the following purposes:

1. **Educational Progress:** Track learning progress and completion
2. **App Functionality:** Save user preferences and profiles
3. **Content Delivery:** Download new lessons and educational content to your device
4. **Progress Backup:** Automatically backup learning progress to cloud (when enabled)
5. **Cross-Device Sync:** Enable progress sync across multiple devices (when enabled)
6. **Family Content Storage:** Store parent-uploaded Grandma's Corner videos locally on your device
7. **Improvement:** Improve app features and user experience
8. **Support:** Provide customer support when needed

---

## How We Store Information

### Local Storage (SQLite)
- All learning data is stored **locally** on your device using SQLite database
- The app works fully offline using local storage

### Cloud Storage (Supabase - Automatic Background Sync)

**Automatic Sync is ENABLED by default** and runs in the background:

#### **What Gets Synced:**

**Downloaded to Your Device (Automatic):**
- New educational lessons and content from our servers
- Lesson updates and improvements
- Syncs every 24 hours when internet is available

**Uploaded from Your Device (Automatic):**
- Child's learning progress (lessons completed, scores, time spent)
- Kid profile ID and lesson IDs
- Device ID for sync tracking
- Completion timestamps
- Only syncs when you're logged in with an authenticated account

#### **What is NOT Synced:**
- Grandma's Corner parent-uploaded videos are never uploaded to cloud servers
- Videos are never included in automatic background sync
- Videos remain stored locally on your device only

#### **How Sync Works:**
- Checks for updates every 24 hours automatically
- Runs in the background when app is opened
- Requires internet connection
- **You can disable automatic sync at any time** in Settings
- All data is encrypted in transit (HTTPS/TLS)
- Data is stored in secure cloud servers (Supabase)

#### **Disabling Sync:**
- Go to Settings → Disable "Auto-sync"
- App continues to work fully offline
- No data will be uploaded or downloaded
- Existing local data remains on your device

### Authentication (Firebase)
- Account authentication is handled by Google Firebase
- Credentials are encrypted and securely managed
- We do not store passwords directly

---

## Data Sharing and Disclosure

We **DO NOT** sell, trade, or rent your child's information to third parties.

### Third-Party Services We Use

#### **Firebase Authentication** (Google)
- Purpose: Secure user login
- Privacy Policy: https://firebase.google.com/support/privacy

#### **Supabase** (Cloud Database)
- Purpose: Automatic background sync for lessons and learning progress (enabled by default)
- What's synced: New lessons downloaded, progress uploaded (scores, completion, time spent)
- Frequency: Every 24 hours automatically
- Can be disabled: Yes, in app Settings
- Privacy Policy: https://supabase.com/privacy

### When We May Disclose Information
We may disclose information only in the following limited circumstances:
- With parental consent
- To comply with legal obligations (court orders, subpoenas)
- To protect the safety of children or others
- To trusted service providers who help operate the app (under strict confidentiality)

---

## Parental Rights (COPPA Compliance)

As a parent or legal guardian, you have the right to:

1. **Review** the personal information collected from your child
2. **Delete** your child's profile and data at any time
3. **Refuse** further collection of your child's information
4. **Disable** cloud sync features

### How to Exercise Your Rights

To review, delete, or manage your child's information:
- **In-App:** Go to Settings → Kid Profile → Delete Profile
- **Email Us:** muthuc@credgesolutions.com
- **Response Time:** We will respond within 48 hours

---

## Data Retention

- **Active Accounts:** We retain data while your account is active
- **Deleted Profiles:** Data is permanently deleted within 30 days of deletion request
- **Inactive Accounts:** Accounts inactive for 2+ years may be automatically deleted

---

## Security Measures

We implement industry-standard security measures:

- ✅ Encryption in transit (HTTPS/TLS)
- ✅ Secure authentication (Firebase)
- ✅ Regular security audits
- ✅ Access controls and authentication
- ✅ Local-first data storage

However, no method of electronic storage is 100% secure. We cannot guarantee absolute security.

---

## Children's Privacy

KalviPal is designed specifically for children and complies with COPPA requirements:

- We collect minimal information necessary for app functionality
- We require verifiable parental consent for children under 13
- We do not enable public profiles or social features
- We do not display behavioral advertising to children
- We do not share children's information with third parties for marketing

---

## Your Choices

### Automatic Cloud Sync
- Automatic sync is **ENABLED by default**
- Runs in the background every 24 hours
- Downloads new lessons automatically
- Uploads learning progress automatically (requires login)
- **Disable at any time** in Settings → "Auto-sync"
- App works fully offline when sync is disabled
- No data uploaded/downloaded when sync is disabled

### Account Deletion
- Delete kid profiles individually or entire account
- All data is permanently removed
- Request deletion via Settings or email

### Marketing Communications
- We do not send marketing emails
- We send only essential account-related communications
- You can opt out of non-essential emails

---

## International Users

KalviPal is operated from the United States. If you access the app from outside the United States, your information may be transferred to, stored, and processed in the United States or other countries where our service providers operate.

By using the app, you consent to this transfer.

### GDPR Rights (European Users)
If you are in the European Economic Area (EEA), you have additional rights:
- Right to access your data
- Right to rectification
- Right to erasure
- Right to data portability
- Right to object to processing

Contact us at muthuc@credgesolutions.com to exercise these rights.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. When we do:
- We will update the "Last Updated" date
- We will notify you via in-app notification
- For material changes, we will request renewed consent

Continued use of the app after changes indicates acceptance of the updated policy.

---

## Contact Us

If you have questions or concerns about this Privacy Policy or our data practices:

**Email:** muthuc@credgesolutions.com  
**Website:** https://credgesolutions.com  
**Mailing Address:**  
Credge Solutions  
Shrewsbury, MA  
United States

**Response Time:** We aim to respond within 48 hours.

---

## Third-Party Links

KalviPal does not contain links to third-party websites or services. All content is self-contained within the app.

---

## Cookies and Tracking

KalviPal does not use cookies or tracking technologies for advertising purposes. We use only essential session management for authentication.

---

## Your California Privacy Rights

California residents have additional rights under the California Consumer Privacy Act (CCPA):
- Right to know what personal information is collected
- Right to delete personal information
- Right to opt-out of sale (we do not sell information)

Contact us to exercise these rights.

---

## Consent

By using KalviPal:
- Parents/guardians consent to collection as described
- Parents confirm they have authority to consent for their child
- Parents can withdraw consent at any time by deleting the account

---

**KalviPal** - Educational Learning for Kids  
Version 1.0.0  
© 2026 Credge Solutions. All rights reserved.
