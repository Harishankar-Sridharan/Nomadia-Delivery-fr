# Comprendre les paramètres de mission

Les paramètres de mission sont les éléments de données essentiels qui définissent les caractéristiques, les objectifs et les détails d’exécution de chaque mission. Comprendre ces paramètres est essentiel pour garantir que les missions sont correctement configurées, affectées et exécutées sur le terrain.

Ces paramètres fournissent des informations à la fois opérationnelles et logistiques utilisées par les coordinateurs, les répartiteurs et les livreurs.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à la **page Mission**.
* Identifiez la mission que vous souhaitez modifier, car vous ouvrez ses paramètres avec l’icône en forme de **crayon** située à côté.

## Accéder aux paramètres de mission

Depuis la **page Mission** :

1. Cliquez sur l’icône en forme de **crayon** à côté de la mission que vous souhaitez modifier.

![](<../../.gitbook/assets/image-6 (3).png>)

## Présentation de la fonctionnalité

### Onglet Paramètres de mission

| Section     | Paramètre                                   | Description                                                                                         |
| ----------- | ------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| **Mission** | Code-barres                                 | Généré automatiquement par Nomadia Delivery pour identifier la mission de manière unique.           |
|             | Agence (obligatoire)                        | Champ obligatoire précisant l’agence responsable du traitement de la mission.                       |
|             | Sous-traitant                               | Prestataire de livraison tiers affecté à la réalisation de la mission.                              |
|             | Code-barres de l’expéditeur                 | Code-barres facultatif fourni par le donneur d’ordre.                                               |
|             | ID du conteneur parent                      | Identifie le conteneur principal ou le groupe auquel appartient la mission.                         |
|             | Clé de regroupement                         | Regroupe les missions liées au même client pour faciliter leur traitement.                          |
|             | Type de conteneur                           | Type de conteneur utilisé (boîte, palette, caisse, etc.).                                           |
|             | Origine                                     | Lieu d’expédition initial de la livraison.                                                          |
|             | Livreur programmé                           | Nom du livreur affecté.                                                                             |
|             | Priorité                                    | Indique l’urgence (Haute, Moyenne, Basse).                                                          |
|             | Type de configuration du statut             | Définit le workflow appliqué à la mission.                                                          |
|             | Un type de mot de passe                     | Code de sécurité (PIN/OTP) utilisé pour la vérification.                                            |
|             | Statut de la mission                        | État actuel de la mission (par exemple : En attente, Livrée).                                       |
|             | Sous-statut                                 | État détaillé au sein du statut principal.                                                          |
|             | Motif                                       | Raison du sous-statut actuel.                                                                       |
|             | Type de mission                             | Livraison, Enlèvement, Enlèvement et livraison enchaînés, Visite, Livraison directe.                |
|             | Date provisoire                             | Date provisoire de la mission.                                                                      |
|             | Date de scan au dépôt principal             | Date/heure du scan au dépôt.                                                                        |
|             | Lieu de stockage                            | Emplacement dans le dépôt où l’article est stocké.                                                  |
|             | Durée fixe de visite                        | Durée estimée (en minutes) pour terminer la mission.                                                |
|             | Compatibilité avec les ressources           | Indique la compatibilité avec les ressources affectées.                                             |
|             | Exiger que toutes les compétences soient compatibles | Garantit que la ressource possède toutes les compétences requises.                         |
|             | Livraison avant enlèvement                  | Impose la séquence livraison avant enlèvement.                                                      |
|             | Clés                                        | Indique si des clés ou des codes d’accès sont nécessaires.                                          |
|             | Position                                    | Ordre de la mission dans l’itinéraire.                                                              |

### Colis

| Section   | Paramètre        | Description                                                  |
| --------- | ---------------- | ------------------------------------------------------------ |
| **Colis** | Type de produit  | Catégorie du produit (par exemple : électronique, alimentation). |
|           | Longueur         | Longueur du colis.                                           |
|           | Largeur          | Largeur du colis.                                            |
|           | Hauteur          | Hauteur du colis.                                            |
|           | Poids            | Poids du colis.                                              |
|           | Volume           | Volume du colis.                                             |
|           | Valeur du colis  | Valeur monétaire déclarée.                                   |
|           | Commentaire      | Notes internes sur la mission.                               |

### Enlèvement

| Section        | Paramètre                                | Description                                             |
| -------------- | ---------------------------------------- | ------------------------------------------------------- |
| **Enlèvement** | Adresse (obligatoire)                    | Adresse d’enlèvement (non modifiable après le routage). |
|                | Coordonnées                              | Civilité, nom, téléphone et e-mail de l’expéditeur.     |
|                | Retiré par                               | Personne/agent ayant effectué l’enlèvement.             |
|                | Date demandée d’enlèvement / date de fin | Créneau horaire d’enlèvement demandé.                   |
|                | Code de conteneur scannable              | Code-barres permettant d’identifier le conteneur.       |
|                | Instructions d’enlèvement / commentaire  | Instructions spéciales pour l’enlèvement.               |

### Livraison

| Section       | Paramètre                                | Description                                             |
| ------------- | ---------------------------------------- | ------------------------------------------------------- |
| **Livraison** | Adresse (obligatoire)                    | Adresse de livraison (non modifiable après le routage). |
|               | Coordonnées                              | Civilité, nom, téléphone et e-mail du destinataire.     |
|               | Livré par                                | Personne/agent ayant effectué la livraison.             |
|               | Date demandée de livraison / date de fin | Créneau horaire de livraison demandé.                   |
|               | Paiement à la livraison                  | Montant à encaisser.                                    |
|               | Prix de livraison                        | Coût de livraison pour la facturation.                  |
|               | Instructions de livraison / commentaire  | Instructions spéciales de livraison.                    |

### Articles

| Section      | Paramètre      | Description                     |
| ------------ | -------------- | ------------------------------- |
| **Articles** | Type d’article | Type d’article défini.          |
|              | Prévu          | Quantité prévue (0 = non liée). |
|              | Réalisé        | Quantité réellement effectuée.  |

### Heures d’ouverture

| Section                | Paramètre            | Description                                                 |
| ---------------------- | -------------------- | ----------------------------------------------------------- |
| **Heures d’ouverture** | Créneaux d’ouverture | Créneaux horaires autorisés pour l’exécution de la mission. |

### Photos

| Section    | Paramètre | Description                                            |
| ---------- | --------- | ------------------------------------------------------ |
| **Photos** | Photos    | Images capturées lors de l’enlèvement/de la livraison. |

### Signatures

| Section        | Paramètre  | Description                                           |
| -------------- | ---------- | ----------------------------------------------------- |
| **Signatures** | Signatures | Signatures du sous-traitant, du livreur et du client. |

### Documents

| Section       | Paramètre | Description                                                         |
| ------------- | --------- | ------------------------------------------------------------------- |
| **Documents** | Documents | Fichiers liés depuis la bibliothèque Nomadia ou des services cloud. |

### Journaux

| Section      | Paramètre                | Description                                                          |
| ------------ | ------------------------ | -------------------------------------------------------------------- |
| **Journaux** | Événements de la mission | Chronologie de tous les événements de la mission avec horodatage.    |

## Conseils

{% hint style="warning" %}
**Les adresses sont figées après le routage** : l’adresse d’enlèvement et l’adresse de livraison ne sont plus modifiables après le routage.
{% endhint %}

## Rubriques connexes

* [Gérer les missions](manage-missions.md)
* [Missions](../README.md)
* [Comprendre la page des missions](../understanding-the-missions-page/README.md)
