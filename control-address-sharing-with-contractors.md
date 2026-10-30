# Contrôler le partage des adresses avec les donneurs d’ordres

Le contrôle du partage des adresses avec les donneurs d’ordres vous permet de choisir quelles entrées de la liste générale d’adresses vos donneurs d’ordres peuvent voir. Vous pouvez garder une adresse sensible privée, vérifier d’un coup d’œil le statut de partage de chaque entrée, et partager ou arrêter de partager plusieurs adresses en une seule étape.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** en tant qu’administrateur ou utilisateur back-office ayant accès à l’onglet **Configuration**.
* Assurez-vous que les adresses que vous souhaitez gérer existent dans la liste générale d’adresses. Voir [Gérer la liste globale d’adresses](manage-global-address-list.md).

## Présentation de la fonctionnalité

* **Carnet d’adresses** : liste générale d’adresses utilisée dans toute votre organisation, accessible dans **Configuration**.
* **Colonne Partagé avec les donneurs d’ordres** : colonne qui indique, pour chaque adresse, si les donneurs d’ordres peuvent la voir (**Oui** ou **Non**). Vous pouvez filtrer cette colonne.
* **Interrupteur Partagé avec les donneurs d’ordres** : interrupteur présent dans chaque adresse qui active ou désactive le partage avec les donneurs d’ordres. Il est activé par défaut.
* **Menu Actions** : menu qui contient **Share with contractors** et **Stop sharing with contractors** pour les adresses sélectionnées.
* **Modifier** : bouton qui enregistre les modifications d’une adresse.

## Ouvrir le carnet d’adresses

1. En tant qu’administrateur ou utilisateur back-office, ouvrez l’onglet **Configuration**.

![Ouvrez l’onglet Configuration](.gitbook/assets/ControlAddressSharing_FR_001.jpg)

2. Dans la zone de recherche, saisissez **Adresse**, puis ouvrez **Carnet d’adresses**.

![Recherchez Adresse et ouvrez le Carnet d’adresses](.gitbook/assets/ControlAddressSharing_FR_002.jpg)

La page **Carnet d’adresses** s’ouvre. Il s’agit de votre liste générale d’adresses, utilisée dans toute votre organisation.

![La page Carnet d’adresses](.gitbook/assets/ControlAddressSharing_FR_003.jpg)

## Vérifier le statut de partage des adresses

1. Dans le **Carnet d’adresses**, consultez la colonne **Partagé avec les donneurs d’ordres**. Elle indique le statut de partage de chaque adresse.

![La colonne Partagé avec les donneurs d’ordres](.gitbook/assets/ControlAddressSharing_FR_004.jpg)

2. Pour afficher uniquement les adresses que vos donneurs d’ordres peuvent actuellement voir, saisissez **Oui** dans le filtre de la colonne **Partagé avec les donneurs d’ordres**.

![Saisissez Oui dans le filtre Partagé avec les donneurs d’ordres](.gitbook/assets/ControlAddressSharing_FR_005.jpg)

### Résultat

La liste affiche uniquement les adresses partagées avec les donneurs d’ordres.

![La liste filtrée sur les adresses partagées avec les donneurs d’ordres](.gitbook/assets/ControlAddressSharing_FR_006.jpg)

## Arrêter de partager une adresse avec les donneurs d’ordres

1. Dans le **Carnet d’adresses**, cliquez sur l’**icône crayon** à côté de l’adresse pour l’ouvrir.
2. Repérez l’interrupteur **Partagé avec les donneurs d’ordres**. Il est activé par défaut : rien ne change tant que vous ne le désactivez pas.

![L’interrupteur Partagé avec les donneurs d’ordres sur Oui](.gitbook/assets/ControlAddressSharing_FR_007.jpg)

3. Désactivez l’interrupteur pour qu’il affiche **Non**.

![L’interrupteur Partagé avec les donneurs d’ordres sur Non](.gitbook/assets/ControlAddressSharing_FR_008.jpg)

4. Cliquez sur **Modifier** pour enregistrer.

![Cliquez sur Modifier](.gitbook/assets/ControlAddressSharing_FR_009.jpg)

### Résultat

Une notification confirme que l’adresse a été mise à jour. Si la liste est filtrée sur **Oui**, l’adresse n’est plus partagée et disparaît donc de la liste.

![L’adresse est mise à jour et retirée de la liste des adresses partagées](.gitbook/assets/ControlAddressSharing_FR_010.jpg)

## Partager ou arrêter de partager plusieurs adresses

1. Dans le **Carnet d’adresses**, cochez les cases des adresses que vous souhaitez mettre à jour.

![Sélectionnez les adresses à mettre à jour](.gitbook/assets/ControlAddressSharing_FR_011.jpg)

2. Cliquez sur **Actions**, puis sur **Share with contractors** ou **Stop sharing with contractors**.

![Cliquez sur Actions et choisissez Share with contractors ou Stop sharing with contractors](.gitbook/assets/ControlAddressSharing_FR_012.jpg)

### Résultat

Toutes les adresses sélectionnées sont mises à jour en une seule étape, et une notification confirme la mise à jour.

![Toutes les adresses sélectionnées sont mises à jour](.gitbook/assets/ControlAddressSharing_FR_013.jpg)

## Conseils

{% hint style="info" %}
**Ce que voient les donneurs d’ordres** : les adresses non partagées n’apparaissent plus dans les recherches d’adresses ni dans les sélecteurs d’adresses des donneurs d’ordres, que ce soit dans l’interface ou via l’API. Les missions déjà affectées à ces adresses ne sont pas modifiées.
{% endhint %}

## Rubriques connexes

* [Gérer la liste globale d’adresses](manage-global-address-list.md)
* [Gérer la liste d’adresses](contractors/manage-address-list.md)
* [Personnaliser la visibilité des adresses](contractors/customizetheaddresslistvisibility.md)
