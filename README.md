# Bac Philo 2026 - Révision Terminale Générale

Site statique de révision pour le Bac de philosophie.

## Structure du projet

- `index.html` — page principale
- `styles.css` — styles du site
- `app.js` — logique JavaScript de navigation et contenu
- `vercel.json` — configuration Vercel pour déploiement statique

## Déploiement sur Vercel

### Option Dashboard
1. Crée un repository sur GitHub / GitLab / Bitbucket.
2. Ajoute ce dépôt local à un remote avec :
   - `git remote add origin <URL_DU_DEPOT>`
3. Pousse sur la branche principale :
   - `git branch -M main`
   - `git push -u origin main`
4. Sur Vercel, clique sur "New Project".
5. Connecte ton compte Git et sélectionne le dépôt.
6. Vérifie que le projet est détecté comme site statique.
7. Déploie.

### Option CLI
1. Installe Vercel :
   - `npm i -g vercel`
2. Lance la commande :
   - `vercel`
3. Suis les étapes et déploie le projet.
