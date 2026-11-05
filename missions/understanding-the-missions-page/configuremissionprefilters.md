# Configurer les pré-filtres de mission

La fonctionnalité **Configurer les pré-filtres de missions gérées** permet de créer des règles de filtrage personnalisées basées sur le statut et le type de mission dans **Nomadia Delivery**. Vous avez besoin de cette fonctionnalité pour contrôler la visibilité de la flotte et centrer les flux de travail sur des tâches opérationnelles précises. En configurant des pré-filtres, vous simplifiez le suivi et optimisez la gestion des missions au sein de votre équipe. Les pré-filtres peuvent aussi utiliser vos champs personnalisés de mission, pour filtrer la liste des missions selon les attributs qui comptent pour votre activité, et vous choisissez les pré-filtres que chaque utilisateur peut voir.

## Avant de commencer

Prérequis et exigences :

* Accès à **Nomadia Delivery** avec des droits d’administrateur ou de répartiteur.
* Des enregistrements de missions actifs configurés dans le système.
* Un navigateur Web connecté à la plateforme SaaS.
* Pour filtrer sur des champs personnalisés, assurez-vous que les champs personnalisés de mission existent. Voir [Champs personnalisés](../custom-fields/README.md).

Étapes de configuration initiale :

1. Ouvrez la page **Configuration**.
2. Sélectionnez **Pré-filtres de missions** dans la liste des paramètres.

![Sélectionnez Pré-filtres de missions dans la liste des paramètres](../../.gitbook/assets/MissionPrefilters_BeforeBegin_001.gif)

3. Cliquez sur **Actions** et sélectionnez **Ajouter** pour ouvrir le générateur de configuration de filtre.

## Présentation de la fonctionnalité

* **Champ Statut** : sélectionne des statuts opérationnels de mission précis pour la requête. Il filtre la vue de la flotte afin d’afficher les statuts de mission pertinents.
* **Champ Type de mission** : indique les catégories de missions incluses dans le filtre. Il limite les résultats de la requête aux types de mission désignés.
* **Opérateur logique (ET/OU)** : bascule la logique conditionnelle entre les règles de filtre. Il détermine si toutes les conditions ou seulement l’une d’entre elles doivent être remplies.
* **Condition de groupe** : combine plusieurs instructions de filtre en un groupe logique. Elle permet une logique de filtrage imbriquée complexe.
* **Champ Nom de la requête** : accepte un libellé de texte personnalisé pour la requête de filtre. Il aide les utilisateurs à identifier facilement les configurations de filtre enregistrées.
* **Symbole plus de traduction** : ouvre des champs de saisie de traduction pour d’autres langues. Il permet la prise en charge multilingue pour les répartiteurs régionaux.
* **Bouton Supprimer la langue** : supprime une traduction de langue ajoutée. Il supprime de la requête les champs de langue inutiles.
* **Option Gérer l’utilisation** : ouvre les paramètres d’affectation d’accès utilisateur pour les pré-filtres. Elle détermine quels utilisateurs reçoivent des vues de missions restreintes.
* **Étiquette Personnalisé** : étiquette affichée à côté de chaque champ personnalisé dans la liste des champs des critères, pour distinguer les champs personnalisés des champs standard. Les nouveaux champs personnalisés apparaissent instantanément dans la liste, sans configuration supplémentaire.
* **Comparaisons par type de champ** : les comparaisons proposées dépendent du type du champ, par exemple **parmi** et **aucun de** pour une liste de valeurs, **contient**, **égal à**, **est vide** et **n’est pas vide** pour un texte, et **égal à**, **supérieur à** et **inférieur à** pour un nombre. Les dates et les champs oui/non sont aussi pris en charge.

## Créer et personnaliser un pré-filtre de mission

1. Ouvrez la page **Configuration** et cliquez sur **Pré-filtres de missions**.

2. Cliquez sur **Actions** et sélectionnez **Ajouter** pour lancer l’éditeur.

3. Choisissez les valeurs de statut requises dans le **Champ Statut**.

![Choisissez les valeurs de statut requises dans le Champ Statut](../../.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_001.png)

4. Choisissez les catégories de missions requises dans le **Champ Type de mission**.

