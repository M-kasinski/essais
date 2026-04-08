# Essais

Ce projet est deploye comme site statique simple sur Vercel.

## Structure

- `index.html` sert la page d'accueil a la racine `/`
- pour ajouter une nouvelle page plus tard, cree un nouveau fichier HTML ou un sous-dossier dedie
- exemple:
  - `a-propos/index.html` -> `/a-propos/`
  - `essai-2.html` -> `/essai-2.html`

## Deploiement

- Vercel detecte automatiquement ce projet comme site statique
- aucun build ni framework n'est necessaire
- un nouveau push Git declenche un nouveau deploiement une fois le repo connecte a Vercel
