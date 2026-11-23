<p align="center">
  <img src="logo.svg" alt="Logo WebLooping" width="128">
</p>

<h1 align="center">WebLooping</h1>

<p align="center">
  <strong>Dessine ton MCD, obtiens le MLD et le script SQL, directement dans le navigateur.</strong><br>
  Outil de modélisation de bases de données en Merise ou en UML, sans installation.
</p>

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?logo=javascript&logoColor=black">
  <img alt="Sans dépendance" src="https://img.shields.io/badge/d%C3%A9pendances-aucune-success">
</p>

---

## Sommaire

- [Fonctionnalités](#fonctionnalités)
- [Raccourcis clavier](#raccourcis-clavier)
- [Démarrage rapide](#démarrage-rapide)
- [Structure du projet](#structure-du-projet)
- [Confidentialité](#confidentialité)

## Fonctionnalités

### ✏️ Modélisation
- Notation **Merise (MCD)** ou **UML (diagramme de classes)**.
- **Entités**, **associations** (avec propriétés), **cardinalités** (`0,1`, `1,1`, `0,n`, `1,n`), associations **fictives** et identifiants relatifs.
- **Héritage**, **contraintes** entre associations, **règles de gestion**, zones de **texte** et **images**.
- Canevas **zoomable**, aimantation à la grille, **annuler / rétablir**.
- Quatre **thèmes** : classique, pastel, monochrome (pour l'impression) et sombre.

### 🔄 Génération
- **MLD** produit automatiquement à partir du MCD, exportable en `.txt`.
- **Script SQL** pour **MySQL, MariaDB, PostgreSQL, SQLite, SQL Server et Oracle**, pour un SGBD ou pour tous à la fois.

### 💾 Fichiers et export
- Modèle d'**exemple** prêt à explorer.
- **Ouverture / enregistrement** du modèle en `.json`, et sauvegarde automatique dans le navigateur.
- Export de l'image du modèle en **PNG** ou **SVG**, ou copie dans le presse-papiers.

## Raccourcis clavier

| Touche | Outil |
|---|---|
| `V` | Sélection |
| `L` | Lien |
| `E` | Entité |
| `A` | Association |
| `F` | Association fictive |
| `H` | Héritage |
| `C` | Contrainte |
| `R` | Règle de gestion |
| `T` | Texte |
| `I` | Image |
| `Ctrl/⌘ + Z` | Annuler (`+ Maj` pour rétablir) |
| `Ctrl/⌘ + molette` | Zoom |

## Démarrage rapide

Aucune installation : ouvre `index.html` dans un navigateur récent.

Ou sers le dossier en local :

```bash
git clone https://github.com/sami-krm/WebLooping.git
cd WebLooping
python3 -m http.server 8000
```

puis ouvre <http://localhost:8000>.

## Structure du projet

```
.
├── index.html   # structure de la page
├── style.css    # styles
├── script.js    # éditeur, génération du MLD et du SQL
└── logo.svg     # logo et favicon
```

## Confidentialité

Tout fonctionne **dans ton navigateur** : le modèle est enregistré localement (`localStorage`) et rien n'est envoyé à un serveur.

---

<p align="center">Projet de <a href="https://github.com/sami-krm">sami-krm</a>.</p>