![Choisissez les catégories de missions requises dans le Champ Type de mission](../../.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_002.png)

5. Cliquez pour ajouter des conditions de statut supplémentaires si nécessaire.

![Cliquez pour ajouter des conditions de statut supplémentaires si nécessaire](../../.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_003.png)

6. Sélectionnez la logique **ET** ou **OU** pour relier vos conditions.

![Sélectionnez la logique ET ou OU pour relier vos conditions](../../.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_004.gif)

7. Regroupez les conditions si vous combinez plusieurs règles de filtre.

![Regroupez les conditions si vous combinez plusieurs règles de filtre](../../.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_005.gif)

8. Saisissez un libellé clair et descriptif dans le **Champ Nom de la requête**.
9. Cliquez sur **Enregistrer** pour créer la requête de filtre.

![Cliquez sur Enregistrer pour créer la requête de filtre](../../.gitbook/assets/MissionPrefilters_CreateCustomizeMissionPre_006.png)

## Ajouter un champ personnalisé à un pré-filtre de missions

1. Vérifiez vos champs personnalisés de mission et leur type, par exemple liste de valeurs, nombre ou texte.

![Les champs personnalisés de mission et leur type](../../.gitbook/assets/PrefilterCustomFields_FR_001.jpg)

2. Accédez à **Configuration** > **Préfiltres de missions**, puis cliquez sur l’**icône crayon** à côté d’un préfiltre, ou cliquez sur **Actions** > **Ajouter** pour en créer un.
3. Sous **Critères**, ouvrez la liste des champs d’une condition. Les champs personnalisés apparaissent avec l’étiquette **Personnalisé**. Sélectionnez un champ personnalisé.

![Les champs personnalisés avec l’étiquette Personnalisé dans la liste des champs](../../.gitbook/assets/PrefilterCustomFields_FR_002.jpg)

4. Choisissez la comparaison. Les comparaisons dépendent du type du champ :

   * Pour une liste de valeurs, choisissez **parmi** ou **aucun de**, puis sélectionnez les valeurs directement dans la liste.

![Les comparaisons d’un champ de type liste](../../.gitbook/assets/PrefilterCustomFields_FR_004.jpg)

![Sélectionnez les valeurs dans la liste](../../.gitbook/assets/PrefilterCustomFields_FR_005.jpg)

   * Pour un texte, choisissez **contient**, **égal à**, **est vide** ou **n’est pas vide**, puis saisissez le texte.

![Les comparaisons d’un champ de type texte](../../.gitbook/assets/PrefilterCustomFields_FR_006.jpg)

   * Pour un nombre, choisissez **égal à**, **supérieur à** ou **inférieur à**, puis saisissez le nombre.

![Les comparaisons d’un champ de type nombre](../../.gitbook/assets/PrefilterCustomFields_FR_003.jpg)

5. Ajoutez d’autres conditions si nécessaire, avec des champs standard comme **Statut** et des champs personnalisés, et reliez-les par **ET** ou **OU**.

![Un préfiltre qui combine champs standard et champs personnalisés](../../.gitbook/assets/PrefilterCustomFields_FR_008.jpg)

6. Cliquez sur **Enregistrer**.

## Ajouter des traductions à une requête de pré-filtre

1. Cliquez sur le **Symbole plus de traduction** à côté du champ de traduction.

![Cliquez sur le Symbole plus de traduction à côté du champ de traduction](../../.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_001.gif)

2. Sélectionnez votre langue cible dans la liste déroulante.

![Sélectionnez votre langue cible dans la liste déroulante](../../.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_002.png)

3. Saisissez le nom de la requête dans la langue sélectionnée.

![Saisissez le nom de la requête dans la langue sélectionnée](../../.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_003.gif)

4. Cliquez sur le **Bouton Supprimer la langue** si vous souhaitez supprimer une langue.

![Cliquez sur le Bouton Supprimer la langue si vous souhaitez supprimer une langue](../../.gitbook/assets/MissionPrefilters_AddTranslationsPreFilter_004.gif)

5. Cliquez sur **Enregistrer** pour mettre à jour les traductions.

