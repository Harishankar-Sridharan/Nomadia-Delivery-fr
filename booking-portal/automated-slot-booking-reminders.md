# Relances automatiques de réservation de créneau

Les relances de réservation de créneau relancent automatiquement les clients qui n’ont pas encore réservé de créneau de livraison. Après le premier message de réservation, Nomadia Delivery envoie jusqu’à quatre relances par e-mail et par SMS aux jours que vous choisissez, avec des modèles de messages dédiés. Dès que le client réserve un créneau, les relances restantes s’arrêtent. Vous réduisez le nombre de créneaux non réservés sans aucune relance manuelle.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à **Configuration**.
* Assurez-vous que le portail de réservation est configuré. Voir [Configurer le portail](booking-slots/configure-the-portal.md).
* Assurez-vous que l’envoi d’e-mails ou de SMS aux clients est activé dans **Configurer l’envoi de messages** > **Configuration générale**.

## Présentation de la fonctionnalité

* **Relances de prise de rendez-vous** : liste du paramétrage des pages expérience client dans laquelle vous choisissez les jours d’envoi des relances. Chaque relance est envoyée un jour compté à partir du premier message de réservation (**J**), n’importe quel jour de **J+1** à **J+10**. Vous pouvez choisir jusqu’à quatre jours : trois relances et une dernière relance.
* **Modèles de relance** : un modèle d’e-mail et de SMS dédié à chaque relance, de type **slotbookingreminder**. Le champ **Reminder slot** indique à quelle relance le modèle correspond : **1st**, **2nd**, **3rd** ou **Final**.
* **Aperçu** : affiche, à côté du message, le message tel que le client le recevra.
* **Arrêt automatique à la réservation** : lorsque le client réserve un créneau, les relances encore programmées ne sont pas envoyées.
* **Historique complet** : chaque relance envoyée apparaît dans la **Liste des e-mails envoyés** et la **Liste des SMS envoyés**, avec sa date d’envoi, son type et son état.

## Définir les jours de relance

1. Allez dans **Configuration** > **Réalisation et expérience client** > **Configurer les pages expérience client**, puis restez sur l’onglet **Général**.

![L’onglet Général des pages expérience client](../.gitbook/assets/SlotReminders_FR_001.jpg)

2. Ouvrez la liste **Relances de prise de rendez-vous**, puis sélectionnez jusqu’à quatre jours, de **J+1** à **J+10**. Par exemple, **J+2**, **J+4**, **J+6** et **J+9**.

![Choisissez les jours de relance dans la liste Relances de prise de rendez-vous](../.gitbook/assets/SlotReminders_FR_002.jpg)

3. Cliquez sur **Enregistrer**.

### Résultat

Les relances sont programmées. Avec les jours **J+2**, **J+4**, **J+6** et **J+9**, un client qui ne réserve jamais de créneau reçoit quatre relances sur neuf jours, la dernière étant la **dernière relance**.

## Personnaliser les messages de relance

1. Allez dans **Configuration** > **Réalisation et expérience client** > **Configurer l’envoi de messages**.
2. Cliquez sur **Modèles de courriel** pour les e-mails, ou sur **Modèles de SMS** pour les SMS. Les modèles de relance sont ceux de type **slotbookingreminder**.
3. Cliquez sur l’**icône crayon** du modèle à modifier, par exemple le modèle de la deuxième relance.
4. Dans **Reminder slot**, vérifiez la relance à laquelle correspond le modèle : **1st**, **2nd**, **3rd** ou **Final**. Le nombre de modèles déjà configurés est indiqué en dessous, par exemple **3 of 4 templates configured**.
5. Saisissez l’**Objet de l’e-mail**, puis rédigez le **Message à envoyer aux clients**. Vous pouvez y insérer des champs dynamiques, comme le numéro de mission.
6. Vérifiez l’**Aperçu** à côté du message, puis enregistrez le modèle.

![Un modèle de relance avec son Reminder slot et son aperçu](../.gitbook/assets/SlotReminders_FR_004.jpg)

### Résultat

Chaque relance utilise son propre modèle. Le client reçoit un message différent à chaque relance, ce qui l’aide à comprendre qu’une action est toujours attendue.

## Arrêt des relances dès qu’un créneau est réservé

Vous n’avez rien à faire. Lorsque le client réserve un créneau, les relances qui n’ont pas encore été envoyées sont annulées. Dans l’exemple ci-dessous, le client a réservé à **J+3** après la première relance : les relances suivantes et la dernière relance ne sont pas envoyées.

![Les relances s’arrêtent dès que le client réserve un créneau](../.gitbook/assets/SlotReminders_FR_005.jpg)

## Consulter les relances envoyées

1. Allez dans **Configuration** > **Réalisation et expérience client** > **Configurer l’envoi de messages**, puis cliquez sur **Liste des e-mails envoyés**.
2. Si besoin, cliquez sur **Filtre sur la période** et choisissez une période plus longue, par exemple **Le dernier mois**, puis cliquez sur **Appliquer**.
3. Consultez les messages de type **SLOTBOOKING**. Chacun est listé avec sa **Date d’envoi**, l’**Adresse e-mail** du client, son **État** (par exemple **Envoyé** ou **Cancelled**), l’utilisateur ou le système qui a déclenché l’envoi et le livreur.

![Les relances dans la Liste des e-mails envoyés](../.gitbook/assets/SlotReminders_FR_006.jpg)

4. Cliquez sur **Liste des SMS envoyés** pour voir les relances envoyées par SMS.

![Les relances dans la Liste des SMS envoyés](../.gitbook/assets/SlotReminders_FR_007.jpg)

## Conseils

{% hint style="info" %}
**Espacez les relances** : laissez au moins un jour entre deux relances et gardez la dernière relance pour les derniers jours avant la livraison. Les clients sont ainsi relancés sans être submergés de messages.
{% endhint %}

{% hint style="info" %}
**Configurez un modèle par relance** : vérifiez que chaque jour choisi a son modèle, par exemple **4 of 4 templates configured**, afin que chaque relance envoie un message adapté.
{% endhint %}

## Rubriques connexes

* [Portail de réservation](README.md)
* [Configurer le portail](booking-slots/configure-the-portal.md)
* [Enregistrement d’un donneur d’ordres](../contractors/register-a-contractor.md)
