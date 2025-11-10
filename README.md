# 📅 Solution de Gestion des Évènements

## 📝 Description du Projet

Ce projet est une **solution informatique complète** visant à améliorer l’efficacité et la fluidité de la **gestion des évènements** au sein de la **Commune de Laâyoune**.  

Il a été conçu pour **automatiser** les processus d’organisation, de suivi et de coordination des évènements, auparavant **complexes, chronophages et sujets à des erreurs** dues à la gestion manuelle.  

L’application permet aux **administrateurs**, **gestionnaires** et **utilisateurs** d’interagir efficacement au sein d’une plateforme intuitive et performante.

---

## 🛠️ Technologies Utilisées

| Catégorie | Technologie | Rôle dans le Projet |
|------------|--------------|--------------------|
| **Base de Données** | MongoDB | Base NoSQL orientée document, offrant flexibilité, scalabilité et hautes performances. |
| **Frontend / Backend** | Next.js | Framework basé sur React, permettant le rendu côté serveur (SSR) et la génération statique pour des performances optimisées. |
| **Styling** | Tailwind CSS | Framework CSS utility-first, facilitant un développement rapide et réactif. |
| **Authentification** | Firebase Auth | Authentification sécurisée avec intégration facile de fournisseurs externes (Google, Facebook). |
| **Gestion d’État** | Redux Toolkit | Centralisation et simplification de la gestion de l’état global de l’application. |
| **UX / UI** | SweetAlert2 | Alertes, modales et confirmations modernes et personnalisables. |
| **IDE** | Visual Studio Code | Environnement de développement complet avec intégration Git et extensions riches. |

---

## 🚀 Fonctionnalités Clés

### 👨‍💼 Espace Administrateur / Gestionnaire
- Authentification par nom d’utilisateur et mot de passe.  
- **Gestion des Évènements :** création, modification et suppression.  
- **Gestion des Gestionnaires :** ajout, modification et suppression de comptes.  
- **Gestion des Partenaires :** administration des entités externes collaborant avec la commune.

### 👥 Espace Utilisateur
- **Authentification simplifiée :** via Google, Facebook ou manuellement.  
- **Consultation :** accès à la liste des évènements et à leurs détails.  
- **Inscription :** possibilité de s’inscrire à un ou plusieurs évènements après connexion.

---

## 💻 Installation et Lancement

### ✅ Prérequis

Assurez-vous d’avoir installé :
- [Node.js](https://nodejs.org/) (version 18 ou supérieure)
- npm ou yarn
- Un serveur **MongoDB** (local ou distant)

---

### ⚙️ Étapes d’Installation

#### 1️⃣ Cloner le dépôt
```bash
git clone [https://github.com/YOUCEF54/Event-Management]
cd [Event_Management]
```

#### 2️⃣ Installer les dépendances
```bash
npm install
# ou
yarn install
```

#### 3️⃣ Configurer les variables d’environnement
Créez un fichier **.env.local** à la racine du projet avec les informations suivantes :

```bash
MONGODB_URI=mongodb+srv://user:password@clustername/event_db
NEXTAUTH_URL=http://localhost:3000
FIREBASE_API_KEY=VOTRE_CLE_FIREBASE
FIREBASE_AUTH_DOMAIN=VOTRE_DOMAINE_FIREBASE
FIREBASE_PROJECT_ID=VOTRE_ID_FIREBASE
FIREBASE_STORAGE_BUCKET=VOTRE_BUCKET
FIREBASE_MESSAGING_SENDER_ID=VOTRE_SENDER_ID
FIREBASE_APP_ID=VOTRE_APP_ID
```

#### 4️⃣ Lancer le serveur de développement
```bash
npm run dev
# ou
yarn dev
```

L’application sera accessible à l’adresse :  
👉 [http://localhost:3000](http://localhost:3000)

---

## 🧑‍💻 Auteur

**Youssef El Omari**  
🎓 Réalisé dans le cadre d’un **stage de Brevet de Technicien Supérieur (BTS)** en **Développement des Systèmes d’Information**  
📍 **Commune de Laâyoune**

---

## 📜 Licence

Ce projet est libre d’utilisation à des fins éducatives et de démonstration.  

---
