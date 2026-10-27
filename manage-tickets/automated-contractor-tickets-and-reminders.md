# Tickets et relances automatiques pour les donneurs d’ordres

Les tickets et relances automatiques créent un ticket pour le donneur d’ordres dès qu’un chauffeur enregistre un sous-statut précis dans l’application mobile, par exemple **Customer Door Closed**. Si le donneur d’ordres ne répond pas, des relances sont publiées selon un calendrier et une notification par e-mail est envoyée. Les relances s’arrêtent dès que le donneur d’ordres répond ou que le ticket est fermé, et chaque étape est consignée dans l’historique du ticket.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès au module **Tickets** et à **Configuration**. Voir [Activation du module de tickets](activating-the-ticket-module.md).
* Assurez-vous que le sous-statut qui doit déclencher le ticket existe. Voir [Gérer les sous-statuts](../manage-substatus/README.md).

## Présentation de la fonctionnalité

* **Modèles de tickets** : page de **Tickets** où vous créez les modèles utilisés pour les tickets automatiques.
* **Modèle de ticket** : modèle comportant un **Identifiant**, un **Nom du modèle**, un interrupteur **Activé**, le message d’origine et jusqu’à trois relances.
* **Relances sans réponse** : relances publiées lorsque le donneur d’ordres n’a pas répondu. Vous pouvez ajouter jusqu’à trois relances, une seule par jour, et chaque nouvelle relance doit tomber après la précédente, jusqu’à D+10.
* **Édition en cours** : sélecteur qui permet de passer du **Message d’origine** à chaque relance, afin que chacun ait son propre titre de ticket et son propre message.
* **Insérez des champs dans votre message** : champs dynamiques, tels que **Statut**, **Sous-statut**, **Motif**, **Livraison (Commentaire)**, **Enlèvement (Commentaire)**, **Prénom du client**, **Nom du client**, **Nom du prestataire**, **Prénom du prestataire**, **Nom de famille du prestataire** et **Numéros de mission**, remplacés par les valeurs de la mission dans le ticket.
* **Créer un ticket** : action à la réalisation d’un sous-statut qui crée automatiquement un ticket lorsqu’un utilisateur mobile exécute ce sous-statut.

## Créer un modèle de ticket

1. Accédez à **Tickets** > **Modèles de tickets**.

![La page Modèles de tickets](../.gitbook/assets/ContractorTickets_FR_001.jpg)

2. Cliquez sur **Actions**, puis sur **Nouveau modèle**.

![Cliquez sur Actions, puis sur Nouveau modèle](../.gitbook/assets/ContractorTickets_FR_002.jpg)

3. Assurez-vous que l’interrupteur **Activé** est activé, puis saisissez un **Identifiant** et un **Nom du modèle**.

![Le formulaire Modèle de ticket avec l’interrupteur Activé, l’Identifiant et le Nom du modèle](../.gitbook/assets/ContractorTickets_FR_003.jpg)

4. Avec **Message d’origine** sélectionné dans **Édition en cours**, saisissez le **Titre du ticket** et le message dans **Instructions pour l’agent**.
5. Pour ajouter des données de mission au message, cliquez sur les champs sous **Insérez des champs dans votre message**. Par exemple, `$[Nom du prestataire]$` est remplacé par le nom du donneur d’ordres dans le ticket.
6. Sous **Relances sans réponse**, cliquez sur **+ Ajouter une relance** et choisissez le moment de chaque relance, par exemple **D+1**, **D+3** et **D+5**.

![Le titre, le message, les champs dynamiques et les relances du modèle](../.gitbook/assets/ContractorTickets_FR_004.jpg)

7. Dans **Édition en cours**, sélectionnez tour à tour chaque relance et saisissez son propre **Titre du ticket** et son propre message.

![Le titre et le message d’une relance](../.gitbook/assets/ContractorTickets_FR_005.jpg)

8. Cliquez sur **Enregistrer le modèle**.

### Résultat

Le modèle apparaît dans la liste **Modèles de tickets**, avec son nombre de relances et son état d’activation.

## Lier le modèle à un sous-statut

1. Accédez à **Configuration** > **Sous-statuts**.

![La page Sous-statuts](../.gitbook/assets/ContractorTickets_FR_006.jpg)

2. Cliquez sur l’**icône crayon** à côté du sous-statut qui doit déclencher le ticket, par exemple **Customer Door Closed**.

![La page Modifier le sous-statut](../.gitbook/assets/ContractorTickets_FR_007.jpg)

3. Sous **Actions à la réalisation**, activez **Créer un ticket**, puis choisissez le **Modèle de ticket**. Le **Titre du ticket** est renseigné à partir du modèle.

![Activez Créer un ticket et choisissez le Modèle de ticket](../.gitbook/assets/ContractorTickets_FR_008.jpg)

![Créer un ticket crée automatiquement un ticket lorsqu’un utilisateur mobile exécute ce sous-statut](../.gitbook/assets/ContractorTickets_FR_009.jpg)

4. Cliquez sur **Enregistrer**.

### Résultat

Désormais, lorsqu’un chauffeur enregistre ce sous-statut dans l’application mobile :

1. Un ticket est créé à partir de votre modèle.
2. Si le donneur d’ordres ne répond pas, les relances sont publiées selon le calendrier, par exemple à D+1, D+3 et D+5, et une notification par e-mail est envoyée.
3. Les relances s’arrêtent dès que le donneur d’ordres répond ou que le ticket est fermé.

## Suivre un ticket automatique

1. Accédez à **Tickets** et ouvrez le ticket. Il affiche le message d’origine.
2. Consultez **Détails de la mission à la création**. Cette section affiche un instantané de la mission au moment de la création du ticket, comme le statut de la mission, le sous-statut, le motif, le commentaire, le nom du client et le numéro de la mission.
3. Pour mettre fin au suivi, cliquez sur **Fermer le ticket**.

![Le ticket automatique avec son message d’origine, les détails de la mission et le bouton Fermer le ticket](../.gitbook/assets/ContractorTickets_FR_010.jpg)

4. Consultez **Réponses**. Les relances y sont publiées selon le calendrier.
5. Pour répondre, saisissez votre réponse dans la zone **Tapez votre réponse ici…** et cliquez sur **Répondre**.

![Les relances publiées dans la section Réponses et la zone de réponse](../.gitbook/assets/ContractorTickets_FR_011.jpg)

### Résultat

Lorsque le donneur d’ordres répond ou que le ticket est fermé, les relances restantes s’arrêtent. Chaque étape est consignée dans l’historique du ticket.

## Conseils

{% hint style="info" %}
**Calendrier des relances** : vous pouvez ajouter jusqu’à trois relances, une seule par jour. Chaque nouvelle relance doit tomber après la précédente, jusqu’à D+10.
{% endhint %}

## Rubriques connexes

* [Gérer les tickets](README.md)
* [Créer un ticket](creating-a-ticket.md)
* [Gérer les sous-statuts](../manage-substatus/README.md)
