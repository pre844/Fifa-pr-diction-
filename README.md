# FIFA Virtual Prediction Bot

Ce projet est une application web simple qui prédit le résultat d’un match FIFA virtuel entre deux équipes. Il utilise Python (Flask) pour l'API backend et HTML/CSS/JavaScript pour l'interface frontend.

## Fonctionnalités

- Choix de deux équipes (ex : PSG, Chelsea, Manchester City)
- Prédiction basée sur une évaluation simple des équipes
- API REST accessible via `/predict`

## Déploiement

### 1. Backend (Flask) sur Render
- Crée un compte sur [Render.com](https://render.com)
- Connecte ton dépôt GitHub
- Build command : `pip install -r requirements.txt`
- Start command : `python app.py`

### 2. Frontend sur Netlify
- Va sur [https://netlify.com](https://netlify.com)
- Clique sur "Deploy site" puis uploade `index.html`
- Modifie l'URL dans `index.html` pour pointer vers ton backend Render

## Structure du projet
