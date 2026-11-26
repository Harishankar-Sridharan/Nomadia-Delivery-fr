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

## À qui s’adresse ce guide

| Lecteur | Ce que vous trouverez | Commencez ici |
| ------- | --------------------- | ------------- |
| **Répartiteurs et planificateurs** | Le travail au quotidien : missions, itinéraires, simulations, donneurs d’ordres, sous-traitants et tickets. | [Guide des opérations](#guide-des-operations) |
| **Administrateurs** | La configuration du back-office : utilisateurs, adresses, conteneurs, documents, notifications, zones et flottes. | [Guide de l’administrateur](#guide-de-ladministrateur) |
| **Intégrateurs** | La connexion de Nomadia Delivery à d’autres systèmes. | [Intégration](#integration) |

## Contenu du guide

### Prise en main

| Section | Ce que vous trouverez |
| ------- | --------------------- |
| [Nomadbot](chatbot.md) | L’assistant virtuel qui répond à vos questions. |
| [Dernières mises à jour](summer-release-topics-2026/README.md) | Les nouveautés de chaque version : [Version d’été 2026](summer-release-topics-2026/summer-release-topics-2026.md) et [Version d’automne 2026](fall-release-2026/fall-release-2026.md). |
| [Page d’accueil](page-daccueil/README.md) | L’écran d’accueil, ses KPI et les statuts des missions. |

### Guide des opérations

| Section | Ce que vous trouverez |
| ------- | --------------------- |
| [Missions](missions/README.md) | Créer, importer, rechercher, modifier et suivre les missions, et configurer leurs formulaires et leurs champs personnalisés. |
| [Itinéraires](routes/README.md) | Créer, affecter, consulter et terminer les itinéraires. |
| [Simulation](simulation/simulation.md) | Optimiser les livraisons, ajuster les itinéraires et les valider. |
| [Sous-traitants](contractors/README.md) | Enregistrer les donneurs d’ordres et gérer leurs utilisateurs, leurs adresses, leurs restrictions et leurs plans. |
| [Gestion des sous-traitants](subcontractor-management/README.md) | Enregistrer les sous-traitants, créer leurs utilisateurs et leur affecter des missions. |
| [Retour au donneur d’ordres](return-to-contractor.md) | Créer les missions de retour pour les colis non livrés. |
| [Gérer les tickets](manage-tickets/README.md) | Signaler et résoudre les demandes liées aux missions entre donneurs d’ordres et transporteurs. |
| [Tableaux de bord personnalisés](custom-dashboards.md) | Construire et personnaliser vos tableaux de bord. |

### Guide de l’administrateur

| Section | Ce que vous trouverez |
| ------- | --------------------- |
| [Gérer les utilisateurs](manage-users/README.md) | Utilisateurs, profils, accès, rôles et droits, et jours de congé. |
| [Gérer la liste globale d’adresses](manage-global-address-list.md) | Le référentiel des adresses clients. |
| [Gérer les articles](manage-articles/README.md) | Le catalogue des articles livrés avec les missions. |
| [Gérer les types de conteneurs](manage-container-types/README.md) | Types de conteneurs, missions enfants, héritage et suivi des conteneurs. |
| [Gérer la bibliothèque de documents](manage-document-library/README.md) | Les documents partagés et les documents des missions. |
| [Gérer les modèles de documents](manage-document-templates/README.md) | Modèles Word, eCMR et QR codes. |
| [Gérer les notifications](manage-notifications/README.md) | Les notifications par e-mail et par SMS et leurs modèles. |
| [Gestion des alertes](alertmanagement.md) | Les seuils d’alerte. |
| [Gérer les études et les zones](manage-studies-and-zones/README.md) | Zones postales et sectorisation. |
| [Gérer les sous-statuts](manage-substatus/README.md) | Les sous-statuts et leurs notifications. |
| [Gérer les flottes de véhicules](manage-vehicle-fleets/README.md) | Véhicules, flottes, contraintes et lieux de pause déjeuner. |
| [Portail de réservation](booking-portal/README.md) | La réservation et le report des créneaux de livraison par les clients. |
| [Configuration de sondages personnalisés](configuring-customized-surveys.md) | Les sondages et les photos de l’état du véhicule. |
| [Personnaliser les onglets de navigation](customize-navigation-tabs.md) | L’ordre des onglets de l’en-tête. |
| [Configuration des raccourcis clavier](keyboard-shortcuts-configuration.md) | Les raccourcis clavier du back-office. |
| [Navigation par fil d’Ariane dans la configuration](configuration-breadcrumb-navigation.md) | Le fil d’Ariane cliquable de l’onglet Configuration. |

### Intégration

| Section | Ce que vous trouverez |
| ------- | --------------------- |
| [Gestion sécurisée des clés d’API](secure-api-key-management.md) | Les clés d’API de vos intégrations. |
| [Actions personnalisées](custom-actions.md) | Des boutons qui appellent des systèmes externes depuis le back-office. |

### Scénarios

| Section | Ce que vous trouverez |
| ------- | --------------------- |
| [Études de cas](case-studies/README.md) | Des scénarios de bout en bout : zones, permutations de sous-traitants, PUDO, missions à étapes multiples, logistique inverse et mode Sans Itinéraire. |

### Référence

| Page | Ce que vous trouverez |
| ---- | --------------------- |
| [Trouver une rubrique (A–Z)](reference/find-a-topic.md) | Toutes les rubriques du guide par ordre alphabétique. |
| [Glossaire](reference/glossary.md) | La signification des termes utilisés dans le back-office et dans ce guide. |

## Je veux...

| Je veux... | Accéder à |
| ---------- | --------- |
| Comprendre l’écran d’accueil | [Comprendre l’écran d’accueil](page-daccueil/comprendre-lecran-daccueil.md) |
| Créer une mission | [Ajout d’une mission](missions/adding-a-mission.md) |
| Importer des missions depuis Excel | [Importer des missions](missions/import-missions/README.md) |
| Rechercher une mission | [Rechercher une mission](missions/understanding-the-missions-page/search-for-a-mission.md) |
| Modifier plusieurs missions à la fois | [Modifier en masse les données de mission](missions/bulk-edit-mission-data.md) |
| Optimiser mes livraisons en itinéraires | [Optimiser les livraisons](simulation/simulation-deliveries-optimize.md) |
| Valider les itinéraires d’une simulation | [Valider les itinéraires](simulation/simulation-routes-validate.md) |
| Créer un itinéraire à la main | [Création manuelle d’un itinéraire](routes/manualroutecreation.md) |
| Enregistrer un donneur d’ordres | [Enregistrement](contractors/register-a-contractor.md) |
| Affecter des missions à un sous-traitant | [Affectation des missions au sous-traitant](subcontractor-management/assigning-missions-to-subcontractor.md) |
| Créer un utilisateur | [Créer un utilisateur à partir de zéro](manage-users/creating-user-from-a-scratch.md) |
| Envoyer des notifications par e-mail ou par SMS | [Gérer les notifications](manage-notifications/README.md) |
| Personnaliser un modèle de document Word | [Personnalisation des modèles Word](manage-document-templates/customizing-word-templates.md) |
| Connecter un système externe | [Actions personnalisées](custom-actions.md) et [Gestion sécurisée des clés d’API](secure-api-key-management.md) |
| Limiter les missions chargées sur la page Missions | [Définir l’affichage des missions (préfiltre)](missions/understanding-the-missions-page/pre-filters/set-missions-display-prefilter.md) |
| Sélectionner plusieurs missions à la fois | [Sélection d’une plage par Maj+clic](missions/understanding-the-missions-page/shift-click-range-selection.md) |
| Copier une configuration de mission | [Cloner une configuration de mission](missions/clone-a-mission-configuration.md) |
| Transférer des configurations de mission vers un autre compte | [Importer et exporter des configurations de mission en JSON](missions/import-and-export-mission-configurations-as-json.md) |
| Choisir les blocs d’adresse visibles par un profil utilisateur | [Visibilité des blocs du carnet d’adresses par profil utilisateur](contractors/address-list-block-visibility-per-user-profile.md) |
| Remonter à un niveau supérieur de l’onglet Configuration | [Navigation par fil d’Ariane dans la configuration](configuration-breadcrumb-navigation.md) |
| Donner aux donneurs d’ordres l’accès à un ensemble d’adresses | [Groupes d’adresses pour les donneurs d’ordres](contractors/address-list-groups-for-contractors.md) |
| Voir les nouveautés | [Version d’automne 2026](fall-release-2026/fall-release-2026.md) |
| Trouver une rubrique par son nom | [Trouver une rubrique (A–Z)](reference/find-a-topic.md) |
| Comprendre un terme | [Glossaire](reference/glossary.md) |

## Conseils

{% hint style="info" %}
**Synchronisation en temps réel** : à chaque mise à jour du statut d’une Mission, les modifications sont immédiatement synchronisées en temps réel avec la base de données du Backoffice, garantissant des informations cohérentes et à jour sur toutes les plateformes.
{% endhint %}

## Rubriques connexes

* [Page d’accueil](page-daccueil/README.md)
* [Missions](missions/README.md)
* [Itinéraires](routes/README.md)
* [Trouver une rubrique (A–Z)](reference/find-a-topic.md)
* [Glossaire](reference/glossary.md)
