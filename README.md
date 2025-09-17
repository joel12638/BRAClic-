# 🍻 BRAClic - Livraison & Réseau Bralima ma en 1 Clic

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> Une bière, un clic, un revenu

BRAClic est une plateforme innovante qui digitalise la chaîne de distribution des produits Brahma (Primus, Mützig, Coca-Cola, nkoyi etc.) en permettant aux clients de commander en quelques clics, de localiser les dépôts, d'être livrés rapidement, et de devenir des revendeurs indépendants officiels.

## ✨ Fonctionnalités Principales

- **📱 Commande Rapide** - Interface intuitive pour commander vos produits Brahma préférés
- **🚚 Livraison Intelligente** - Géolocalisation et estimation des délais en temps réel
- **🏪 Carte Interactive** - Localisation de tous les dépôts Brahma avec informations détaillées
- **👨‍💼 Espace Revendeur** - Devenez revendeur agréé et suivez vos performances
- **📊 Dashboard Admin** - Outils de gestion avancés pour BRALIMA

## 🛠️ Technologies Utilisées

- **Frontend:** Flutter (Android + iOS)
- **Backend:** Node.js avec Express
- **Base de données:** MongoDB avec Mongoose
- **Géolocalisation:** MapBox API
- **Paiements:** Intégrations Vodacom, Orange, Airtel Money
- **Hébergement:** Firebase Hosting & Functions
- **Notifications:** WhatsApp Business API, SMS

## 🚀 Installation et Déploiement

### Prérequis

- Node.js 16+ et npm
- Flutter SDK 3.0+
- Compte Firebase
- Compte MapBox

### Installation

1. Cloner le repository:
```bash
git clone https://github.com/votre-username/braclic-app.git
cd braclic-app
# Backend
cd backend && npm install

# Frontend
cd ../frontend && flutter pub get
cp backend/.env.example backend/.env
# Remplir les variables d'environnement nécessaires
