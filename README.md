# Gestion des Stocks - Frontend (Angular)

Ce repository contient la **partie frontend** de l'application de **Gestion des Stocks**, développée avec **Angular**. Le frontend fournit une **interface utilisateur moderne et interactive** pour gérer et optimiser les stocks en entrepôt. Il communique avec le backend (Spring Boot) via des **API RESTful** pour afficher et manipuler les données.

---

## 🚀 Fonctionnalités

- **Interface Utilisateur Moderne** : Conçue avec Angular et Angular Material pour une expérience utilisateur fluide.
- **Gestion des Stocks** : Permet d'ajouter, de modifier, de supprimer et de consulter les stocks.
- **Gestion des Produits** : Affiche la liste des produits et permet de les gérer.
- **Gestion des Commandes** : Permet de créer, modifier et suivre les commandes.
- **Responsive Design** : Compatible avec les appareils mobiles et les écrans de bureau.

---

## 🛠️ Technologies Utilisées

- **Framework Frontend** : Angular
- **UI Library** : Angular Material
- **Communication avec le Backend** : API RESTful (Spring Boot)
- **Gestion des États** : RxJS (Observables)
- **Gestion des Formulaires** : Reactive Forms

---

## 📂 Structure du Repository
gestion-stocks-frontend/
├── src/
│ ├── app/
│ │ ├── components/ # Composants Angular (liste, formulaire, etc.)
│ │ ├── services/ # Services pour interagir avec le backend
│ │ ├── models/ # Modèles de données (interfaces TypeScript)
│ │ ├── guards/ # Guards pour la protection des routes
│ │ ├── interceptors/ # Intercepteurs HTTP (optionnel)
│ │ └── app.module.ts # Module principal de l'application
│ ├── assets/ # Ressources statiques (images, styles)
│ ├── environments/ # Configurations pour les environnements (dev, prod)
│ └── styles.scss # Styles globaux
├── angular.json # Configuration d'Angular CLI
├── package.json # Dépendances du projet
├── README.md # Documentation du projet
└── .gitignore # Fichier Git ignore


---

## 🚀 Guide de Démarrage

### Prérequis
- Node.js (v16+)
- Angular CLI (v15+)

### Étapes pour Exécuter le Frontend

1. **Cloner le Repository** :
   ```bash
   git clone https://github.com/SaifeddineBENZAIED/gestion-stocks-frontend.git
   cd gestion-stocks-frontend
Installer les Dépendances :

```bash
npm install
```

Démarrer l'Application :

```bash
ng serve
```

L'application sera disponible à l'adresse http://localhost:4200.

🔍 Fonctionnalités Clés

Interface Utilisateur

- Tableau de Bord : Affiche un aperçu des stocks, des produits et des commandes.

- Formulaire de Gestion : Permet d'ajouter, de modifier et de supprimer des produits et des stocks.

- Liste des Commandes : Affiche les commandes en cours et leur statut.

Communication avec le Backend

- Services Angular : Utilise des services pour interagir avec les API RESTful du backend.

- Gestion des États : Utilise RxJS pour gérer les données de manière réactive.

Responsive Design

- Compatibilité Mobile : L'interface s'adapte aux écrans de différentes tailles.

- Expérience Utilisateur : Conçue pour être intuitive et facile à utiliser.

📫 Contact
Pour toute question ou feedback, n'hésitez pas à me contacter :

- Email : saif2001benz2036@gmail.com
