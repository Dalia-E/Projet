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
Dans mon jeux de donnée, j'ai supprimé les colonnes suivantes : J’ai supprimé la colonne genre dans le jeu de données principales car elles ne renvoyait qu’aux termes « Fixes ».  Et la colonne catégorie Art et Essai et label Art et Essai car il y avait énormément de manque d’informations, et films Art et Essai. En effet, ellesles informations ne correspondaient pas à mes recherches.

### Visualisation des données
Pour visualiser ces données, il a fallu faire les modifications nécessaire sur le fichier csv. Cela a pu se faire grâce à openoffice et ainsi pouvoir passer à l'étape suivante, la visualisation des données grâce aux différents outils vu en cours.


## 2. Première datavisualisation : Les différents types de profil au Cinéma selon les zones géographiques (Flourish)

Afin de pouvoir faire ce visuel, nous avons décidé d'utiliser le graphique "Char type Bars". Cela permet de faire une comparaison entre différentes variables. 

<iframe src='https://flo.uri.sh/visualisation/12579203/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/12579203/?utm_source=embed&utm_campaign=visualisation/12579203' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

A travers cette visualisayion, nous avons pu voir le nombre de films programmés et inédits selon la région administrative et la population de la commune. Nous pouvons en déduire que le Top 5 des cinémas où il y a le plus de programmations de films ce sont les suivants: MEGA CGR, PATHE, REX, UGC CINE CITY et GAUMONT. Et dès que l'on cible une autre régions, le classement change car les goûts des établissemnet de cinémas diffère d'une région à une autre. 

## 3. Deuxième datavisualisation à l'aide d'une carte (Datawrapper)

Par la suite, nous avons pensé qui'il serait nécessaire de visualiser les différents cinémas de France selon leurs régions avec une carte. La carte a été choisi avec les régions de 2018. 

## 4. Troisième datavisualisation : Comparaison de données

Les données des Box-Office en France durant les années 2021 et 2022 ont été trouvées sur wikipédia. Cependant les données de l'année 2021 ne sont pas complètent car nous étions en période de crise sanitaire et les cinémas étaient ermés durant une période. Ainsi à cause de la pandémie de covid19 plusieurs films ont vu leur date de sortie repoussées.

<iframe src='https://flo.uri.sh/story/1822932/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/story/1822932/?utm_source=embed&utm_campaign=story/1822932' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

## 5. Quatrième datavisualisation : Comparaison entre Flourish et Rawgraphs 

A travers cette visualisation, nous pouvons voir les différents types de profils qui partent au cinéma. Les différents profis snt réparties dans différentes catégories à savoir les hommes, les enfants, les occasionnels, les adultes, les autres régions ect. Nous pouvons remarqués que entre 60% et 80%, ce sont les personnes "des Autres régions" qui se rendent le plus Cinéma. 


<iframe src='https://flo.uri.sh/visualisation/12556747/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/12556747/?utm_source=embed&utm_campaign=visualisation/12556747' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

![pourcentage des personnes qui se rendent le plus au Cinéma](https://user-images.githubusercontent.com/103186628/217538923-0fc5c920-3149-4246-9a05-d4662d65b87d.jpg)
Il s'agit d'une visualisation différente mais qui nous rassure dans notre précèdente analyse. Nous avons juste une rendu qui est différent. 
## 6. Visualisation de la France avec Wikidata Query Service


## 8. Conclusion



