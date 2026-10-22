# Introduction

Nomadia Delivery est une solution SaaS basée sur le cloud, conçue pour simplifier et optimiser les processus logistiques et de distribution. La plateforme permet une gestion efficace des opérations de livraison en organisant les expéditions en Missions, chacune représentant un flux logistique de marchandises d’un point d’origine vers une destination de livraison. Une Mission peut concerner un colis, une palette ou tout autre conteneur transportable. Chaque Mission suit un trajet d’une origine vers une destination. Par exemple, une Mission peut concerner une palette de légumes quittant un entrepôt central pour être livrée à une épicerie locale. Les Missions sont suivies à l’aide d’une série de statuts — tels que En attente, Reçue, Chargée, À livrer, Livrée, et autres — offrant une traçabilité complète tout au long du cycle de livraison. Des informations supplémentaires, notamment l’historique des statuts, des photos et les détails clés du trajet, sont également enregistrées afin d’assurer une transparence complète.

La plateforme prend en charge la gestion de jusqu’à 500 000 Missions, avec de puissantes fonctions de filtrage et de tri disponibles pour aider les utilisateurs à se concentrer sur les Missions pertinentes pour leurs opérations.

## Avant de commencer

* Ayez à disposition les Missions que vous souhaitez gérer, par exemple sous forme de feuille de calcul Excel ou via un import par API.
* Connaissez l’Itinéraire et la ressource de livraison auxquels les Missions seront affectées.

## Présentation de la fonctionnalité

* **Mission** : un flux logistique de marchandises d’un point d’origine vers une destination de livraison, tel qu’un colis, une palette ou tout autre conteneur transportable.
* **Statuts** : suivent chaque Mission, tels que En attente, Reçue, Chargée, À livrer et Livrée.
* **Backoffice** : l’endroit où les Missions sont importées, progressent à travers les statuts et sont affectées à un Itinéraire.
* **Application mobile** : l’endroit où le personnel de livraison met à jour les statuts des Missions jusqu’à ce qu’elles atteignent le statut Livrée.

## Dans le Backoffice

* Les Missions (telles que des colis ou des palettes) peuvent être importées dans le système par différentes méthodes, notamment des feuilles de calcul Excel et des API.
* Chaque mission progresse à travers des statuts définis jusqu’à atteindre le statut « À livrer ».
* Les Missions sont ensuite affectées à un Itinéraire spécifique, ainsi qu’à la ressource de livraison désignée.

## Dans l’application mobile

* Le personnel de livraison continue de mettre à jour les statuts de la Mission au fur et à mesure de son parcours, jusqu’à atteindre finalement le statut Livrée.

## Conseils

{% hint style="info" %}
**Synchronisation en temps réel** : à chaque mise à jour du statut d’une Mission, les modifications sont immédiatement synchronisées en temps réel avec la base de données du Backoffice, garantissant des informations cohérentes et à jour sur toutes les plateformes.
{% endhint %}

## Rubriques connexes

* [Page d’accueil](page-daccueil/README.md)
* [Missions](missions/README.md)
* [Itinéraires](routes/README.md)
