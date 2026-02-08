---
layout: default
title: Privacy Policy / Politique de confidentialité
permalink: /privacy/
---

[🇫🇷 Français](#fr) | [🇬🇧 English](#en)

---

<div id="fr">

## Politique de confidentialité – Bot Rilindra

**Dernière mise à jour :** Février 2026

La présente politique décrit les données collectées par le bot Discord Rilindra et la façon dont elles sont utilisées et protégées.

---

### 1. Responsable du traitement

Le traitement des données est effectué sous la responsabilité de l'équipe d'administration du serveur Discord ASA Rilindra. Pour toute question, contactez cette équipe.

---

### 2. Données collectées

#### 2.1 Données liées à votre compte Discord

| Donnée | Source | Utilisation |
|--------|--------|-------------|
| Identifiant Discord (ID) | Discord | Identification unique, liaison tribu/économie/enchères |
| Pseudonyme / nom d'affichage | Discord | Affichage dans les commandes et logs |
| Avatar | Discord | Affichage (optionnel) |

Ces données sont obtenues via l'API Discord lorsque vous utilisez les commandes du bot ou interagissez avec celui-ci.

#### 2.2 Données d'inscription et d'activité

- **Tribus** : nom de tribu, identifiant du chef, liste des membres (IDs Discord), groupe serveur (descended/vanilla)
- **Économie** : solde virtuel, total gagné/dépensé, historique des transactions
- **Enchères** : mises, enchères créées ou remportées, identifiant vendeur/acheteur
- **Sessions d'enchères** : données de progression lors de la création d'une enchère (assistant multi-étapes)

#### 2.3 Statistiques d'activité (optionnel)

Si Firebase est activé, le bot peut enregistrer des statistiques d'activité pour les utilisateurs liés à la webapp Staff Manager :

- Nombre de messages envoyés
- Temps passé en vocal
- État de présence (en ligne, absent, etc.)

Ces données sont stockées dans Firebase/Firestore et partagées uniquement avec l'application web Staff Manager, en lecture seule.

#### 2.4 Logs d'administration

Les actions des administrateurs (ajout/retrait d'argent, modifications de tribus, etc.) sont enregistrées avec l'identifiant de l'administrateur, la cible et les détails de l'action.

---

### 3. Base légale et finalités

Le traitement repose sur :

- **Exécution du contrat** : fourniture des services du bot (tribus, enchères, économie)
- **Intérêt légitime** : modération, lutte contre la fraude, administration du serveur

Les données sont utilisées pour :

- Assurer le fonctionnement du bot
- Gérer les tribus, enchères et économie virtuelle
- Modérer le serveur et appliquer les règles
- Produire des statistiques et classements (dans le cadre du service)

---

### 4. Destinataires et sous-traitants

| Destinataire | Données concernées | Localisation |
|--------------|-------------------|--------------|
| PostgreSQL (Supabase) | Tribus, économie, enchères, transactions, logs, sessions | Hébergement Supabase |
| Firebase (Google) | Statistiques d'activité (si activé) | Hébergement Google |
| Discord | Données transmises via l'API Discord | Conformément aux conditions Discord |

Les données ne sont ni vendues ni cédées à des tiers à des fins commerciales. L'équipe d'administration et les administrateurs autorisés du serveur ont accès aux données nécessaires à leur mission.

---

### 5. Durée de conservation

| Type de données | Durée |
|-----------------|-------|
| Tribus, économie, enchères, transactions | Tant que vous êtes membre du serveur et que les données sont nécessaires au service |
| Sessions d'enchères | Jusqu'à fin de session ou nettoyage automatique |
| Logs d'administration | Selon les besoins de modération et de traçabilité |
| Statistiques Firebase | Selon configuration (typiquement : conservation limitée) |

Les données peuvent être conservées plus longtemps si une obligation légale ou une contestation l'exige. En cas de départ du serveur ou de demande de suppression, les données personnelles sont supprimées ou anonymisées dans les délais techniques raisonnables, sauf conservation légale.

---

### 6. Vos droits (RGPD)

Conformément au Règlement général sur la protection des données (RGPD), vous disposez des droits suivants :

| Droit | Description |
|-------|-------------|
| **Accès** | Obtenir une copie des données vous concernant |
| **Rectification** | Faire corriger des données inexactes ou incomplètes |
| **Effacement** | Demander la suppression de vos données |
| **Limitation** | Demander la limitation du traitement dans certains cas |
| **Portabilité** | Recevoir vos données dans un format structuré et courant |
| **Opposition** | Vous opposer au traitement fondé sur l'intérêt légitime |

Pour exercer ces droits : contactez l'équipe d'administration du serveur Discord ASA Rilindra.

Vous pouvez également introduire une réclamation auprès de la CNIL (Commission nationale de l'informatique et des libertés) si vous estimez que le traitement porte atteinte à vos droits.

---

### 7. Sécurité

- Les accès à la base de données sont restreints et authentifiés
- Les communications vers Supabase et Firebase sont chiffrées (HTTPS/TLS)
- Les backups quotidiens sont effectués selon la configuration du bot
- Les clés d'accès (tokens, service accounts) ne sont pas exposées au public

---

### 8. Transferts hors UE

Supabase et Firebase peuvent héberger des données dans des régions hors Union européenne. Ces prestataires appliquent des garanties appropriées (clauses types, certifications) conformément au RGPD. Pour plus de détails, consultez leurs politiques de confidentialité respectives.

---

### 9. Modifications

Cette politique peut être modifiée à tout moment. Les changements importants seront portés à la connaissance des utilisateurs via le serveur Discord. La poursuite de l'utilisation du bot après modification vaut acceptation de la politique mise à jour.

---

### 10. Contact

Pour toute question relative à cette politique de confidentialité ou à l'exercice de vos droits : contactez l'équipe d'administration du serveur Discord ASA Rilindra.

</div>

---

<div id="en">

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

For any questions regarding this privacy policy or exercising your rights: contact the ASA Rilindra Discord server administration team.

</div>
