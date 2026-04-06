# Projet E-commerce Django

## Description
Ce projet est une application e-commerce développée avec Django 6.0.3. Il utilise PostgreSQL comme base de données et est conçu pour gérer des produits.

## Configuration Actuelle

### Technologies Utilisées
- **Framework** : Django 6.0.3
- **Base de données** : PostgreSQL
- **Langage** : Python
- **Serveur** : Python (développement)

### Applications Django Installées
- `django.contrib.admin` - Interface d'administration Django
- `django.contrib.auth` - Système d'authentification
- `django.contrib.contenttypes` - Framework de types de contenu
- `django.contrib.sessions` - Gestion des sessions utilisateur
- `django.contrib.messages` - Système de messages
- `django.contrib.staticfiles` - Gestion des fichiers statiques
- `products` - Application personnalisée pour gérer les produits

### Base de Données
- **Type** : PostgreSQL
- **Nom** : `db_ecommerce`
- **Host** : localhost
- **Port** : 5432

### Structure du Projet
```
ecommerce_project/
├── ecommerce/
│   ├── manage.py
│   ├── ecommerce/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── wsgi.py
│   │   └── asgi.py
│   ├── products/
│   │   ├── models.py
│   │   ├── views.py
│   │   ├── urls.py
│   │   └── admin.py
│   └── images/
└── README.md
```

## Étapes Suivantes
- Développer les modèles dans l'application `products`
- Créer les vues et templates
- Configurer les URLs
- Ajouter les migrations de base de données

## Installation et Configuration
Pour démarrer le projet localement :
1. Installer les dépendances
2. Configurer PostgreSQL
3. Exécuter les migrations : `python manage.py migrate`
4. Créer un superutilisateur : `python manage.py createsuperuser`
5. Lancer le serveur : `python manage.py runserver`

## Auteur
MOUSSAOU Ismail