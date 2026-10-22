# Restrictions des sous-traitants

Les restrictions des sous-traitants vous permettent de contrôler précisément l’accès aux modèles et aux autorisations de modification des missions.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès à l’onglet **Configuration**.
* Assurez-vous que le sous-traitant existe déjà et, pour la seconde procédure, que l’utilisateur sous-traitant existe également.

## Présentation de la fonctionnalité

Dans la section **Missions** des détails du sous-traitant, plusieurs restrictions peuvent être appliquées aux sous-traitants.

* **Modèle d’extraction de mission** : permet aux utilisateurs de sélectionner uniquement les modèles d’extraction de mission applicables au sous-traitant.
* **Modèle d’étiquette** : permet aux utilisateurs de sélectionner uniquement les modèles d’étiquette applicables au sous-traitant.
* **Édition groupée** : permet aux utilisateurs de sélectionner uniquement les configurations de modification applicables au sous-traitant.

## Restreindre les sous-traitants à des modèles spécifiques

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Configuration**.

![](<../.gitbook/assets/image-67 (2).png>)

2. Cliquez sur la page **Sous-traitants** dans l’en-tête principal.

![](<../.gitbook/assets/image-68 (2).png>)

3. Cliquez sur l’icône **Crayon** pour modifier les détails du sous-traitant.

![](<../.gitbook/assets/image-69 (2).png>)

4. Appliquez les restrictions dans la section **Missions**.

![](<../.gitbook/assets/image-70 (2).png>)

5. Cliquez sur **Enregistrer** pour appliquer les restrictions au sous-traitant sélectionné.

![](<../.gitbook/assets/image-71 (2).png>)

## Empêcher les sous-traitants de modifier les missions après impression

1. Ouvrez l’application Nomadia Delivery et accédez à l’onglet **Configuration**.

![](<../.gitbook/assets/image-72 (2).png>)

2. Sélectionnez **Gérer les utilisateurs** dans la liste.

![](<../.gitbook/assets/image-73 (2).png>)

3. Cliquez sur l’icône **Crayon** pour modifier un utilisateur sous-traitant.

![](<../.gitbook/assets/image-74 (2).png>)

4. Cliquez sur l’onglet **Rôles et droits**.
5. Dans la section **Missions**, désactivez le droit **Modifier la mission après impression**.

![](<../.gitbook/assets/image-75 (2).png>)

6. Cliquez sur **Enregistrer** pour appliquer les modifications.

![](<../.gitbook/assets/image-76 (2).png>)

7. Accédez à l’onglet **Missions** et sélectionnez une mission en attente.

![](<../.gitbook/assets/image-77 (2).png>)

8. Cliquez sur le menu **Actions** et sélectionnez **Générer des étiquettes autocollantes**.

![](<../.gitbook/assets/image-78 (2).png>)

9. Cliquez sur le bouton **Imprimer** pour générer l’étiquette autocollante.

![](<../.gitbook/assets/image-79 (2).png>)

10. Cliquez sur l’icône **Crayon** pour modifier la mission après impression.

![](<../.gitbook/assets/image-77 (2).png>)

### Résultat

Un avertissement apparaît dans l’éditeur de mission, et la modification de la mission est bloquée car l’utilisateur n’a pas l’autorisation de la modifier après l’impression des étiquettes autocollantes.

![](<../.gitbook/assets/image-81 (2).png>)

Cela garantit une meilleure traçabilité et protège les données de mission une fois les documents générés.

## Conseils

{% hint style="info" %}
**Limiter les modèles par sous-traitant** : appliquez les restrictions dans la section **Missions** des détails du sous-traitant afin que les utilisateurs sélectionnent uniquement les modèles et les configurations de modification applicables au sous-traitant.
{% endhint %}

{% hint style="warning" %}
**Modification après impression** : lorsque le droit **Modifier la mission après impression** est désactivé, la modification de la mission est bloquée après l’impression des étiquettes autocollantes, ce qui protège les données de mission une fois les documents générés.
{% endhint %}

## Rubriques connexes

* [Sous-traitants](README.md)
* [Enregistrer un sous-traitant](register-a-contractor.md)
* [Créer un utilisateur sous-traitant](create-a-contractor-user.md)
* [Personnalisation des modèles Word](../manage-document-templates/customizing-word-templates.md)
