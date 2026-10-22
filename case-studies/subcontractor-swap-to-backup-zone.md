# Permutation du sous-traitant vers la zone de secours

Cette fonctionnalité vous permet de réattribuer rapidement des missions lorsqu'un sous-traitant principal n'est pas disponible. Vous remapperez les missions concernées vers une zone de secours et un sous-traitant de remplacement en une seule action. Cela garantit que votre charge de travail reste visible pour l'équipe de remplacement et évite les retards de livraison.

#### Pour commencer

Avant de commencer, assurez-vous que les conditions suivantes sont remplies :

* Une zone de secours est déjà créée.
* Un sous-traitant de remplacement est affecté à cette zone de secours.
* Vous avez identifié la sous-zone principale qui nécessite une couverture.
* Ouvrez le **Missions** onglet pour commencer l'échange.

<figure><img src="../.gitbook/assets/image (868).png" alt=""><figcaption></figcaption></figure>

#### Présentation de la fonctionnalité

* **Panneau de filtrage**: Utilisez-le pour isoler les missions appartenant à une sous-zone spécifique.

<figure><img src="../.gitbook/assets/image (869).png" alt=""><figcaption></figcaption></figure>

* **Tableau des missions**: Affiche la liste filtrée des missions nécessitant une réattribution.

<figure><img src="../.gitbook/assets/image (870).png" alt=""><figcaption></figcaption></figure>

* **menu Actions**: Contient l'outil permettant de réattribuer plusieurs missions à la fois.
* **Attribuer au sous-traitant**: Ouvre la fenêtre contextuelle pour modifier le propriétaire de la mission et les zones.

<figure><img src="../.gitbook/assets/image (871).png" alt=""><figcaption></figcaption></figure>

* **Attribuer les zones principales**: Un interrupteur permettant d'attribuer les missions au territoire principal du sous-traitant.
* **Attribuer la zone secondaire**: Un interrupteur permettant d'attribuer les missions spécifiquement à la zone de secours.
* **Sélectionner le tableau des sous-traitants**: Répertorie les sous-traitants disponibles et leur couverture géographique pour les missions sélectionnées.
* **Appliquer**: Exécute la modification sur tous les enregistrements de mission sélectionnés.

#### Mode d'emploi : isoler les missions concernées

1. Accédez à **Panneau de filtrage** et saisissez « sector ».
2. Choisissez le **Parmi** option de filtrage.
3. Sélectionnez la sous-zone principale qui nécessite un échange de secours.

<figure><img src="../.gitbook/assets/image (872).png" alt=""><figcaption></figcaption></figure>

#### Mode d'emploi : échanger les sous-traitants

1. Sélectionnez toutes les missions dans le **Tableau des missions**.
2. Ouvrez le **menu Actions** et cliquez sur **Attribuer au sous-traitant**.

<figure><img src="../.gitbook/assets/image (873).png" alt=""><figcaption></figcaption></figure>

3. Assurez-vous que le **Attribuer les zones principales** interrupteur est désactivé.
4. Activez la **Attribuer la zone secondaire** interrupteur.
5. Sélectionnez le sous-traitant de remplacement affichant une couverture à 100 % dans le **Sélectionner le tableau des sous-traitants**.
6. Cliquez sur **Appliquer** pour finaliser l'échange.

<figure><img src="../.gitbook/assets/image (874).png" alt=""><figcaption></figcaption></figure>

#### Mode d'emploi : vérifier l'échange

1. Retournez au **Panneau de filtrage** et recherchez « sector ».
2. Sélectionnez le **Parmi** opérateur.
3. Choisissez la zone de secours que vous venez d'attribuer.
4. Confirmez que les missions apparaissent maintenant sous la bonne zone de secours et le bon sous-traitant.

<figure><img src="../.gitbook/assets/image (875).png" alt=""><figcaption></figcaption></figure>

#### Conseils de productivité

* 💡 **Efficacité**: Une seule action met simultanément à jour le secteur, le sous-traitant et le livreur pour toutes les missions.
* ⚠️ **Itinéraire du conducteur**: Si aucun livreur n'est affecté à la zone de secours, le système efface le conducteur existant. Cela évite que des missions soient routées vers des conducteurs qui ne sont plus responsables du territoire.
* 💡 **Validation de la couverture**: Recherchez une couverture à 100 % dans le tableau des sous-traitants afin de vous assurer que leur zone de secours correspond aux missions sélectionnées.
