# Déclencher des notifications pour les changements de sous-statut

La fonctionnalité Déclencher des notifications pour les changements de sous-statut permet une communication précise et en temps réel avec toutes les parties prenantes impliquées dans le mouvement des colis. Elle améliore la transparence, la coordination et la qualité globale du service sur les opérations du premier kilomètre, du kilomètre intermédiaire et du dernier kilomètre.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à l’onglet **Configuration**.
* Assurez-vous que le sous-statut que vous souhaitez modifier existe déjà dans la liste **Sous-statuts**.
* Préparez un modèle de message personnalisé, car seuls les modèles de messages personnalisés sont pris en charge.
* Ayez à portée de main les adresses e-mail ou les numéros de mobile si vous notifiez **Autres destinataires**.

## Présentation de la fonctionnalité

Les notifications peuvent être envoyées aux destinataires suivants :

* **Expéditeur** : l’expéditeur initial de la mission. Les notifications sont envoyées à l’adresse e-mail ou au numéro de mobile du sous-traitant enregistré dans les détails de la mission.
* **Destinataire** : le destinataire initial de la mission (client). Les notifications sont envoyées à l’adresse e-mail de livraison ou au numéro de mobile enregistré dans les détails de la mission.
* **Autres destinataires** : les parties prenantes internes telles que les équipes d’exploitation ou de logistique. Ce champ accepte plusieurs adresses e-mail ou numéros de téléphone, séparés par des virgules. Ce champ est activé uniquement lorsque **Autres destinataires** est sélectionné dans la colonne **Destinataire**.

## Configurer les notifications pour les changements de sous-statut

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Configuration**.

<figure><img src="../.gitbook/assets/image (5) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. Sélectionnez **Sous-statuts** dans la liste.

<figure><img src="../.gitbook/assets/image (6) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

3. Cliquez sur l’icône **crayon** à côté du sous-statut existant pour le modifier.

<figure><img src="../.gitbook/assets/image (7) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

4. Repérez la section Configuration des messages personnalisés en bas de la page.

<figure><img src="../.gitbook/assets/image (8) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

5. Cliquez sur le bouton **+** pour ajouter la configuration de notification au sous-statut.

<figure><img src="../.gitbook/assets/image (9) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

6. Sélectionnez le destinataire : **Expéditeur**, **Destinataire** ou **Autres destinataires**.

<figure><img src="../.gitbook/assets/image (10) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

7. Sélectionnez un **destinataire**, un **type de message** (e-mail ou SMS) et un **modèle de message** pour créer la configuration de notification.

<figure><img src="../.gitbook/assets/image (11) (1) (1).png" alt=""><figcaption></figcaption></figure>

8. Si vous avez sélectionné **Autres destinataires**, saisissez plusieurs adresses e-mail ou numéros de téléphone dans le champ Autres destinataires, séparés par des virgules.

<figure><img src="../.gitbook/assets/image (12) (1) (1).png" alt=""><figcaption></figcaption></figure>

9. Cliquez sur **Enregistrer** pour appliquer et enregistrer les modifications.

<figure><img src="../.gitbook/assets/image (13) (1) (1).png" alt=""><figcaption></figcaption></figure>

### Résultat

Lorsque l’utilisateur mobile déclenche un sous-statut, tous les destinataires configurés reçoivent automatiquement la mise à jour par e-mail ou SMS en même temps, ce qui fournit des informations en temps réel sur le mouvement de la mission.

<figure><img src="../.gitbook/assets/image (14) (1) (1).png" alt=""><figcaption></figcaption></figure>

## Conseils

{% hint style="info" %}
**Modèles de messages** : seuls les **modèles de messages personnalisés** sont pris en charge dans ce cas.
{% endhint %}

## Rubriques connexes

* [Gérer les sous-statuts](README.md)
* [Créer un sous-statut](creating-a-substatus.md)
* [Gérer les notifications](../manage-notifications/README.md)
* [Personnaliser les modèles d’e-mail](../manage-notifications/customize-email-templates.md)
