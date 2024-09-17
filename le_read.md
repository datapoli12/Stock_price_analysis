## Analyse de l'impact des nouvelles économiques sur les prix des actions ## 

Analyse d'impact : Comprendre comment un évènement spécifique influence une variable.

    ** Variable expliquée : le prix des actions

    ** Variable explicative : nouvelles économiques

    => Corrélation ou Causalité ?

## Idée de questionnement 1 : Comment les annonces de l'OPEP sur les quotas de production affectent-elles les prix des actions des grandes entreprises pétrolières dans les heures qui suivent l'annonce ? ##

- Examiner comment les prix des actions des grandes entreprises pétrolières réagissent immédiatement après une annonce de l'OPEP.

- Évaluer si les actions des entreprises pétrolières réagissent différemment selon que l'OPEP décide d'augmenter, de réduire, ou de maintenir les quotas de production de pétrole.

- Mesurer la rapidité avec laquelle les prix des actions des entreprises pétrolières s'ajustent après les annonces, pour comprendre l'efficacité du marché.


## Idée de questionnement 2 : Comment les annonces d'une Banque centrale sur les taux directeurs affectent-elles les prix des actions du secteur bancaire dans les heures qui suivent l'annonce ?"

- Examiner comment les prix des actions des principales entreprises bancaires réagissent immédiatement après une annonce d'ajustement des taux directeurs par la Banque centrale.

- Évaluer si les actions des entreprises bancaires réagissent différemment selon que la Banque centrale décide d'augmenter, de diminuer ou de maintenir les taux d'intérêt.

- Mesurer la rapidité avec laquelle les prix des actions du secteur bancaire s'ajustent après ces annonces, afin de déterminer l'efficacité des marchés financiers et la répercussion instantanée des nouvelles économiques majeures sur le secteur bancaire.


### Notre objectif principal : 

* Comprendre la relation existante entre les variables ; identifier si les prix augmentent, diminuent ou stagnent suite à une annonce (quelque soit son ordre), et quantifier cet impact.

* Proposer un modèle prédictif simple qui anticipe la réaction du marché en fonction du type d'annonce ( Par exemple annonce gouvernementale d'ordre macro ou annonce de résultats trimestriels des grandes entreprises) et de son envergure.


### Collecte des données

* Toute notre analyse sera construite à partir des données. On se doit de trouver des données les plus fiables et pertinentes pour une bonne analyse et un modèle prédictif de qualité.

* Nous allons d'abord nous concentrer sur certaines entreprises d'un secteur donné pour l'analyse. 
    - on Travaillera avec : *JPMorgan Chase (JPM), Goldman Sachs (GS), Bank of America (BAC), Wells Fargo (WFC), Citigroup (C)*
    
    - Le choix de ces grandes banques, nous permet d'observer les effets des annonces économiques sur un ensemble  d'entreprises du secteur. Cela donne une vue plus globale sur la réaction du secteur financier.

* Nous allons récupérer les données des annonces économiques via l'API FRED


### Préparation et nettoyage des données

* Nous allons nettoyer la donnée en éliminant les erreurs, les valeurs manquantes pour s'assurer que les données soit dans un format approprié pour l'analyse. C'est l'une des parties les plus importantes du projet. on se doit de le faire avec une rigueur absolue. Si cette étape est mal faite, toute l'analyse risque d'être faussée.

* Pour la gestion des valeurs manquantes, nous allons utiliser la méthode de la suppression des lignes manquantes pour des attributs dont une grande partie des données est manquante si non, la méthode de remplissage des valeurs manquantes puisque les données sont continues.




