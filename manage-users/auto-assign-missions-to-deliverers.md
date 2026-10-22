# Affectation automatique des missions aux livreurs

La fonctionnalité d’affectation automatique dans Nomadia Delivery simplifie la répartition en attribuant automatiquement les missions aux bons livreurs et véhicules, en fonction de zones spatiales ou postales prédéfinies. Cela réduit les tâches manuelles, limite la charge administrative et améliore l’efficacité, en particulier dans les opérations à fort volume.

Prérequis : pour utiliser l’affectation automatique des missions, vous devez disposer au préalable d’une zone de code postal ou d’une zone spatiale configurée. Pour un guide pas à pas, reportez-vous au guide Création de zones par sectorisation automatique.

Suivez les étapes ci-dessous pour associer des zones aux utilisateurs et aux véhicules :

1. Ouvrez l'application Nomadia Delivery et accédez à l'onglet **onglet Configuration.**
2. Dans la liste déroulante, sélectionnez **Gérer les utilisateurs**.

**Remarque**: Les zones ne peuvent être associées qu’aux utilisateurs disposant d’un accès mobile.

3. Cliquez sur le **crayon** icône à côté de l’utilisateur mobile souhaité.

<figure><img src="../.gitbook/assets/msedge_J4ptMOEI4U.png" alt=""><figcaption></figcaption></figure>

4. Les utilisateurs disposant d’un accès mobile verront un onglet supplémentaire pour configurer les droits sur les zones. Cliquez sur **Agences** et **zones** pour configurer les affectations de zones.
5. Déplacez les zones disponibles des agences associées vers le panneau de droite pour les attribuer à l’utilisateur.
6. Après avoir ajusté les paramètres de zone, cliquez sur **Enregistrer** pour confirmer les modifications.

<figure><img src="../.gitbook/assets/image (972).png" alt=""><figcaption></figcaption></figure>

Si l’utilisateur est lié à un véhicule, tous les paramètres de zone se synchroniseront automatiquement avec ce véhicule.

<figure><img src="../.gitbook/assets/msedge_mi4B2IG1k9.png" alt=""><figcaption></figcaption></figure>

Nomadia Delivery permet également, dans des cas exceptionnels tels qu’un arrêt maladie ou une indisponibilité soudaine, d’attribuer les utilisateurs et les véhicules à différentes zones. Dans ce type de situation, une erreur de synchronisation apparaîtra dans la section Générale du véhicule.

<figure><img src="../.gitbook/assets/Image 12.png" alt=""><figcaption></figcaption></figure>

Une fois que les utilisateurs et les véhicules sont correctement synchronisés avec leurs paramètres de zone, les missions sont automatiquement attribuées en fonction de l’alignement spatial. Si le point de retrait ou de livraison d’une mission se trouve dans une zone configurée, l’utilisateur ou le véhicule correspondant lié à cette zone est automatiquement attribué, et le champ Livreur planifié est mis à jour.

<figure><img src="../.gitbook/assets/image (973).png" alt=""><figcaption></figcaption></figure>

Si plusieurs utilisateurs partagent la même zone, le système attribue la mission au premier utilisateur.

<figure><img src="../.gitbook/assets/Image 13.png" alt=""><figcaption></figcaption></figure>

Pendant l’optimisation, le planificateur dispose de trois options :

* Utiliser uniquement le livreur planifié affecté automatiquement.
* Autoriser la prise en compte de tous les véhicules compatibles pour l’optimisation.
* Ignorer les livreurs affectés automatiquement.

<figure><img src="../.gitbook/assets/image 15.png" alt=""><figcaption></figcaption></figure>
