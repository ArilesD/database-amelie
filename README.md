# Ameli - Base de données SQLite

Projet universitaire réalisé en équipe : structuration de données agrégées de l’Assurance maladie dans une base relationnelle.

## Consulter le projet

- [Lire le rapport de conception](Rapport.pdf).
- [Ouvrir le dépôt de l’application Ameli](https://github.com/ArilesD/site-amelie) pour voir les graphiques et lancer le projet. L’application fournit la base complète compressée et la prépare automatiquement.

## Contenu du dépôt

- `dabase.db` : base SQLite d’environ 278 Mo, stockée avec Git LFS.
- `Rapport.pdf` : cahier des charges et conception de la base.

<details>
<summary>Télécharger la base seule avec Git LFS</summary>

### Ouvrir la base

Installe [Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage), puis exécute ces commandes.

```powershell
git lfs install
git clone https://github.com/ArilesD/database-amelie.git
cd database-amelie
git lfs pull
```

Ouvre `dabase.db` dans DBeaver ou un autre client SQLite. Si tu ne disposes que d’un fichier texte de quelques lignes, vérifie le résultat de `git lfs pull` avant de l’ouvrir.

</details>

[Source des données Ameli](https://data.ameli.fr/)
