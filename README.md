# 📚 Projet de Système de Gestion de Bibliothèque Municipale  
*(Library Management System Project)*  

---

## 👥 Auteurs / Authors  
- POINT Yvon  
- GAREA Jeannette  
- MOHAMED AMINE Jilani  

---

## 📖 Description du projet (FR)  

Nous sommes chargés de concevoir un système de gestion pour une **bibliothèque municipale** souhaitant informatiser ses activités :  
- Catalogage  
- Consultations  
- Gestion des utilisateurs  
- Prêts et retours  

La bibliothèque propose un large choix de ressources : **livres, films et enregistrements musicaux**.  

Chaque ressource, quel que soit son type, est caractérisée par :  
- Un code unique  
- Un titre  
- Une liste de contributeurs  
- Une date d’apparition  
- Un éditeur  
- Un genre  
- Un code de classification (pour la localisation dans la bibliothèque)  

Des informations spécifiques s’ajoutent selon le type de ressource :  
- **Livre** : ISBN, résumé, langue  
- **Film** : réalisateurs, acteurs, durée, langue, synopsis  
- **Œuvre musicale** : compositeurs, interprètes, durée  

Chaque ressource peut exister en plusieurs exemplaires, avec un état : *neuf, bon, abîmé ou perdu*.  

### Gestion des utilisateurs  
- **Personnel** : compte utilisateur (login/mot de passe), accès aux fonctions d’administration.  
- **Adhérents** : compte utilisateur + carte d’adhérent, permettant l’emprunt. Caractéristiques : nom, prénom, date de naissance, adresse, email, téléphone.  

### Gestion des prêts  
- Un emprunt est lié à une **date** et une **durée**.  
- Un document doit être disponible et en bon état.  
- Limitation du nombre d’emprunts simultanés.  
- **Sanctions** : retards, détérioration ou perte. Retards → suspension proportionnelle au retard. Perte → suspension jusqu’au remboursement.  
- Possibilité de **blacklister** un adhérent en cas d’abus répétés.  

### Besoins fonctionnels  
- Recherche de documents et gestion des emprunts pour les adhérents.  
- Gestion des ressources documentaires (ajout, modification, exemplaires).  
- Gestion des prêts, retards et réservations pour le personnel.  
- Gestion des utilisateurs et de leurs données.  
- Génération de **statistiques** : documents populaires, profils d’adhérents, recommandations.  

### Choix d’architecture  
L’architecture du projet est guidée par :  
- Les besoins fonctionnels  
- Les contraintes techniques  
- Les objectifs de long terme : **évolutivité, performance, maintenabilité**  

---

## 📖 Project Description (EN)  

We are tasked with designing a **management system** for a municipal library that wants to digitize its activities:  
- Cataloging  
- Consultations  
- User management  
- Loans and returns  

The library offers a wide range of resources: **books, movies, and music recordings**.  

Each resource, regardless of its type, has:  
- A unique code  
- A title  
- A list of contributors  
- A publication/release date  
- A publisher  
- A genre  
- A classification code (to locate it within the library)  

Additional information is required depending on the resource type:  
- **Book**: ISBN, summary, language  
- **Film**: directors, actors, duration, language, synopsis  
- **Musical work**: composers, performers, duration  

Resources can exist in multiple copies, each with a state: *new, good, damaged, or lost*.  

### User Management  
- **Staff**: user account (login/password), access to administration features.  
- **Members**: user account + membership card, allowing borrowing. Characteristics: name, surname, date of birth, address, email, phone number.  

### Loan Management  
- A loan has a **date** and a **duration**.  
- A document must be available and in good condition.  
- Maximum number of simultaneous loans is limited.  
- **Penalties**: late returns, deterioration, or loss. Late → suspension equal to the number of delayed days. Loss → suspension until reimbursement.  
- The library can **blacklist** a member in case of repeated sanctions.  

### Functional Requirements  
- Make it easier for members to search for documents and manage their loans.  
- Simplify library resource management (add/edit documents, add copies).  
- Help staff manage loans, late returns, and reservations.  
- Manage users and their data.  
- Provide **statistics**: popular documents, user profiles, personalized recommendations.  

### Architecture Choice  
The project’s architecture depends on:  
- Functional requirements  
- Technical constraints  
- Long-term objectives: **scalability, performance, maintainability**  

---

