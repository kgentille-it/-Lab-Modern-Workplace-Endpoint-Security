# 🛡️ Modern Workplace & Sécurité Cloud (Intune / Entra ID)

## 📋 Présentation du Projet
Ce projet simule la transition d'un parc informatique traditionnel vers une gestion moderne **Cloud Native**. L'objectif est de sécuriser les accès et les données d'une organisation en déployant une infrastructure basée sur la suite **Microsoft 365 Business Premium**.

---

## 🛠️ Stack Technique
* **Gestion des Identités :** Microsoft Entra ID (Azure AD)
* **Gestion des Terminaux (MDM) :** Microsoft Intune
* **Sécurité :** Chiffrement BitLocker, MFA, Accès Conditionnel
* **Environnement :** VMware Workstation, Windows 10/11 Professionnel

---

## 🚀 Réalisations Clés

### 1. Gouvernance et Identités
* **Structuration de l'annuaire :** Création de groupes de sécurité ciblés (`GRP-SEC-ADMINS`, `COMMERCIAUX`, `FINANCE`).
* **Stratégie de licences :** Attribution et gestion des licences Microsoft 365 Business Premium.

### 2. Sécurisation "Zero Trust"
* **Accès Conditionnel :** Mise en place de politiques de Multi-Factor Authentication (MFA).
* **Géofencing :** Restriction des accès basée sur la localisation géographique (blocage des connexions hors zone autorisée).

### 3. Gestion de la Conformité (MDM)
* **Enrôlement automatique :** Configuration de la portée utilisateur GPM (MDM User Scope).
* **Protection des données :** Déploiement de stratégies de chiffrement **BitLocker** avec sauvegarde centralisée des clés de récupération dans le Cloud.
