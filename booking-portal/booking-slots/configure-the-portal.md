# Configurer le portail

Le portail de réservation de rendez-vous de Nomadia Delivery vous permet de planifier des créneaux optimisés pour les missions, en garantissant l’alignement avec les tournées existantes des livreurs. Utilisez ce guide pour améliorer l’efficacité de la planification.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à l’onglet **Configuration** et à l’onglet **Missions**.
* Connaissez les jours et les horaires de disponibilité de vos livreurs, car vous les définissez dans l’onglet **Planning**.
* Disposez d’une mission standard de retrait ou de livraison existante si vous souhaitez réserver un créneau, car **Réservation de rendez-vous** est désactivée pour les missions de cross-docking et de retrait et livraison en chaîne.

## Présentation de la fonctionnalité

* **Onglet Planning** : définit les créneaux horaires disponibles à la réservation dans le portail de rendez-vous.
* **Bouton Réservation de rendez-vous** : affiche les propositions de créneaux disponibles lorsque vous modifiez une mission.
* **Notation par étoiles** : classe les créneaux proposés selon leur distance par rapport aux tournées existantes dans le Backoffice.
  * **1 étoile** : le créneau proposé se situe à plus de 30 minutes des tournées existantes dans le Backoffice.
  * **2 étoiles** : le créneau proposé se situe entre 10 et 30 minutes des tournées existantes dans le Backoffice.
  * **3 étoiles** : le créneau proposé se situe à moins de 10 minutes des tournées existantes dans le Backoffice.

## Configurer le portail de réservation de rendez-vous

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Configuration**.

![](<../../.gitbook/assets/image-1 (5).png>)

2. Dans le menu déroulant, sélectionnez **Configurer les pages d’expérience client.**

![](<../../.gitbook/assets/image-2 (5).png>)

3. Cliquez sur l’option **Planifier une livraison.**

![](<../../.gitbook/assets/image-3 (5).png>)

4. Ouvrez l’onglet Planning. Cet onglet vous permet de définir les créneaux horaires qui seront disponibles à la réservation dans le portail de rendez-vous.

![](../../.gitbook/assets/image-6.png)

5. Cliquez dans la zone grise pour définir la disponibilité de vos livreurs.

![](<../../.gitbook/assets/image-5 (5).png>)

6. Choisissez les jours et les horaires souhaités selon vos préférences de livraison, puis enregistrez le planning.

Vous pouvez soit appliquer les mêmes créneaux à tous les jours de la semaine, soit configurer des créneaux différents pour chaque jour. Une fois la configuration terminée, la vue de planification affiche les créneaux préférés, comme indiqué dans la capture d’écran exemple.

![](<../../.gitbook/assets/image-6 (5).png>)

7. Cliquez sur **Enregistrer** pour confirmer le planning.

![](<../../.gitbook/assets/image-7 (5).png>)

## Mettre à jour ou supprimer un planning existant

1. Cliquez sur la **zone bleue** pour ouvrir le planning que vous souhaitez modifier.

![](<../../.gitbook/assets/image-8 (4).png>)

2. Ajustez la date et l’heure si nécessaire.
3. Cliquez sur **Mettre à jour** pour enregistrer les modifications, ou sur **Supprimer** pour retirer le planning.

## Réserver un créneau via le portail de réservation de rendez-vous

1. Lancez l’application Nomadia Delivery et accédez à l’onglet **Missions**.
2. Sélectionnez une mission existante en cliquant sur l’icône **crayon** pour la modifier.

![](<../../.gitbook/assets/image-9 (4).png>)

3. Cliquez sur le bouton **Réservation de rendez-vous** pour afficher les propositions de créneaux disponibles.

![](<../../.gitbook/assets/image-10 (3).png>)

La fonctionnalité **Réservation de rendez-vous** est disponible uniquement pour les missions standard de retrait ou de livraison. Elle est désactivée pour les types de mission suivants :

* **Cross-docking**
* **Retrait et livraison en chaîne**

Pour ces missions, un message d’infobulle, comme indiqué dans la capture d’écran ci-dessous, apparaît.

![](<../../.gitbook/assets/image-11 (3).png>)

Le moteur d’optimisation en temps réel propose des créneaux en tenant compte de la disponibilité du véhicule et de l’utilisateur, ainsi que des horaires de la mission, sur la base des créneaux prédéfinis configurés lors de la mise en place.

![](<../../.gitbook/assets/image-12 (3).png>)

Les créneaux proposés sont classés selon la notation par étoiles.

![](<../../.gitbook/assets/image-13 (3).png>)

4. Choisissez l’un des créneaux proposés et cliquez sur le bouton **Choisir** pour soit créer un nouveau planning de tournée pour le créneau sélectionné (si aucune tournée n’est déjà planifiée dans le Backoffice à cette date et heure), soit ajouter la mission à un planning de tournée existant.

![](<../../.gitbook/assets/image-14 (3).png>)

5. Consultez la notification qui apparaît dans le Backoffice une fois le créneau réservé avec succès.

![](<../../.gitbook/assets/image-15 (3).png>)

6. Retournez à l’onglet **Missions** pour confirmer que la tournée a été créée ou mise à jour pour la date et l’heure sélectionnées.

![](<../../.gitbook/assets/image-16 (3).png>)

## Conseils

{% hint style="info" %}
**Définition des créneaux** : les créneaux de livraison définis dans l’onglet Planning sont ceux proposés par le moteur d’optimisation en temps réel. Configurez-les avec soin afin d’éviter des suggestions de créneaux indésirables pendant les pauses (par exemple, déjeuner, briefing ou débriefing).
{% endhint %}

{% hint style="info" %}
**Facteurs des propositions de créneaux** : les propositions de créneaux sont influencées par plusieurs facteurs, tels que la disponibilité de l’utilisateur, la disponibilité du véhicule et les horaires d’ouverture de la mission. Veillez à ce que vos définitions de créneaux prennent ces facteurs en compte.
{% endhint %}

## Rubriques connexes

* [Portail de réservation](../README.md)
* [Créneaux de réservation](README.md)
* [Configuration du report](../reschedule-configuration.md)
