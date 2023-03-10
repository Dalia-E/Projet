# Projet de datavisualisation: Les différents cinémas de France 
![FdZX0XdXoAIF_Oe](https://user-images.githubusercontent.com/103186628/217844279-25d31c28-7462-4c83-89d7-d8170fce8411.png)

# Table des matières

1. [Avant-Propos](#1-Avant-propos)
2. [Première datavisualisation : Les différents types de profil au Cinéma selon les zones géographiques (Flourish)](#2-première-datavisualisation-es-différents-types-de-profil-au-Cinéma-selon-les-zones-géographiques-Flourish)
3. [Deuxième datavisualisation à l'aide d'une carte (Datawrapper): l'évolution des entrées au Cinéma ](#3-deuxième-datavisualisation-à-l'aide-d'une-carte-Datawrapper)
4. [Troisième datavisualisation : Comparaison de données](#4-troisième-datavisualisation-Comparaison-de-données)
5. [Quatrième datavisualisation : Comparaison entre Flourish et Rawgraphs](#5-quatrième-datavisualisation-Comparaison-entre-Flourish-et-Rawgraphs)
6. [Cinquième datavisualisation avec Wikidata Query Service](#6-cinquième-datavisualisation-avec-Wikidata-Query-Service)
7. [Conclusion](#7-Conclusion)

## 1. Avant-Propos et jeu de donnée
Les données utilisées pour ce travail d’analyse et de visualisation de données ont été récupérées sur le site data.gouv.fr. Elles proviennent du Centre nationale du cinéma et de l’image animée (CNC) qui, comme toutes les autres institutions nationales et collectivités françaises, se doit de rendre ses données publiques. 
En l’occurrence, la CNC a effectué, par l’intermédiaire de partenaires, une étude de fréquentation des salles de cinéma et a ainsi pu récolté un certain nombre d’informations sur les personnes ayant assisté à une projection de film dans un cinéma en France. Ainsi, ce corpus de données se révèle être une mine d’or pour quiconque souhaiterait étudier les pratiques culturelles des Français en matière de cinéma, ou encore qui chercherait à établir un “profil-type” d’usager de cinémas. Telle est ainsi l’ambition de ce travail, qui permettra de faire ressortir les constantes comme les exceptions en matière de fréquentation de salles de cinéma françaises, en mettant l’accent sur des éléments d’interprétation et d’explication afin de contextualiser ce jeu de données. 

Le jeu de données utilisé comme unique source de ce travail est facilement téléchargeable à l’adresse suivante : https://www.data.gouv.fr/fr/datasets/etablissements-cinematographiques/. Il s’agit d’un fichier Excel répartissant plusieurs colonnes sur l'emplacements, le nom l'adresse, la commune des cinémas. Et j'ai alimenté mon jeu de donnée avec un autre qui est téléchargeable à l'adresse suivante: https://public.opendatasoft.com/explore/dataset/cnc-public-des-films/information/?flg=fr&disjunctive.categorie. 
Dans mon jeux de donnée, j'ai supprimé les colonnes suivantes : la colonne "genre" dans le jeu de données principales car elles ne renvoyait qu’aux termes "Fixes".  Et la colonne "catégorie Art et Essai" et "label Art et Essai" car il y avait énormément de manque d’informations, et "films Art et Essai". En effet, les informations ne correspondaient pas à mes recherches.

### Visualisation des données
Pour visualiser ces données, il a fallu faire les modifications nécessaire sur le fichier csv. Cela a pu se faire grâce à openrefine et ainsi pouvoir passer à l'étape suivante, la visualisation des données grâce aux différents outils vu en cours.


## 2. Première datavisualisation : Les différents types de profil au Cinéma selon les zones géographiques (Flourish)

Afin de pouvoir faire ce visuel, nous avons décidé d'utiliser le graphique "Char type Bars". Cela permet de faire une comparaison entre différentes variables. 

<iframe src='https://flo.uri.sh/visualisation/12579203/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/12579203/?utm_source=embed&utm_campaign=visualisation/12579203' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

A travers cette visualisation, nous avons pu voir le nombre de films programmés et inédits selon la région administrative et la population de la commune. Nous pouvons en déduire que le Top 5 des cinémas où il y a le plus de programmations ce sont les suivants: MEGA CGR, PATHE, REX, UGC CINE CITY et GAUMONT. Et dès que l'on cible une autre région, nous pouvons voir que le classement change car les goûts des établissemnet de cinémas diffère d'une région à l'autre. 

## 3. Deuxième datavisualisation à l'aide d'une carte (Datawrapper) : l'évolution des entrées au Cinéma

Par la suite, nous avons pensé qu'il serait nécessaire de visualiser les différents cinémas de France selon leurs régions avec une carte ainsi que l'évolution des entrées.

La carte a été choisi avec les régions de 2018. Pour pouvoir faire cette datavisualisation, il a fallu faire des modifications au niveau des données des régions car elles n'étaient pas conforme au format des régions de la carte sélectionnée. Il a fallu par expemple ajouter un trait d'union entre deux régions lorsque c'était nécessaire. Et après cette modification, nous avons pu avoir le résultat suivant. 

<iframe title="Les évolutions d'entrées au Cinéma" aria-label="Carte" id="datawrapper-chart-6DOOd" src="https://datawrapper.dwcdn.net/6DOOd/2/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="720" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(e){if(void 0!==e.data["datawrapper-height"]){var t=document.querySelectorAll("iframe");for(var a in e.data["datawrapper-height"])for(var r=0;r<t.length;r++){if(t[r].contentWindow===e.source)t[r].style.height=e.data["datawrapper-height"][a]+"px"}}}))}();</script>
 
Cette datavisualisation permet de montrer l'évolution des entrées au cinéma entre la période de 2019 à 2020. Les noms des cinémas sur la carte correspondent aux cinémas qui ont eu le plus grand nombre d'entrées. Lorsque l'on pose notre curseur sur les évolutions d'entrées, on peut voir qu'il y a eu des évolutions d'entrées dans les régions eux extrémités de la France, puis il y a eu une forte évolution en Ile-de-France avec le cinéma Kinepolis Servon et en Nouvelle-Aquitaine avec le Grand Club. Donc, cela nous permet de voir les cinémas qui sont les plus rentable. 
  
## 4. Troisième datavisualisation : Comparaison de données

Il me manquait des données d'actualité, c'est pour cela que les données des Box-Office (l'échelle de succès d'après le montant des recettes) en France durant les années 2021 et 2022 ont été trouvées sur Wikipédia. Cependant les données de l'année 2021 ne sont pas complètent car nous étions en période de crise sanitaire et les cinémas étaient fermés durant une période. Ainsi à cause de la pandémie de covid19 plusieurs films ont vu leur date de sortie repoussées. Voici ci dessous une comparaison de données à l'aide d'une story sur Flourish. En passant sur le donut, nous pouvons voir le titre du film, son classement et le succès qu'il a eu. 

<iframe src='https://flo.uri.sh/story/1822932/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/story/1822932/?utm_source=embed&utm_campaign=story/1822932' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

## 5. Quatrième datavisualisation : Comparaison entre Flourish et Rawgraphs 

Nous nous sommes focalisés sur le jeu de donnée visant les publics des films. A travers cette visualisation, nous pouvons voir les différents types de profils qui se rendent au cinéma. Les différents profils sont réparties dans différentes catégories à savoir les hommes, les enfants, les occasionnels, les adultes, les autres régions ect. L'axe des abscices renvoit aux années et l'axe des ordonnées renvoit au pourcentage. Nous pouvons remarqués que entre 60% et 80%, ce sont les personnes "des Autres régions" qui se rendent le plus au cinéma. La jauge de couleur permet de se repérer au niveau des catégories. Chaque catégorie se voit attribuer une couleur qui lui est propre.


<iframe src='https://flo.uri.sh/visualisation/12556747/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/12556747/?utm_source=embed&utm_campaign=visualisation/12556747' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

![pourcentage des personnes qui se rendent le plus au Cinéma](https://user-images.githubusercontent.com/103186628/217538923-0fc5c920-3149-4246-9a05-d4662d65b87d.jpg)

Il s'agit d'une visualisation différente mais qui nous rassure dans notre précèdente analyse. En effet, cette fois-ci les résultats sont sous forme de graphique avec en axe des abscisse, les catégories de personnes qui partent au cinéma et en axe des ordonnées les valeurs coresspondante. Nous avons juste une rendu qui n'est pas le même mais nous retrouvons toujours le même résultat. Par contre, les catégories des personnes ne s'affichait pas bien c'est-à-dire qu'on avait pas d'espace entre eux. Je n'ai pas réussi à changer cela.  

## 6. Cinquième datavisualisation avec Wikidata Query Service

### 1. Datavisualisation des films sortis en 2022

Avec l'aide d'une requête Wikidata, nous avons pu voir tous les films qui sont sortis durant l'année 2022. Pour cela, il a fallu ajouter un filtre qui a permis d'indiquer la date que l'ont souhaité rechercher. Le filtre permet de rendre le résultat plus sélectif et nous allons droit au but de notre recherche. 

```sparql
SELECT DISTINCT ?item ?itemLabel WHERE {
  ?item wdt:P31 wd:Q11424;
    wdt:P577 ?pubdate.
  FILTER((?pubdate >= "2022-01-01T00:00:00Z"^^xsd:dateTime) && (?pubdate <= "2022-12-31T00:00:00Z"^^xsd:dateTime))
  SERVICE wikibase:label { bd:serviceParam wikibase:language "fr,en". }
}
```
<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#SELECT%20DISTINCT%20%3Fitem%20%3FitemLabel%20WHERE%20%7B%0A%20%20%3Fitem%20wdt%3AP31%20wd%3AQ11424%3B%0A%20%20%20%20wdt%3AP577%20%3Fpubdate.%0A%20%20FILTER((%3Fpubdate%20%3E%3D%20%222022-01-01T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime)%20%26%26%20(%3Fpubdate%20%3C%3D%20%222022-12-31T00%3A00%3A00Z%22%5E%5Exsd%3AdateTime))%0A%20%20SERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22fr%2Cen%22.%20%7D%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>

### 2) Datavisualisation des films réalisés par Georges Lucas
Grâce à cette requête, nous pouvons visualiser tout les films réalisés par Georges Lucas avec un visuel en mode graphe. 
```sparql
#defaultView:Graph
SELECT ?item ?itemLabel (MIN(?date) AS ?firstReleased) ?_image
WHERE {
  ?item wdt:P161 wd:Q38222;
        wdt:P577 ?date
  SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],en". }
  OPTIONAL { ?item wdt:P18 ?_image. }
} GROUP BY ?item ?itemLabel ?_image
ORDER BY (?date)
```
<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#%23defaultView%3AGraph%0ASELECT%20%3Fitem%20%3FitemLabel%20(MIN(%3Fdate)%20AS%20%3FfirstReleased)%20%3F_image%0AWHERE%20%7B%0A%20%20%3Fitem%20wdt%3AP161%20wd%3AQ38222%3B%0A%20%20%20%20%20%20%20%20wdt%3AP577%20%3Fdate%0A%20%20SERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22%5BAUTO_LANGUAGE%5D%2Cen%22.%20%7D%0A%20%20OPTIONAL%20%7B%20%3Fitem%20wdt%3AP18%20%3F_image.%20%7D%0A%7D%20GROUP%20BY%20%3Fitem%20%3FitemLabel%20%3F_image%0AORDER%20BY%20(%3Fdate)" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>

## 7. Conclusion

Ce projet m'a permis de pratiquer et de créer des datavisualisations sur le sujet des cinémas. Cependant, il y a eu des cas où pour faire des visualisations, je n'ai pas pu utiliser un modèle car mes données étaient trop volumineuses et le rendu n'était pas compréhensible. C'est pour cela que j'ai décidé de choisir ceux qui allait mettre au mieux en avant mon projet. J'ai préféré utiliser openrefine à OpenOffice pour pouvoir faire des modifications sur mes jeux de donnée. Sur Openoffice, je ne pouvais pas enregistrer mon fichier au format csv, il fallait obligatoirement l'enregister en odt sinon les colonnes se décaler.
Concernant la réalisation du projet, cela a été très intéressant et très instructif. En effet, cela m'a permis de manipuler les différents outils de datavisualisation. Le seul désavantage c'est qu'on ne peut pas avoir une datavisualisation du premier coup, il faut pratiquer sur les différents outils afin de trouver celui qui nous convient le mieux. J'étais très loin d'imaginer que j'aurais pu faire tous cela grâce aux différents outils que nous avons manipulé en cours.


