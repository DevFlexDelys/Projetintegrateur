# API RESTful - Boutique en ligne (Projet intégrateur)

## Description
Cette API permet de gérer une boutique en ligne avec les fonctionnalités suivantes :
- Authentification des utilisateurs (avec token)
- Gestion des utilisateurs, produits, commandes
- Journalisation des erreurs
- Base de données MySQL

## Fonctionnalités de l'API
- CRUD utilisateurs, produits, commandes
- Authentification via JWT ou token simple
- Routes RESTful
- Fichier de log d'erreurs

## Instructions

### 1. Exécuter le serveur (avec PHP)
```bash
php -S localhost:8000 -t public
```

### 2. Initialiser la base de données
Importer le fichier `database/init.sql` dans votre MySQL local.

### 3. Tester les routes
Utilisez Postman et chargez la collection fournie dans `/postman/test_collection.json`
