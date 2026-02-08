---
layout: default
title: Politique de confidentialité
permalink: /privacy/
---

# Politique de confidentialité – Bot Rilindra

**Dernière mise à jour :** Février 2026

La présente politique décrit les données collectées par le bot Discord Rilindra et la façon dont elles sont utilisées et protégées.

---

## 1. Responsable du traitement

Le traitement des données est effectué sous la responsabilité de l'équipe d'administration du serveur Discord ASA Rilindra. Pour toute question, contactez cette équipe.

---

## 2. Données collectées

### 2.1 Données liées à votre compte Discord

| Donnée | Source | Utilisation |
|--------|--------|-------------|
| Identifiant Discord (ID) | Discord | Identification unique, liaison tribu/économie/enchères |
| Pseudonyme / nom d'affichage | Discord | Affichage dans les commandes et logs |
| Avatar | Discord | Affichage (optionnel) |

Ces données sont obtenues via l'API Discord lorsque vous utilisez les commandes du bot ou interagissez avec celui-ci.

### 2.2 Données d'inscription et d'activité

- **Tribus** : nom de tribu, identifiant du chef, liste des membres (IDs Discord), groupe serveur (descended/vanilla)
- **Économie** : solde virtuel, total gagné/dépensé, historique des transactions
- **Enchères** : mises, enchères créées ou remportées, identifiant vendeur/acheteur
- **Sessions d'enchères** : données de progression lors de la création d'une enchère (assistant multi-étapes)

### 2.3 Statistiques d'activité (optionnel)

Si Firebase est activé, le bot peut enregistrer des statistiques d'activité pour les utilisateurs liés à la webapp Staff Manager :

- Nombre de messages envoyés
- Temps passé en vocal
- État de présence (en ligne, absent, etc.)

Ces données sont stockées dans Firebase/Firestore et partagées uniquement avec l'application web Staff Manager, en lecture seule.

### 2.4 Logs d'administration

Les actions des administrateurs (ajout/retrait d'argent, modifications de tribus, etc.) sont enregistrées avec l'identifiant de l'administrateur, la cible et les détails de l'action.

---

## 3. Base légale et finalités

Le traitement repose sur :

- **Exécution du contrat** : fourniture des services du bot (tribus, enchères, économie)
- **Intérêt légitime** : modération, lutte contre la fraude, administration du serveur

Les données sont utilisées pour :

- Assurer le fonctionnement du bot
- Gérer les tribus, enchères et économie virtuelle
- Modérer le serveur et appliquer les règles
- Produire des statistiques et classements (dans le cadre du service)

---

## 4. Destinataires et sous-traitants

| Destinataire | Données concernées | Localisation |
|--------------|-------------------|--------------|
| PostgreSQL (Supabase) | Tribus, économie, enchères, transactions, logs, sessions | Hébergement Supabase |
| Firebase (Google) | Statistiques d'activité (si activé) | Hébergement Google |
| Discord | Données transmises via l'API Discord | Conformément aux conditions Discord |

Les données ne sont ni vendues ni cédées à des tiers à des fins commerciales. L'équipe d'administration et les administrateurs autorisés du serveur ont accès aux données nécessaires à leur mission.

---

## 5. Durée de conservation

| Type de données | Durée |
|-----------------|-------|
| Tribus, économie, enchères, transactions | Tant que vous êtes membre du serveur et que les données sont nécessaires au service |
| Sessions d'enchères | Jusqu'à fin de session ou nettoyage automatique |
| Logs d'administration | Selon les besoins de modération et de traçabilité |
| Statistiques Firebase | Selon configuration (typiquement : conservation limitée) |

Les données peuvent être conservées plus longtemps si une obligation légale ou une contestation l'exige. En cas de départ du serveur ou de demande de suppression, les données personnelles sont supprimées ou anonymisées dans les délais techniques raisonnables, sauf conservation légale.

---

## 6. Vos droits (RGPD)

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

## 7. Sécurité

- Les accès à la base de données sont restreints et authentifiés
- Les communications vers Supabase et Firebase sont chiffrées (HTTPS/TLS)
- Les backups quotidiens sont effectués selon la configuration du bot
- Les clés d'accès (tokens, service accounts) ne sont pas exposées au public

---

## 8. Transferts hors UE

Supabase et Firebase peuvent héberger des données dans des régions hors Union européenne. Ces prestataires appliquent des garanties appropriées (clauses types, certifications) conformément au RGPD. Pour plus de détails, consultez leurs politiques de confidentialité respectives.

---

## 9. Modifications

Cette politique peut être modifiée à tout moment. Les changements importants seront portés à la connaissance des utilisateurs via le serveur Discord. La poursuite de l'utilisation du bot après modification vaut acceptation de la politique mise à jour.

---

## 10. Contact

Pour toute question relative à cette politique de confidentialité ou à l'exercice de vos droits : contactez l'équipe d'administration du serveur Discord ASA Rilindra.
