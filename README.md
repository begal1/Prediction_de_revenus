# "Effectuez une prédiction de revenus" - Parcours Data Analyst - OpenClassrooms

Le but du projet est de créer un modèle pour déterminer le revenu potentiel d'une personne.  

Jeu de données:  

* country_code.csv: Liste des codes pays ISO3-3166 Alpha-3  
* data-projet7.csv: données de la World Income Distribution sur les revenus par quantile par pays et année  
* gdim.csv: données de la World Income Distribution sur les coefficients de mobilité intergénérationnelle de revenus  
* gini: données de la banque mondiale sur les indices de Gini par pays et année  
* population: données de la banque mondiale sur le nombre d'habitants par pays  

A partir du jeu de données dans le fichier downloaded_csv, le script "Partie1_P7.ipynb" va:  
-Repérer et remplacer les valeurs manquantes par des données les plus cohérentes possibles  
-Afficher des représentations graphiques des revenus et des indices de Gini  
-Attribuer une classe de revenus parents en fonction des revenus d'une personne, selon une loi Normale, et grâce au coefficient d'élasticité.  
-Créer un fichier analyse.csv  

A partir du fichier analyse.csv, le script "Partie2_P7.ipynb" va:  
-Effectuer différentes modélisations.  
-Analyser la pertinance de ces modèles.  


Il s'agit de fichiers jupyter notebook.  
Les scripts principaux utilisent des fonctions stockées dans deux fichiers:
-functions1.py pour le script 1
-functions2.py pour le script 2

  ---------------------------------------- Projet en cours d'évaluation ----------------------------------------  

### Environnement  

Jupyter 6.0.2 - Python 3.8.1 - Conda 4.8.0  
Pandas 0.25.3 - Numpy 0.25.3 - Seaborn 0.9.0 - Statsmodels 0.10.2 - Matplotlib 3.1.2 - Scipy 1.4.0  


## Auteur  

* **Alain Béguin**  

En cours de formation à la Data Analyse depuis le 01 septembre 2018  

## Remerciements  

* “GDIM. 2018. Global Database on Intergenerational Mobility.  
  Development Research Group, World Bank. Washington, D.C.: World Bank Group.”  

"Narayan, Ambar; Van der Weide, Roy; Cojocaru, Alexandru; Lakner,  
Christoph; Redaelli, Silvia; Mahler, Daniel Gerszon; Ramasubbaiah, Rakesh Gupta N.; Thewissen, Stefan."  
"2018. Fair Progress? : Economic Mobility Across Generations Around the World. Equity and Development."  
Washington, DC: World Bank. https://openknowledge.worldbank.org/handle/10986/28428  

* Benjamin Marlé, mentors OC  
* Ricco Rakotomalala de l'université de Lyon, pour ses cours disponible librement en version pdf  

*A tous ceux qui mettent en lignes des ressources de grandes qualités *  

## Date  

17 Janvier 2020 - Tourcoing  
