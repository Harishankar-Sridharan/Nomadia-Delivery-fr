# Créneaux de réservation

Le portail de réservation I-Frame offre aux transporteurs une solution de réservation flexible et fluide, pouvant être directement intégrée aux sites web des sous-traitants. Utilisez-le pour renforcer l’engagement client en permettant la réservation optimisée de créneaux de livraison et en offrant une expérience utilisateur sans friction.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à l’onglet **Configuration**.
* Sachez quelles informations vous devez recueillir auprès des clients pour réussir la livraison, car vous les configurez sous forme de champs.
* Disposez d’un accès au site web du sous-traitant, ou au sous-traitant lui-même, afin que l’exemple de code puisse être intégré.

## Présentation de la fonctionnalité

* **Afficher le portail de réservation** : bouton qui active le portail de réservation.
* **Ajouter un champ** : ajoute un champ personnalisé pour recueillir les informations nécessaires à la bonne livraison. Par défaut, Nom et Adresse sont obligatoires, car ils sont essentiels pour localiser le client.
* **Type de champ** : Texte, Case à cocher, Texte multiligne, Liste de valeurs, Nombre ou date.
* **Mode** : Saisie obligatoire, Masqué, Lecture seule ou Lecture/écriture, afin de définir le niveau de contrôle du client lors du remplissage du formulaire.

## Configurer le portail de réservation

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Configuration**.
2. Dans le menu déroulant, sélectionnez **Configurer les pages d’expérience client**.

![](<../../.gitbook/assets/image-17 (3).png>)

3. Choisissez l’élément de menu **Planifier une livraison**.
4. Ouvrez l’**onglet Portail de réservation**.
5. Activez le bouton **Afficher le portail de réservation.**
6. Configurez les champs que vous souhaitez afficher au client final afin de recueillir les informations nécessaires à la bonne livraison.
7. Cliquez sur **Ajouter un champ** pour inclure des champs supplémentaires.

![](<../../.gitbook/assets/image-18 (3).png>)

8. Spécifiez le **nom du champ** et sélectionnez le **type de champ** **(Texte, Case à cocher, Texte multiligne, Liste de valeurs, Nombre ou date).**

Exemple : Nom du champ – Code d’accès (le code dont le livreur a besoin pour accéder aux locaux du client).

9. Choisissez le mode du champ, comme Saisie obligatoire, Masqué, Lecture seule ou Lecture/écriture, afin de définir le niveau de contrôle du client lors du remplissage du formulaire.

![](<../../.gitbook/assets/image-19 (3).png>)

10. Cliquez sur **Ajouter** pour inclure le champ personnalisé dans le formulaire.

![](<../../.gitbook/assets/image-20 (3).png>)

Le champ apparaît désormais dans la liste des données à collecter auprès du client.

![](<../../.gitbook/assets/image-21 (3).png>)

## Intégrer le portail de réservation au site web du sous-traitant

1. Copiez l’exemple de code depuis le portail de réservation.

![](<../../.gitbook/assets/image-22 (3).png>)

2. Partagez l’exemple de code avec le sous-traitant pour intégration.

L’URL dans l’exemple de code redirige automatiquement vers le portail de réservation et peut être intégrée dans une I-frame sur le site web du sous-traitant.

![](<../../.gitbook/assets/image-23 (3).png>)

L’I-frame permet aux clients de planifier directement les livraisons.

3. Cliquez sur **Programmer** (en tant que client) pour afficher en temps réel les créneaux horaires optimisés.
4. Sélectionnez votre créneau préféré et cliquez sur **Choisir**.

![](<../../.gitbook/assets/image-24 (3).png>)

### Résultat

Le portail de réservation est directement lié aux plans de tournée des livreurs dans l’application Nomadia Delivery. Une fois la réservation confirmée :

* Une mission est automatiquement créée.
* La mission est planifiée de manière optimale et ajoutée à la tournée en temps réel du livreur.

![](<../../.gitbook/assets/image-25 (3).png>)

## Conseils

{% hint style="info" %}
**Avantages** : le portail de réservation I-Frame aide les transporteurs à renforcer leur présence numérique et l’engagement client en proposant une intégration fluide, des formulaires de réservation personnalisables, une administration facile, des créneaux de livraison optimisés et des notifications de confirmation de créneau.
{% endhint %}

## Rubriques connexes

* [Portail de réservation](../README.md)
* [Configurer le portail](configure-the-portal.md)
* [Configuration du report](../reschedule-configuration.md)
