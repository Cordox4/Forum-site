# Le Forum — leforum.online

Un forum de discussion simple, sans création de compte, dans un style rétro années 2000.

## Fonctionnalités

- Rubriques prédéfinies + création de rubriques par les visiteurs
- Messages avec pseudo libre (pas de compte)
- Envoi de photos (compressées automatiquement)
- Mise à jour des messages en temps réel
- Barre de recherche pour trouver une rubrique
- Compatible mobile et ordinateur

## Technique

- Une seule page HTML/CSS/JS (`index.html`), aucun framework, aucune installation
- Stockage des données avec **Firebase Firestore** (gratuit, sans carte bancaire nécessaire)
- Hébergé gratuitement avec **GitHub Pages**

## Mise à jour du site

Pour modifier le site, il suffit d'éditer `index.html` directement dans ce repo
(ou en local puis de pousser les changements) — GitHub Pages republie automatiquement
à chaque modification sur la branche principale.

## Règles Firestore

Les règles de sécurité de la base de données sont gérées côté Firebase Console
(Firestore Database → Règles), pas dans ce repo.
