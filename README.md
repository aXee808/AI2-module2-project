# AI2 Bootcamp - Module 2 projet
## Description Projet
Mettre en œuvre un projet d’intégration de données industrielles. 
Travail attendu : 
- Collecte d’un jeu de données (capteurs ou API). 
- Nettoyage, transformation et stockage. 
- Visualisation finale 

Le choix pour le projet s'est porté sur l'api du Art Institute Of Chicago car l'API ne requiert
pas d'authentification. La documentation de l'API se trouve à l'adresse https://api.artic.edu/docs/#iiif-image-api.

Extraire l'intégralité de la base n'était pas envisageable dans le cadre du projet. Le notebook  .\jupyter_notebook\project.ipynb
contient le code pour récupérer n fiches d'oeuvres d'art aléatoirement, de garder des "features" interressantes et d'en consolider d'autres à partir de certaines données textuelles.

## Arborescence

```bash
├── jupyter_notebook
│   ├── project.ipynb           <--- Fichier notebook jupyter comportant tout le code
│   └── data                    <--- Dossier comportant tous les fichiers générés (fichier csv,base sqlite3)
├── summary_report              <--- Dossier comportant le rapport 
│   └── ....
└── README.md                   <--- Présentation du projet
```