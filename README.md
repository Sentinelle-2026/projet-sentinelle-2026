# SENTINELLE CI

Plateforme nationale de surveillance environnementale multi-secteurs (mines, pétrole, industrie) — Côte d'Ivoire.

Projet réalisé par **Équipe Sentinelle** dans le cadre du **Hackathon SIREXE 2026**.

## Aperçu

SENTINELLE CI est une application web (fichier unique, aucune installation nécessaire) qui centralise le suivi environnemental des sites industriels, miniers et pétroliers : cartographie des sites, indicateurs de conformité, alertes, cadastre, jumeau numérique, et un module dédié **CARBON CONNECT CI** pour le suivi carbone par entreprise avec cloisonnement de confidentialité entre structures.

## Utilisation en ligne (GitHub Pages)

Une fois ce dépôt publié avec GitHub Pages activé (voir réglages du dépôt → *Pages*), l'application est accessible directement depuis un navigateur, sans backend ni base de données — tout fonctionne côté client.

## Utilisation locale

Il suffit d'ouvrir `index.html` dans un navigateur pour lancer la plateforme, sans serveur requis.

## Structure du dépôt

- `index.html` — l'application complète (SENTINELLE + module CARBON CONNECT CI intégré)
- `manifest.json`, `sw.js` — configuration Progressive Web App (installation sur écran d'accueil, usage hors-ligne du shell applicatif)
- `icon-*.png`, `apple-touch-icon.png`, `favicon-32.png` — icônes de l'application
- `LICENSE` — droits d'utilisation

## Licence

Voir le fichier `LICENSE` — tous droits réservés à l'Équipe Sentinelle.
