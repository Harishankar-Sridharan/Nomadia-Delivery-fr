# Plans fixes et récurrents

Ce guide fournit des instructions étape par étape aux transporteurs pour créer des plans fixes et récurrents dans Nomadia Delivery. Ces fonctionnalités sont conçues pour aider les sous-traitants ayant des engagements de livraison et de retrait à long terme en simplifiant le processus de planification, en améliorant la précision et en offrant de la flexibilité pour gérer les itinéraires sur de longues périodes.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à l’onglet **Sous-traitants**.
* Assurez-vous que le sous-traitant pour lequel vous souhaitez planifier existe et qu’il possède des adresses dans sa **Liste d’adresses**.
* Connaissez les dates de début et de fin de la période d’optimisation ainsi que les véhicules pour lesquels les itinéraires doivent être créés.

## Présentation de la fonctionnalité

Les détails du plan d’itinéraire sont les suivants :

* **Nom** : attribuez un nom pour faciliter la référence ultérieure.
* **Activé** : activez le bouton bascule pour activer le plan d’itinéraire.
* **Itinéraires dédiés** : activez cette option si le plan doit générer des itinéraires dédiés qui ne peuvent pas être combinés avec les missions d’autres sous-traitants.
* **Récurrent** : activez cette option pour rendre le plan récurrent.
* **Du et au** : indiquez les dates de début et de fin pour définir la période de validité du plan.
* **Répéter tous les** : définissez la fréquence de récurrence (hebdomadaire ou mensuelle).
* **Jours de la semaine** : choisissez les jours de répétition du plan et définissez, si nécessaire, l’intervalle entre les récurrences.

## Créer un plan fixe et récurrent

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Sous-traitants**.

![](<../.gitbook/assets/image-1 (7).png>)

2. Sélectionnez le sous-traitant pour lequel vous souhaitez créer un plan fixe et récurrent, puis cliquez sur l’icône crayon pour le modifier.

![](<../.gitbook/assets/image-2 (8).png>)

3. Accédez à la **Liste d’adresses**.
4. Sélectionnez les adresses pour lesquelles vous souhaitez créer le plan fixe et récurrent.

![](<../.gitbook/assets/image-3 (7).png>)

5. Ouvrez le menu **Actions** et choisissez **Ajouter à une simulation**.

![](<../.gitbook/assets/image-4 (7).png>)

6. Cliquez sur **Créer une simulation** ou sélectionnez une simulation existante dans la liste déroulante **Sélectionner une simulation**.

![](<../.gitbook/assets/image-5 (7).png>)

7. Définissez les dates de début et de fin de la période d’optimisation.

![](<../.gitbook/assets/image-6 (7).png>)

8. Sélectionnez les véhicules pour lesquels les itinéraires doivent être créés.
9. Cliquez sur **Optimiser** pour lancer le processus d’optimisation.

![](<../.gitbook/assets/image-7 (7).png>)

10. Une fois l’optimisation en cours, cliquez sur **Arrêter** pour voir les résultats, puis cliquez sur **Afficher la simulation** pour consulter le résultat.

![](<../.gitbook/assets/image-8 (6).png>)

11. Si les résultats sont satisfaisants, accédez à la section **Itinéraires**, ouvrez le menu **Actions** et sélectionnez **Créer le plan d’itinéraire**.

![](<../.gitbook/assets/image-9 (6).png>)

12. Cliquez sur **OK** pour confirmer et commencer la création du plan d’itinéraire.

![](<../.gitbook/assets/image-10 (5).png>)

13. Renseignez les détails du plan d’itinéraire décrits dans la présentation de la fonctionnalité.
14. Cliquez sur **Enregistrer** pour sauvegarder le plan d’itinéraire récurrent.

![](<../.gitbook/assets/image-11 (5).png>)

### Résultat

Une notification de confirmation apparaît une fois le plan créé avec succès.

![Capture d’écran](<../.gitbook/assets/image-12 (5).png>)

Tous les plans d’itinéraire enregistrés sont accessibles depuis la page Liste d’adresses dans le module Sous-traitants.

![](<../.gitbook/assets/image-13 (5).png>)

## Accéder aux plans d’itinéraire depuis la page Missions

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Missions**.
2. Cliquez sur l’icône **Panneau** pour activer la personnalisation du panneau.

![](<../.gitbook/assets/image-14 (5).png>)

3. Faites glisser-déposer le panneau **Plan d’itinéraire** à l’emplacement souhaité.

![](<../.gitbook/assets/image-15 (5).png>)

4. Cliquez de nouveau sur le panneau **Plan d’itinéraire** pour quitter le mode d’édition du panneau.

![](<../.gitbook/assets/image-16 (5).png>)

## Générer des missions le jour prévu

Le jour de la livraison ou du retrait, les missions peuvent être soit :

* créées directement par le sous-traitant via le Portail sous-traitant ;
* créées automatiquement par le transporteur pour effectuer les livraisons.

Si des missions ont déjà été créées par le sous-traitant :

1. Ouvrez le menu **Actions** et sélectionnez **Appliquer le plan d’itinéraire**.

![](<../.gitbook/assets/image-17 (6).png>)

Si le transporteur doit créer des missions pour le compte du sous-traitant :

1. Cliquez sur **Générer les livraisons** pour créer des missions de livraison.
2. Cliquez sur **Générer les retraits** pour créer des missions de retrait.

![](<../.gitbook/assets/image-18 (6).png>)

3. Cliquez sur **Oui** pour confirmer et générer des missions pour tous les clients inclus dans le plan récurrent.

![](<../.gitbook/assets/image-19 (6).png>)

### Résultat

Nomadia Delivery crée automatiquement les missions pour tous les clients associés au plan d’itinéraire récurrent.

![](<../.gitbook/assets/image-20 (6).png>)

## Exécuter le plan d’itinéraire le jour de la livraison

Le jour de la livraison, les sous-traitants peuvent créer des missions uniquement pour certains clients, par exemple lorsque certaines commandes peuvent être refusées pour des raisons telles qu’une rupture de stock ou l’indisponibilité du client.

Pour valider le plan d’itinéraire :

1. Ouvrez le menu **Actions** et sélectionnez **Appliquer le plan d’itinéraire**.

![](<../.gitbook/assets/image-17 (6).png>)

2. Comparez le plan d’itinéraire prédéfini avec les missions créées en mode Comparaison. Cela aide les transporteurs à évaluer le pourcentage du plan d’itinéraire qui sera exécuté en temps réel.

![](<../.gitbook/assets/image-22 (6).png>)

3. Cliquez sur **Valider** pour générer le plan d’itinéraire final.

![](<../.gitbook/assets/image-23 (6).png>)

En suivant ces étapes, les transporteurs peuvent gérer efficacement les plans fixes et récurrents dans Nomadia Delivery, en garantissant des opérations fluides et un service fiable pour les sous-traitants et leurs clients.

## Conseils

{% hint style="warning" %}
**Aucune mission liée** : si aucune mission n’est liée au plan d’itinéraire sélectionné, le système affiche une notification d’erreur.
{% endhint %}

## Rubriques connexes

* [Sous-traitants](README.md)
* [Enregistrer un sous-traitant](register-a-contractor.md)
* [Gérer la liste d’adresses](manage-address-list.md)
* Optimiser les livraisons
