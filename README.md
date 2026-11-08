# Ameli - Base de données SQLite

Projet universitaire réalisé en équipe. L’objectif était de structurer des données agrégées de l’Assurance maladie dans une base relationnelle. Le [rapport du projet](Rapport.pdf) présente le cahier des charges et la conception de la base.

## Contenu du dépôt

- `dabase.db` contient la base SQLite du projet. Le fichier d’environ 278 Mo est stocké avec Git LFS.
- `Rapport.pdf` contient le rapport de conception.

## Ouvrir la base

Installe [Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage), puis exécute ces commandes.

```bash
git lfs install
git clone https://github.com/ArilesD/database-amelie.git
cd database-amelie
git lfs pull
```

Ouvre `dabase.db` dans DBeaver ou un autre client SQLite. Si tu ne disposes que d’un fichier texte de quelques lignes, vérifie le résultat de `git lfs pull` avant de l’ouvrir.

Pour consulter les données via Flask et voir les graphiques, utilise le [guide de l’application web Ameli](https://github.com/ArilesD/site-amelie). L’application fournit sa propre version de la base dans son archive d’origine.

[Source des données Ameli](https://data.ameli.fr/)
