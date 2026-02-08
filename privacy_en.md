---
layout: default
title: Privacy Policy
permalink: /privacy/en/
---

## Privacy Policy – Rilindra Bot

**Last updated:** February 2026

This policy describes the data collected by the Discord bot Rilindra and how it is used and protected.

---

### 1. Data controller

Data processing is carried out under the responsibility of the ASA Rilindra Discord server administration team. For any questions, contact this team.

---

### 2. Data collected

#### 2.1 Discord account data

| Data | Source | Use |
|------|--------|-----|
| Discord ID | Discord | Unique identification, tribe/economy/auction linking |
| Nickname / display name | Discord | Display in commands and logs |
| Avatar | Discord | Display (optional) |

This data is obtained via the Discord API when you use the bot's commands or interact with it.

#### 2.2 Registration and activity data

- **Tribes**: tribe name, leader ID, member list (Discord IDs), server group (descended/vanilla)
- **Economy**: virtual balance, total earned/spent, transaction history
- **Auctions**: bids, auctions created or won, seller/buyer ID
- **Auction sessions**: progression data when creating an auction (multi-step assistant)

#### 2.3 Activity statistics (optional)

If Firebase is enabled, the bot may record activity statistics for users linked to the Staff Manager webapp:

- Number of messages sent
- Time spent in voice
- Presence status (online, away, etc.)

This data is stored in Firebase/Firestore and shared only with the Staff Manager web application, read-only.

#### 2.4 Administration logs

Administrator actions (adding/removing money, tribe modifications, etc.) are recorded with the administrator ID, target, and action details.

---

### 3. Legal basis and purposes

Processing is based on:

- **Contract performance**: provision of bot services (tribes, auctions, economy)
- **Legitimate interest**: moderation, fraud prevention, server administration

Data is used to:

- Ensure the bot operates correctly
- Manage tribes, auctions, and virtual economy
- Moderate the server and enforce rules
- Generate statistics and rankings (within the service)

---

### 4. Recipients and processors

| Recipient | Data concerned | Location |
|-----------|----------------|----------|
| PostgreSQL (Supabase) | Tribes, economy, auctions, transactions, logs, sessions | Supabase hosting |
| Firebase (Google) | Activity statistics (if enabled) | Google hosting |
| Discord | Data transmitted via Discord API | Per Discord terms |

Data is neither sold nor transferred to third parties for commercial purposes. The administration team and authorized server administrators have access to data necessary for their duties.

---

### 5. Retention period

| Data type | Duration |
|-----------|----------|
| Tribes, economy, auctions, transactions | While you are a server member and data is needed for the service |
| Auction sessions | Until end of session or automatic cleanup |
| Administration logs | Per moderation and traceability needs |
| Firebase statistics | Per configuration (typically: limited retention) |

Data may be retained longer if required by law or a dispute. Upon leaving the server or upon deletion request, personal data is deleted or anonymized within a reasonable technical timeframe, except where legal retention applies.

---

### 6. Your rights (GDPR)

Under the General Data Protection Regulation (GDPR), you have the following rights:

| Right | Description |
|-------|-------------|
| **Access** | Obtain a copy of data concerning you |
| **Rectification** | Have inaccurate or incomplete data corrected |
| **Erasure** | Request deletion of your data |
| **Restriction** | Request restriction of processing in certain cases |
| **Portability** | Receive your data in a structured, commonly used format |
| **Objection** | Object to processing based on legitimate interest |

To exercise these rights: contact the ASA Rilindra Discord server administration team.

You may also lodge a complaint with your supervisory authority if you consider that the processing infringes your rights.

---

### 7. Security

- Database access is restricted and authenticated
- Communications to Supabase and Firebase are encrypted (HTTPS/TLS)
- Daily backups are performed per bot configuration
- Access keys (tokens, service accounts) are not exposed to the public

---

### 8. Transfers outside the EU

Supabase and Firebase may host data in regions outside the European Union. These processors apply appropriate safeguards (standard contractual clauses, certifications) in accordance with the GDPR. For more details, consult their respective privacy policies.

---

### 9. Modifications

This policy may be modified at any time. Significant changes will be communicated to users via the Discord server. Continued use of the bot after modification constitutes acceptance of the updated policy.

---

### 10. Contact

*For any questions regarding this privacy policy or exercising your rights: contact the ASA Rilindra Discord server administration team.*

[MENU](../)
