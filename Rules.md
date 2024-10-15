### Partie principale :

- Créer un site web pour jouer à Pong en ligne
- Utiliser du JavaScript vanilla pour le frontend (sauf si le module Frontend est choisi)
- Utiliser Ruby pur pour le backend (sauf si le module Framework est choisi)
- Application web monopage compatible avec la dernière version stable de Google Chrome
- Tout doit être lancé avec une seule commande Docker
- Permettre aux joueurs de jouer à Pong en direct sur le site
- Implémenter un système de tournoi avec plusieurs joueurs
- Système d'inscription avec alias pour chaque tournoi
- Système d'appariement pour organiser les matchs
- Règles identiques pour tous les joueurs (vitesse de raquette, etc.)
- Développer le jeu selon les contraintes frontend par défaut ou - utiliser le module Graphics
- Stocker les mots de passe de manière hachée
- Protéger contre les injections SQL et XSS
- Utiliser HTTPS pour toutes les connexions
- Valider les formulaires et les entrées utilisateur

### Module Web :

- Utiliser Django comme framework backend
- Utiliser Bootstrap pour le frontend
- Utiliser PostgreSQL comme base de données
- Stocker les scores des tournois sur la blockchain Ethereum avec des smart contracts Solidity

### Module User Management :

- Permettre aux utilisateurs de s'inscrire et se connecter de manière sécurisée
- Implémenter un système d'authentification OAuth 2.0 avec 42
- Gérer les noms d'affichage uniques, les avatars, et les statuts en ligne
- Afficher les statistiques et l'historique des matchs des utilisateurs

### Module Gameplay et expérience utilisateur :

- Permettre le jeu entre joueurs distants
- Implémenter un mode multijoueur (plus de 2 joueurs)
- Ajouter un nouveau jeu avec historique utilisateur et matchmaking
- Offrir des options de personnalisation du jeu
- Créer un chat en direct avec messagerie privée et invitations aux jeux

### Module AI-Algo :

- Développer un adversaire IA sans - utiliser l'algorithme A*
- Créer des tableaux de bord pour les statistiques des utilisateurs et des jeux

### Module Cybersécurité :

- Implémenter WAF/ModSecurity avec une configuration renforcée
- Utiliser HashiCorp Vault pour la gestion des secrets
- Offrir des options de conformité GDPR (anonymisation, gestion des données locales, suppression de compte)
- Implémenter l'authentification à deux facteurs (2FA) et JWT

### Module Devops :

- Mettre en place une infrastructure ELK pour la gestion des logs
- Implémenter un système de surveillance avec Prometheus et Grafana
- Concevoir le backend en microservices

### Module Graphics :

- Utiliser ThreeJS/WebGL pour implémenter des techniques 3D avancées

### Module Accessibilité :

- Assurer la compatibilité sur tous les appareils
- Étendre la compatibilité des navigateurs
- Supporter plusieurs langues (minimum 3)
- Ajouter des fonctionnalités d'accessibilité pour les utilisateurs malvoyants
- Intégrer le rendu côté serveur (SSR)

### Module Server-Side Pong :

- Remplacer le Pong de base par une version côté serveur
- Implémenter une API pour interagir avec le jeu
- Permettre de jouer à Pong via CLI contre des utilisateurs web
