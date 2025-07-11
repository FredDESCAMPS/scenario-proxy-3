# Scenario Proxy

Proxy Node.js pour interagir avec l'API Scenario.com depuis Make ou Postman.

## Déploiement sur Railway

1. Clique sur "New Project" > "Deploy from GitHub repository".
2. Sélectionne ce dépôt.
3. Ajoute la variable d'environnement `SCENARIO_API_KEY` avec ta vraie clé API Scenario.

## Lancer en local

```bash
npm install
SCENARIO_API_KEY=ta_clé_api_scenario node index.js
```
