# Hériter des données de mission depuis la liste des sous-traitants et des adresses

Cette fonctionnalité accélère la création des missions en héritant automatiquement des données des champs personnalisés, ce qui réduit la saisie manuelle. En initialisant automatiquement les champs, vous n’avez pas besoin de ressaisir les mêmes données lors de la création de la mission, ce qui améliore la cohérence et l’efficacité.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à l’onglet **Configuration**.
* Assurez-vous qu’un champ personnalisé de mission existant est disponible pour modification.
* Assurez-vous que le sous-traitant ou l’entrée de la liste d’adresses qui doit fournir la valeur existe.

## Présentation de la fonctionnalité

* **Peut être initialisé par** : liste déroulante qui définit si un champ personnalisé est hérité du sous-traitant ou de la liste d’adresses.
* **Champs personnalisés pour les missions** : section du sous-traitant (section Champs personnalisés) et de l’adresse (section Autres données) qui liste les champs hérités par les missions.
* **Onglet Liste d’adresses** : onglet du sous-traitant où vous modifiez une adresse et définissez ses valeurs héritées.

## Activer l’héritage des champs personnalisés

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Configuration**.

![](<../../.gitbook/assets/image-34 (2).png>)

2. Sélectionnez **Champs personnalisés** dans la liste.

![](<../../.gitbook/assets/image-35 (2).png>)

3. Sélectionnez l’onglet **Missions**.

![](<../../.gitbook/assets/image-36 (2).png>)

4. Cliquez sur l’icône **crayon** pour modifier un champ personnalisé existant.

![](<../../.gitbook/assets/image-37 (2).png>)

5. Dans la liste déroulante **Peut être initialisé par**, choisissez si le champ est hérité du sous-traitant ou de la liste d’adresses.

![](<../../.gitbook/assets/image-38 (2).png>)

6. Cliquez sur le bouton **Enregistrer** pour appliquer les modifications.

![](<../../.gitbook/assets/image-39 (2).png>)

## Définir les valeurs héritées dans le sous-traitant et la liste d’adresses

1. Depuis l’en-tête principal, cliquez sur la page **Sous-traitants**.

![](<../../.gitbook/assets/image-40 (2).png>)

2. Cliquez sur l’icône **crayon** pour modifier le sous-traitant.

![](<../../.gitbook/assets/image-41 (2).png>)

3. Dans la section Champs personnalisés, retrouvez tous les champs hérités par les missions depuis le sous-traitant sous **Champs personnalisés pour les missions**.

![](<../../.gitbook/assets/image-42 (2).png>)

4. Cliquez sur l’onglet **Liste d’adresses**.

![](<../../.gitbook/assets/image-43 (2).png>)

5. Cliquez sur l’icône **crayon** pour modifier une adresse.

![](<../../.gitbook/assets/image-44 (2).png>)

6. Dans la section Autres données, retrouvez tous les champs hérités par les missions depuis l’adresse sous **Champs personnalisés pour les missions**.

![](<../../.gitbook/assets/image-45 (2).png>)

7. Sélectionnez une valeur pour le champ personnalisé dans le sous-traitant ou la liste d’adresses, puis cliquez sur **Enregistrer** pour appliquer les modifications.

![](<../../.gitbook/assets/image-46 (2).png>)

### Résultat

Lorsque vous créez une mission, les champs personnalisés de la mission sont automatiquement renseignés en fonction du sous-traitant ou de l’adresse sélectionné(e) dans la liste d’adresses.

![](<../../.gitbook/assets/image-48 (2).png>)

## Conseils

{% hint style="info" %}
**Deux sources** : un champ personnalisé peut être initialisé à partir du sous-traitant et de la liste d’adresses en même temps. Dans ce cas, la valeur de la liste d’adresses a priorité sur celle du sous-traitant.
{% endhint %}

## Rubriques connexes

* [Champs personnalisés](README.md)
* [Enregistrer un sous-traitant](../../contractors/register-a-contractor.md)
* [Gérer la liste d’adresses](../../contractors/manage-address-list.md)
