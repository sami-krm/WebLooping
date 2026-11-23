# WebLooping

Outil web de modélisation de bases de données : dessinez un **MCD / diagramme UML**, obtenez le **MLD** et générez le **script SQL** correspondant.

Tout tourne dans le navigateur : pas de serveur, pas de dépendance, pas d'installation.

## Fonctionnalités

- Création d'un modèle (entités, associations) sur un canevas zoomable
- Chargement d'un modèle d'exemple
- Ouverture / enregistrement du modèle au format `.json`
- Export de l'image du modèle en **PNG** ou **SVG**, ou copie dans le presse-papiers
- Génération du **MLD** (export `.txt`)
- Génération du **script SQL** pour MySQL, MariaDB, PostgreSQL, SQLite, SQL Server et Oracle (un SGBD ou tous à la fois)

## Utilisation

Ouvrez `index.html` dans un navigateur récent.

Ou servez le dossier localement :

```bash
python3 -m http.server 8000
```

puis allez sur <http://localhost:8000>.

## Structure

```
.
├── index.html   # structure de la page
├── style.css    # styles
└── script.js    # logique de l'application
```
