# AHStudio — Docs

> Documentation technique complète d'AHStudio.

## Contenu

- **Architecture** — vue d'ensemble du système
- **API** — endpoints, modèles, exemples de requêtes
- **Guide de contribution** — conventions, workflow Git
- **Décisions techniques** — pourquoi ces choix technologiques
- **Déploiement** — procédures de mise en production

## Structure

```
docs/
├── architecture/      # Schémas et décisions d'architecture
├── api/               # Documentation des endpoints
├── guides/            # Guides de démarrage et contribution
└── deployement/       # Procédures de déploiement
```

## Comment contribuer à la doc

```bash
# Cloner le repo
git clone https://github.com/ahstudio-dev/docs.git
cd docs

# Créer une branche
git checkout -b docs/nom-du-sujet

# Après modifications
git commit -m "docs: description de la modification"
git push origin docs/nom-du-sujet
```

## Convention de commits

```
docs: ajout de la documentation authentification
docs: mise à jour du guide de déploiement
docs: correction des exemples API
```

## Licence

MIT — © 2025 AHStudio.
