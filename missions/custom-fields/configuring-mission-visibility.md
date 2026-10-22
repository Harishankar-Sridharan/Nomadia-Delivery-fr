# Configurer la visibilité des missions

La visibilité des missions était auparavant déterminée principalement par l’affiliation de l’utilisateur à une agence. Afin d’offrir une plus grande flexibilité et de répondre à des besoins métier variés, les restrictions de visibilité sont désormais étendues pour inclure des règles basées sur des champs personnalisés, en plus des contrôles existants basés sur l’agence.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à l’onglet **Configuration** et à **Gérer les utilisateurs**.
* Assurez-vous qu’un champ personnalisé de type Liste de valeurs existe pour les missions.
* Identifiez les utilisateurs dont vous souhaitez restreindre les missions, ainsi que la valeur du champ personnalisé pour chacun.

## Présentation de la fonctionnalité

* **Bascule de visibilité des missions** : active la visibilité des missions pour un champ personnalisé de mission. Elle ne peut être activée que pour un seul champ à la fois ; un seul champ personnalisé peut donc être utilisé pour contrôler la visibilité des missions.
* **Liste déroulante Visibilité des missions** : apparaît dans la section Mission de l’onglet **Rôles et droits** d’un utilisateur. Elle vous permet de sélectionner la valeur du champ personnalisé associée à l’utilisateur sélectionné.

## Configurer un champ personnalisé comme restriction de visibilité des missions

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Configuration**.

![](<../../.gitbook/assets/image-49 (2).png>)

2. Dans la liste, sélectionnez **Champs personnalisés**.

![](<../../.gitbook/assets/image-50 (2).png>)

3. Cliquez sur l’onglet **Missions**.

![](<../../.gitbook/assets/image-51 (2).png>)

4. Cliquez sur l’icône **crayon** pour modifier tout champ personnalisé existant.

![](<../../.gitbook/assets/image-52 (2).png>)

5. Activez la bascule de visibilité des missions pour le champ.

![](<../../.gitbook/assets/image-53 (2).png>)

6. Cliquez sur **Enregistrer** pour appliquer les modifications.

![](<../../.gitbook/assets/image-54 (2).png>)

## Définir la visibilité des missions selon un champ personnalisé pour les utilisateurs

1. Sélectionnez le menu **Gérer les utilisateurs**.

![](<../../.gitbook/assets/image-55 (2).png>)

2. Cliquez sur l’icône **crayon** pour modifier l’utilisateur requis.

![](<../../.gitbook/assets/image-56 (2).png>)

3. Ouvrez l’onglet **Rôles et droits**.

![](<../../.gitbook/assets/image-57 (2).png>)

4. Dans la section Mission, ouvrez la nouvelle liste déroulante Visibilité des missions pour sélectionner la valeur associée à l’utilisateur sélectionné.

![](<../../.gitbook/assets/image-58 (2).png>)

5. Sélectionnez la valeur du champ personnalisé requise et cliquez sur **Enregistrer**.

![](<../../.gitbook/assets/image-59 (2).png>)

6. Connectez-vous en tant qu’utilisateur configuré et accédez à l’onglet **Missions**.

![](<../../.gitbook/assets/image-60 (2).png>)

7. Cliquez sur l’option **Préfiltre**.

![](<../../.gitbook/assets/image-61 (2).png>)

### Résultat

* Le préfiltre est automatiquement appliqué en fonction du champ personnalisé de visibilité des missions et de la valeur configurée dans les Rôles et droits de l’utilisateur.
* Le préfiltre de visibilité des missions est en lecture seule et ne peut pas être modifié par l’utilisateur.
* Le tableau des missions affiche uniquement les missions qui correspondent à la condition de visibilité des missions, en plus du préfiltre existant basé sur l’agence.

<figure><img src="../../.gitbook/assets/en-image (4).png" alt=""><figcaption></figcaption></figure>

## Conseils

{% hint style="info" %}
**Liste de valeurs uniquement** : la bascule est disponible uniquement pour les champs personnalisés de type Liste de valeurs.
{% endhint %}

{% hint style="warning" %}
**Administrateur requis** : pour supprimer ou modifier le préfiltre de visibilité des missions en lecture seule, contactez l’administrateur.
{% endhint %}

## Rubriques connexes

* [Champs personnalisés](README.md)
* [Regroupement de champs personnalisés](grouping-custom-field.md)
* [Web - Rôles et droits](../../manage-users/web-roles-and-rights.md)
