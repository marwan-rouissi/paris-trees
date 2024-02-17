# paris-trees

## Contexte du Projet 

Inspiré du challenge proposé par l'association "Data For Good" et sponsorisé par la ville de Paris.
Le but est d'aider Paris à devenir une smart-city en réalisant une analyse exploratoire des données sur les arbres de la ville de Paris.

## Contenu du projet :
- Un fichier jupyter notebook : `EDA.ipynb`
    - 
    Analyse exploratoire du jeu de données `p2-arbres-fr.csv` fournit pour le bon déroulement du projet.
- Un fichier Power BI : `paris-trees.pbix`
    - 
    Dashboard contenant différents types de visualisations permettant l'exploration et l'observation du jeu de données fournit.
- Conclusion 
    -
    Observations et des décisions prises post Analyse exploratoire.

## Conclusion :
### - Représentation visuelle du jeu de données :  
![image](https://github.com/marwan-rouissi/paris-trees/assets/115158061/f0d08b1d-81ed-475b-aaa3-d96b8812f6c0)

Nombre total de valeurs: 3 602 466  
Nombre total de valeurs non nulles: 2 936 165  
Nombre total de valeurs nulles: 666 301  
Pourcentage de valeurs nulles: 18.5%

Nous avons pris la décision de nous débarasser des colonnes peu ou pas pertinentes suivantes :
- type_emplacement : valeur unique (Arbre)
- numero : absence de données (vide à 100%)
- complement_adresse : manque de données (vide à 84,56%)

Bien que l'analyse exploratoire soit une étape primordiale dans le contexte de ce projet, elle n'est néanmoins pas suffisante pour répondre à la problèmatique posée ici.  
Le but étant de proposer une optimisation des tournées pour l'entretien des arbres de la ville, il est dommage de ne pas avoir eu en notre possession un jeu de données complet faisant mention des dates et circuits des tournées actuelle mais aussi l'état vital des arbres évoqués.  
Le manque de données, notamment la colonne "stade_de_developpement", joue également un rôle majeur dans la difficulté à réaliser la tâche demandée.  
Il est important de souligner l'importance de la collecte de données et leur mise à jours régulière afin de pouvoir en tirer un maximum d'informations et commencer alors à envisager tout travail d'optimisation par la suite.