## Affecter une requête de pré-filtre à un utilisateur

1. Ouvrez la page **Configuration** et cliquez sur **Gérer les utilisateurs**.

![Ouvrez la page Configuration et cliquez sur Gérer les utilisateurs](../../.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_001.gif)

2. Sélectionnez l’adresse e-mail de l’utilisateur cible.

![Sélectionnez l’adresse e-mail de l’utilisateur cible](../../.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_002.gif)

3. Repérez la section **Pré-filtres de missions**.

![Repérez la section Pré-filtres de missions](../../.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_003.png)

4. Sélectionnez le nom de la requête à affecter, par exemple **En cours de livraison**.

![Sélectionnez le nom de la requête à affecter, par exemple En cours de livraison](../../.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_004.gif)

5. Cliquez sur **Enregistrer** pour appliquer l’affectation.

![Cliquez sur Enregistrer pour appliquer l’affectation](../../.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_005.png)

6. Accédez à **Missions** dans le menu principal.
7. Cliquez sur **Appliquer** pour afficher uniquement les missions correspondant au statut affecté.

![Cliquez sur Appliquer pour afficher uniquement les missions du statut affecté](../../.gitbook/assets/MissionPrefilters_AssignPreFilterQuery_006.gif)

Vous pouvez aussi ouvrir l’utilisateur avec l’**icône crayon** dans **Gérer les utilisateurs**. Le champ **Pré-filtres de missions** se trouve dans l’onglet **Accès**, où vous sélectionnez chaque préfiltre que l’utilisateur peut voir.

### Résultat

L’utilisateur ne voit que les préfiltres qui le concernent. Si aucun préfiltre n’est sélectionné, le champ affiche **Aucune restriction**.

## Appliquer un préfiltre dans la liste des missions

1. Sur la page **Missions**, cliquez sur la zone de préfiltre en haut à gauche de la page pour ouvrir le panneau **Préfiltrer vos missions et vos tournées par**.
2. Dans **Configuration de préfiltre de missions**, choisissez le préfiltre. Le panneau indique le nombre de missions correspondantes.
3. Cliquez sur **Appliquer**.

### Résultat

La liste des missions n’affiche que les missions qui correspondent au préfiltre, par exemple 22 missions sur 364.

## Supprimer un pré-filtre affecté à un utilisateur

1. Ouvrez la page **Configuration** et sélectionnez **Gérer les utilisateurs**.
2. Cliquez sur l’adresse e-mail de l’utilisateur.
3. Effacez la requête affectée sous **Pré-filtres de missions**.

![Effacez la requête affectée sous Pré-filtres de missions](../../.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_001.gif)

4. Cliquez sur **Enregistrer** pour mettre à jour les paramètres du profil utilisateur.

![Cliquez sur Enregistrer pour mettre à jour les paramètres du profil utilisateur](../../.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_002.png)

5. Accédez à **Missions** et effacez les sélections de filtres actives.

![Accédez à Missions et effacez les sélections de filtres actives](../../.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_003.gif)

6. Cliquez sur **Appliquer** pour afficher à nouveau toutes les missions de la flotte.

![Cliquez sur Appliquer pour afficher à nouveau toutes les missions de la flotte](../../.gitbook/assets/MissionPrefilters_RemoveAssignedPreFilter_004.gif)

## Conseils

{% hint style="info" %}
**Adaptabilité multilingue** : l’ajout de traductions garantit que les membres d’équipes internationales voient les titres des requêtes de filtre dans leur langue préférée.
{% endhint %}

{% hint style="warning" %}
**Visibilité masquée de la flotte** : tant qu’un pré-filtre reste affecté, les répartiteurs ne peuvent pas voir l’ensemble de la flotte ; supprimez l’affectation pour y remédier.
{% endhint %}

{% hint style="info" %}
**Un préfiltre, tous vos critères** : combinez champs standard et champs personnalisés dans un seul préfiltre plutôt que de créer plusieurs préfiltres.
{% endhint %}

## Rubriques connexes

* Pré-filtres
* Définir l’affichage des missions (préfiltre)
* [Comprendre la page des missions](README.md)
* [Champs personnalisés](../custom-fields/README.md)
