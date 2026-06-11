# Bac Philo 2026 - Révision Terminale Générale

Site statique de révision pour le Bac de philosophie.

## Structure du projet

- `index.html` — page principale
- `styles.css` — styles du site
- `app.js` — logique JavaScript de navigation et contenu
- `vercel.json` — configuration Vercel pour déploiement statique
- `LICENSE.md` — licence MIT

## Déploiement sur GitHub

Ce dépôt est connecté à : `https://github.com/Aloyss59/philo.git`

### Commandes locales utilisées

```bash
git init
git add .
git commit -m "Initial commit: site statique Bac Philo 2026"
git branch -M main
git remote add origin https://github.com/Aloyss59/philo.git
git push -u origin main
```

## Déploiement sur Vercel

### Option Dashboard
1. Va sur https://vercel.com
2. Clique sur "New Project"
3. Choisis GitHub, puis autorise l’accès si nécessaire
4. Sélectionne le dépôt `Aloyss59/philo`
5. Vérifie que le projet est détecté comme site statique
6. Clique sur "Deploy"

### Option CLI
1. Installe Vercel :
   - `npm i -g vercel`
2. Lance :
   - `vercel`
3. Suis les instructions pour déployer le projet.
