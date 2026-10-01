# Projet de Fin d'Année - Gestion de Transport

[![CI](https://github.com/ElyasAhm4di/Projet-de-Fin-d-ann-e/actions/workflows/symfony.yml/badge.svg)](https://github.com/ElyasAhm4di/Projet-de-Fin-d-ann-e/actions)

Application web développée dans le cadre d'un projet de fin d'année universitaire. Le système gère un réseau de transport avec une interface de réservation pour les usagers et un panneau d'administration pour la gestion du réseau.

## Fonctionnalités

**Espace Utilisateur :**
- Inscription, connexion et gestion de profil.
- Consultation de la carte interactive du réseau, des lignes, des horaires et des tarifs.
- Réservation de trajets en ligne.

**Espace Administrateur :**
- Tableau de bord récapitulatif.
- Gestion des utilisateurs (CRUD des comptes clients).
- Gestion du réseau (ajout et modification des lignes et trajets).
- Suivi des statistiques d'utilisation et de fréquentation.

## Stack Technique

- Backend : PHP 8 natif (sans framework).
- Frontend : HTML5, CSS3, JavaScript.
- Base de données : MySQL / MariaDB.
- CI/CD : GitHub Actions.

## Architecture

L'application suit une structure modulaire simple :
- `/assets/` : Ressources graphiques (logo, carte).
- `/bdd/` : Fichiers utilitaires, configuration et requêtes SQL (`BddUtils.php`, `LigneUtils.php`, etc.).
- `/css/` et `/js/` : Feuilles de styles et scripts frontend.
- `/includes/` : Composants de page partagés (header, footer, topbar).
- Racine : Pages publiques et d'administration (ex: `index.php`, `admin_dashboard.php`, `reserver.php`).

## Installation locale

1. Cloner le dépôt :
   ```bash
   git clone [https://github.com/ElyasAhm4di/Projet-de-Fin-d-ann-e.git](https://github.com/ElyasAhm4di/Projet-de-Fin-d-ann-e.git)
