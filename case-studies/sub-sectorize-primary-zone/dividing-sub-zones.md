# Division des sous-zones

La division des sous-zones vous permet de scinder instantanément un territoire surchargé en deux zones équilibrées. Utilisez cette fonctionnalité pour gérer les pics de demande, les commandes en gros ou les hausses saisonnières sans surcharger les chauffeurs. Vous obtiendrez des volumes de missions équilibrés et des réaffectations automatisées des chauffeurs afin de maintenir vos niveaux de service.

#### Pour commencer

Avant de diviser un territoire, assurez-vous que votre configuration répond à ces exigences :

* Une zone principale doit déjà être sous-sectorisée via le gestionnaire de territoires.
* Les sous-zones cibles doivent avoir un lien établi avec une zone principale.
* Ouvrez le **Module de configuration**.

<figure><img src="../../.gitbook/assets/image (755).png" alt=""><figcaption></figcaption></figure>

* Cliquez sur **Gérer les études et les zones**.

<figure><img src="../../.gitbook/assets/image (756).png" alt=""><figcaption></figcaption></figure>

* Sélectionnez le **Modifier** icône de l’étude contenant la zone surchargée.

**Présentation de la fonctionnalité**

* **Mode d’affectation**: Ce champ affiche « sous-zone principale » pour confirmer que le territoire fait partie d’une hiérarchie plus vaste.

<figure><img src="../../.gitbook/assets/image (757).png" alt=""><figcaption></figcaption></figure>

* **Champ Zone principale**: Celui-ci stocke l’identifiant unique de la zone principale parente afin de conserver la structure intacte.

<figure><img src="../../.gitbook/assets/image (758).png" alt=""><figcaption></figcaption></figure>

* **Menu Actions**: Cela fournit le **Sous-sectoriser** commande pour lancer le processus de division.
* **Paramètres de sectorisation**: Cette fenêtre contextuelle vous permet de filtrer les missions par agence, période ou jours spécifiques.

<figure><img src="../../.gitbook/assets/image (759).png" alt=""><figcaption></figcaption></figure>

* **Bouton Automatisation**: Cela lance l’assistant de territoire pour calculer automatiquement de nouvelles limites.

<figure><img src="../../.gitbook/assets/image (760).png" alt=""><figcaption></figcaption></figure>

#### Mode d’emploi : Diviser une sous-zone surchargée

1. Identifiez la sous-zone surchargée dans le **onglet Zone**.
2. Ouvrez le **menu Actions** et cliquez sur **Sous-sectoriser**.

<figure><img src="../../.gitbook/assets/image (761).png" alt=""><figcaption></figcaption></figure>

3. Définissez vos filtres dans **paramètres de sectorisation** et cliquez sur **Affecter des territoires**.
4. Cliquez sur le **bouton Automatisation** situé au-dessus de la carte dans **Gestionnaire de territoires**.

<figure><img src="../../.gitbook/assets/image (760).png" alt=""><figcaption></figcaption></figure>

5. Sélectionnez **Point d’équilibre** comme méthodologie dans l’ **assistant d’affectation de territoires**.
6. Cliquez sur **Démarrer**.
7. Saisissez le nombre « 2 » dans le **Nombre de territoires** section.
8. Cliquez sur **C’est parti** pour lancer le calcul.

<figure><img src="../../.gitbook/assets/image (762).png" alt=""><figcaption></figcaption></figure>

9. Examinez la répartition sur la carte et cliquez sur **Valider l’affectation du territoire**.
10. Cliquez sur **Enregistrer** dans l’ **Modifier l’affectation du territoire** page.

#### Mode d’emploi : Vérifier la réaffectation automatisée des missions

1. Accédez à **onglet Missions**.
2. Cliquez sur le **colonne** champ pour consulter les affectations des missions.
3. Vérifiez que les missions affichent les noms des nouvelles sous-zones.

<figure><img src="../../.gitbook/assets/image (763).png" alt=""><figcaption></figcaption></figure>

#### Conseils de productivité

* 💡 **Préservation de la hiérarchie**: Le système utilise le **champ Zone principale** pour garantir que la hiérarchie de votre zone reste cohérente pendant les modifications.
* 💡 **Mises à jour automatisées**: Les missions se réaffectent automatiquement en fonction des adresses de livraison géographiques, ce qui élimine la saisie manuelle des données.
* 💡 **Optimisation immédiate**: Les planificateurs peuvent passer directement à l’optimisation des tournées, car le système gère automatiquement tout le re-marquage.
* ⚠️ **Goulots d’étranglement statiques**: Évitez les réaffectations manuelles lors des pics afin de prévenir les goulots d’étranglement de données et les missions non livrées.
