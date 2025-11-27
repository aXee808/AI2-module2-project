# AI2 Bootcamp - Module 2 projet
## Description Projet
Mettre en œuvre un projet d’intégration de données industrielles. 
Travail attendu : 
- Collecte d’un jeu de données (capteurs ou API). 
- Nettoyage, transformation et stockage. 
- Visualisation finale 

Le choix pour le projet s'est porté sur l'api du Art Institute Of Chicago car l'API ne requiert
pas d'authentification. La documentation de l'API se trouve a l'adresse https://api.artic.edu/docs/.

Extraire l'integralite de la base n'etait pas envisageable dans le cadre du projet. Le notebook  .\jupyter_notebook\project.ipynb
contient le code pour recuperer n fiches d'oeuvres d'art aleatoirement, de garder des "features" interressantes et d'en consolider d'autres a partir de certaines donnees textuelles.

Le pipeline complet est executable a partir du notebook jupyter

## Arborescence

```bash
├── jupyter_notebook
│   ├── project.ipynb               <--- Fichier notebook jupyter comportant tout le code
│   ├── data_in                     <--- Dossier comportant countries.csv (utilé pour la transformation)
│   └── data_out                    <--- Dossier comportant les données générées (fichier csv,base sqlite3)
├── summary_report                  <--- Dossier comportant le rapport 
│   └── rapport_projet_module2.pdf  <--- Rapport de projet
└── README.md                       <--- Présentation courte du projet
```