# Guide de lancement de projet MkDocs

Ce guide démontre comment configurer et lancer un projet de documentation utilisant MkDocs avec Python. [Voir la demo en ligne](https://13vlxx.github.io/mkdocs-md/ "Voir la démo")

## Prérequis

- Python 3.6+
- Git
- Pip (gestionnaire de paquets Python)

## Installation

### 1. Récupérer le projet

Clonez le dépôt sur votre machine :

```bash
git clone https://github.com/13vlxx/mkdocs-md
cd MkDocsGuide
```

### 2. Créer et activer l'environnement virtuel

```bash
# Création de l'environnement Python isolé
python3 -m venv venv

# Activation de l'environnement
# Sur Linux/macOS :
source venv/bin/activate
# Sur Windows :
# venv\Scripts\activate
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

## Utilisation

### Lancement du serveur de développement

Pour visualiser la documentation en temps réel :

```bash
mkdocs serve
```

La documentation est alors accessible dans votre navigateur à l'adresse : [http://127.0.0.1:8000](http://127.0.0.1:8000)

### Autres commandes utiles

- Générer le site statique : `mkdocs build`
- Déployer sur GitHub Pages : `mkdocs gh-deploy`
- Afficher l'aide : `mkdocs --help`

## Ressources

- [Documentation officielle MkDocs](https://www.mkdocs.org/)
- [Guide des extensions recommandées](https://www.mkdocs.org/user-guide/plugins/)
- [Personnalisation des thèmes](https://www.mkdocs.org/user-guide/styling-your-docs/)
