# 📧 Contact – API de gestion des contacts avec email


## 📌 Présentation du projet

**API Contact** est une API REST développée avec **Laravel** permettant de gérer des contacts et d’envoyer des emails automatiquement.  
Le projet est testé exclusivement via **Postman**.  
Il permet de comprendre comment fonctionnent les **emails côté serveur**, les **API REST**, et la **communication backend**.

---

## 🎯 Objectifs

- Centraliser la gestion des contacts  
- Automatiser l’envoi d’emails pour notifier les contacts  
- Permettre la recherche et le filtrage par nom ou email  
- Développer une API REST sécurisée et fonctionnelle

---

## 👥 Public cible

### Utilisateurs

- Ajouter, modifier et supprimer des contacts  
- Rechercher des contacts par nom ou email  
- Recevoir automatiquement un email lors de l’ajout

### Administrateurs (optionnel)

- Gérer tous les contacts  
- Envoyer un email manuel à un contact

---

## ⚙️ Fonctionnalités principales

### 🔐 Authentification

- Inscription / Connexion (si nécessaire pour admin)  
- Sécurisation via tokens (**Laravel Sanctum**)

---

### 👤 Gestion des contacts

- Ajouter un contact → envoi automatique d’un email de bienvenue  
- Modifier un contact  
- Supprimer un contact  
- Lister tous les contacts  
- Rechercher par nom ou email

---

### ✉️ Email

- Envoi automatique lors de l’ajout d’un contact  
- Envoi manuel via endpoint dédié  
- Configuration via SMTP (Gmail ou Mailtrap)

## 🧱 Architecture technique

---

### Backend (API)

- **Framework** : Laravel 10+  
- **Base de données** : MySQL  
- **ORM** : Eloquent  
- **Authentification** : Laravel Sanctum (tokens)  
- **Envoi d’emails** : Laravel Mail + Mailable  
- **Architecture** : MVC (API REST)

### Tests

- **Postman** pour tester tous les endpoints  
- **Mailtrap / Gmail** pour visualiser les emails

## 👩‍💻 Réalisé par


**HOUSNA FATHI** - Développeuse web full-stack
