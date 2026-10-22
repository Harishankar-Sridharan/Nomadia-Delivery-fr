# Configuration PUDO

PUDO (points de prise en charge et de dépôt) permet aux chauffeurs de déposer des colis dans des emplacements sécurisés lorsque les clients ne sont pas disponibles. Cette fonctionnalité élimine les coûts élevés de relivraison et réduit les émissions des véhicules. Vous obtiendrez des taux de réussite plus élevés dès la première tentative et un meilleur confort pour les clients.

#### Pour commencer

* Une liste préparée des emplacements PUDO comprenant les noms et les adresses.
* Des catégories définies pour votre réseau, telles que des consignes ou des magasins.
* Accès au **Configuration** module dans Nomadia Delivery.
* Ouvrez le **Configuration** module.

<figure><img src="../../.gitbook/assets/image (889).png" alt=""><figcaption></figcaption></figure>

* Sélectionnez le **type de PUDO** page pour définir vos catégories.

<figure><img src="../../.gitbook/assets/image (890).png" alt=""><figcaption></figcaption></figure>

* Accédez à **PUDO** page pour importer vos emplacements physiques.

<figure><img src="../../.gitbook/assets/image (891).png" alt=""><figcaption></figcaption></figure>

#### Présentation de la fonctionnalité

* **Types de PUDO**: Catégories comme des magasins ou des consignes avec des exigences de traitement spécifiques.

<figure><img src="../../.gitbook/assets/image (892).png" alt=""><figcaption></figcaption></figure>

* **Liste PUDO**: La base de données des emplacements réels et des adresses utilisés par votre activité.

<figure><img src="../../.gitbook/assets/image (893).png" alt=""><figcaption></figcaption></figure>

* **Sous-statut PUDO**: Des libellés personnalisés pour l’application mobile, qui s’appliquent uniquement pendant les interactions PUDO.

<figure><img src="../../.gitbook/assets/image (894).png" alt=""><figcaption></figcaption></figure>

* **PUDO de repli**: Un champ au niveau de la mission qui détermine si un dépôt PUDO est autorisé.

<figure><img src="../../.gitbook/assets/image (895).png" alt=""><figcaption></figcaption></figure>

#### Mode d’emploi : Configurer les types de PUDO

1. Accédez à **Configuration** module.

<figure><img src="../../.gitbook/assets/image (896).png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur **type de PUDO**.
3. Définissez des catégories telles que supermarchés, commerces partenaires ou consignes.

<figure><img src="../../.gitbook/assets/image (897).png" alt=""><figcaption></figcaption></figure>

#### Mode d’emploi : Importer la liste PUDO

1. Accédez à **PUDO** page dans le **Configuration** module.

<figure><img src="../../.gitbook/assets/image (898).png" alt=""><figcaption></figcaption></figure>

2. Ouvrez le **Actions** menu de la liste.
3. Sélectionnez le **Importer** action pour importer votre liste en masse.

<figure><img src="../../.gitbook/assets/image (899).png" alt=""><figcaption></figcaption></figure>

#### Mode d’emploi : Configurer les sous-statuts PUDO

1. Cliquez sur le **Sous-statut** page dans le **Configuration** module.

<figure><img src="../../.gitbook/assets/image (900).png" alt=""><figcaption></figcaption></figure>

2. Activez le **PUDO uniquement** interrupteur.

<figure><img src="../../.gitbook/assets/image (901).png" alt=""><figcaption></figcaption></figure>

3. Saisissez des libellés opérationnels comme « Déposé en consigne » ou « Point PUDO complet ».
4. Cliquez sur le **Enregistrer** bouton.

<figure><img src="../../.gitbook/assets/image (902).png" alt=""><figcaption></figcaption></figure>

#### Mode d’emploi : Activer le PUDO de repli sur une mission

1. Recherchez le **Livraison de repli en PUDO** champ dans le **Tableau des missions**.

<figure><img src="../../.gitbook/assets/image (903).png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur le **Modifier** bouton pour ouvrir l’ **Éditeur de mission**.
3. Sélectionnez le **Informations de livraison** **section**.
4. Définissez la caractéristique de repli sur **Autoriser**, **Refuser**, ou **Après une nouvelle tentative**.

<figure><img src="../../.gitbook/assets/image (904).png" alt=""><figcaption></figcaption></figure>

#### Conseils de productivité

* 💡 **Prise en charge de missions multiples**: Utilisez le PUDO pour les missions de prise en charge et de livraison afin d’accroître la flexibilité opérationnelle.
* 💡 **Mises à jour en masse**: Gérez les autorisations de repli à grande échelle à l’aide du **modèle d’importation** ou de l’API lors de la création des missions.
* ⚠️ **Maintenance des données**: Gardez la **liste PUDO** à jour, sinon les chauffeurs ne pourront pas trouver les points de dépôt à proximité.
* ⚠️ **Distinctions de type**: Faites toujours la différence entre les magasins et les consignes, car ils nécessitent des processus de traitement différents comme **OTP** codes.
