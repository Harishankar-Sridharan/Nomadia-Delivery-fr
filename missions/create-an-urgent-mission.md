# Créer une mission urgente

Les missions urgentes suivent un modèle « en chaîne » où un retrait est immédiatement suivi d’une livraison pour la même commande, comme pour la livraison de repas à la demande ou de soins de santé. Cette fonctionnalité garantit une séquence stricte d’opérations 1 pour 1 et utilise un flux de travail d’affectation dédié aux livreurs disponibles.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès aux missions.
* Préparez les informations de retrait (origine) et de livraison (destination) de la commande.

## Présentation de la fonctionnalité

* **Retrait et livraison en chaîne** : type de mission dans lequel un retrait est immédiatement suivi d’une livraison pour la même commande.
* **Informations de retrait (Origine)** : section où vous saisissez les informations de retrait.
* **Informations de livraison (Destination)** : section où vous saisissez les informations de livraison.
* **Affecter la mission urgente** : bouton qui affecte la mission créée à un livreur disponible.

## Créer une mission urgente

1. Ouvrez l’**écran de création de mission**.
2. Sélectionnez le **type de mission Retrait en chaîne** et **Livraison**.

<figure><img src="../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

3. Saisissez les **Informations de retrait (Origine)**.
4. Saisissez les **Informations de livraison (Destination)**.

<figure><img src="../.gitbook/assets/image (131) (1).png" alt=""><figcaption></figcaption></figure>

5. Sélectionnez la **mission créée** dans la liste.
6. Cliquez sur le bouton **Affecter** la mission urgente.

<figure><img src="../.gitbook/assets/image (132) (1).png" alt=""><figcaption></figcaption></figure>

### Résultat

La nouvelle mission de retrait est ajoutée dynamiquement à l’itinéraire existant.

Lorsque vous créez une mission de retrait urgente, le système **l’ajoute automatiquement à l’itinéraire actuel d’un livreur** sans nécessiter de planification manuelle.

* Le système vérifie :
  * Quel livreur est à proximité
  * Quel itinéraire peut prendre en charge le nouveau retrait
* Il **insère ensuite le retrait à la meilleure position dans l’itinéraire**

<figure><img src="../.gitbook/assets/image (133) (1).png" alt=""><figcaption></figcaption></figure>

## Rubriques connexes

* [Missions](README.md)
* [Créer une mission de retrait urgente](create-an-urgent-pickup-mission.md)
