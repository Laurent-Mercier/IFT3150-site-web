# Site web pour IFT3150

Le site web à jour pour mon projet AntiHook est diposible [ici](https://laurent-mercier.github.io/IFT3150-site-web/).

Ce projet est un site web pour le cours IFT3150, construit avec [MkDocs](https://www.mkdocs.org/) et le thème [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Prérequis

Assurez-vous d’avoir les outils suivants installés :

- Python **3.8** ou plus récent
- `pip` (gestionnaire de paquets Python)

## Installation

1. Clonez ce dépôt :
```bash
git clone git@github.com:udem-diro/template-projet.git
cd ift3150-template
```

2. Installez les dépendances :
```bash
pip install -r requirements.txt
```

## Utilisation

### Développement local

Pour lancer un serveur de développement local :

```bash
mkdocs serve
```

Le site sera accessible à l'adresse [http://127.0.0.1:8000](http://127.0.0.1:8000)

### Construction du site

Pour construire le site :

```bash
mkdocs build
```

Les fichiers générés seront dans le dossier `site/`.

### Déploiement

Pour déployer sur GitHub Pages :

```bash
mkdocs gh-deploy
```

> Cette commande pousse automatiquement le contenu du site sur la branche gh-pages.

## Structure du projet

- `docs/` : Contient tous les fichiers Markdown du site
- `mkdocs.yml` : Configuration de MkDocs
- `requirements.txt` : Dépendances Python
- `site/` : Site généré (créé lors de la construction)

## Personnalisation

1. Modifiez `mkdocs.yml` pour changer la configuration du site
2. Ajoutez/modifiez les fichiers Markdown (`.md`) dans `docs/`
3. Personnalisez le thème en modifiant les paramètres dans `mkdocs.yml`

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
