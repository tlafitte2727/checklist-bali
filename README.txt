CHECKLIST BALI — INSTALLATION iPHONE

Cette version est une PWA (Progressive Web App), c'est-à-dire une mini-app web installable sur l'écran d'accueil de l'iPhone.

IMPORTANT
- Un fichier local ouvert directement depuis l'app Fichiers ne peut pas être installé proprement comme PWA.
- Pour l'utiliser comme une vraie app, les fichiers doivent être hébergés sur un site HTTPS.
- Le plus simple : GitHub Pages, Netlify ou Cloudflare Pages.

INSTALLATION SUR IPHONE
1. Héberger le contenu de ce dossier sur un site HTTPS.
2. Ouvrir l'adresse dans Safari sur l'iPhone.
3. Appuyer sur Partager.
4. Choisir "Ajouter à l'écran d'accueil".
5. Le nom "Checklist Bali" et l'icône seront proposés.
6. Ouvrir ensuite l'app depuis l'écran d'accueil.

DONNÉES
Les cases cochées et les notes sont sauvegardées localement sur l'iPhone.
Elles restent disponibles hors connexion après la première ouverture.
Elles ne sont pas synchronisées entre plusieurs appareils dans cette version.

FICHIERS
- index.html : interface et checklist
- manifest.webmanifest : nom/icône/comportement app
- sw.js : fonctionnement hors connexion
- icons/ : icônes iPhone/PWA
