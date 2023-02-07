# Projet de datavisualisation: Les différents cinémas de France 
![Les salles de cinémas en France](https://www.lagazettedescommunes.com/wp-content/uploads/2019/10/cnc-2-capture-1.png)

# Table des matières

1. [Avant-Propos](#1-Avant-propos)
2. [Première datavisualisation avec Line chart race (Flourish)](#2-première-datavisualisation-avec-un-line-chart-race-flourish)
3. [Deuxième datavisualisation avec une carte (Datawrapper)](#3-deuxième-datavisualisation-avec-une-carte-datawrapper)
4. [Croisement des données](#4-croisement-des-données)
5. [Troisième datavisualisation avec Bar chart race (Flourish)](#5-troisième-datavisualisation-avec-bar-chart-race-flourish)
6. [Quatrième datavisualisation des données croisées](#6-quatrième-datavisualisation-des-données-croisées)
7. [Visualisation de Paris avec Wikidata Query Service](#7-visualisation-de-paris-avec-wikidata-query-service)

## 1. Avant-Propos et jeu de donnée
Les données utilisées pour ce travail d’analyse et de visualisation de données ont été récupérées sur le site data.gouv.fr. Elles proviennent du Centre nationale du cinéma et de l’image animée (CNC) qui, comme toutes les autres institutions nationales et collectivités françaises, se doit de rendre ses données publiques. 

En l’occurrence, la CNC a effectué, par l’intermédiaire de partenaires, une étude de fréquentation des salles de cinéma et a ainsi pu récolté un certain nombre d’informations sur les personnes ayant assisté à une projection de film dans un cinéma en France.

Ainsi, ce corpus de données se révèle être une mine d’or pour quiconque souhaiterait étudier les pratiques culturelles des Français en matière de cinéma, ou encore qui chercherait à établir un “profil-type” d’usager de cinémas. 

Telle est ainsi l’ambition de ce travail, qui permettra de faire ressortir les constantes comme les exceptions en matière de fréquentation de salles de cinéma françaises, en mettant l’accent sur des éléments d’interprétation et d’explication afin de contextualiser ce jeu de données. 

Le jeu de données utilisé comme unique source de ce travail est facilement téléchargeable à l’adresse suivante : https://www.data.gouv.fr/fr/datasets/etablissements-cinematographiques/. Il s’agit d’un fichier Excel répartissant plusieurs colonnes sur l'emplacements, le nom l'adresse, la commune des cinémas. Et j'ai alimenté mon jeu de donnée avec un autre qui est télécheargeable à l'adresse suivante: https://public.opendatasoft.com/explore/dataset/cnc-public-des-films/information/?flg=fr&disjunctive.categorie. 
Dans mon jeux de donnée, j'ai supprimé les colonnes suivantes : J’ai supprimé la colonne genre dans le jeu de données principales car elles ne renvoyait qu’aux termes « Fixes ».  Et la colonne catégorie Art et Essai et label Art et Essai car il y avait énormément de manque d’informations, et films Art et Essai. En effet, ellesles informations ne correspondaient pas à mes recherches 




## Les différents types de profil au Cinéma selon les zones géographiques 

A travers cette visualisayion, nous avons pu voir le nombre de films programmés et inédits selon la région administrative et la population de la commune. Nous pouvons en déduire que le Top 5 des cinémas où il y a le plus de programmations de films ce sont les suivants: MEGA CGR, PATHE, REX, UGC CINE CITY et GAUMONT. Et dès que l'on cible une autre régions, le classement change car les goûts des établissemnet de cinémas diffère d'une région à une autre. 

 <!DOCTYPE html>
<html>
 <head>
   <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
   <link rel="shortcut icon" type="image/ico" href="img/favicon.gif" />
   <link rel="stylesheet" type="text/css" href="style.css" />
   <title> titre </title>
 </head>
 <body>
  <div class="flourish-embed flourish-hierarchy" data-src="visualisation/12579203"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
 </body>
</html>
