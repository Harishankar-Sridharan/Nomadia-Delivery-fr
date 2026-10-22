# Création d’une étude avec zone principale

Gérez efficacement les territoires de livraison pendant les périodes de pointe et les volumes fluctuants. Organisez la couverture en créant des plans saisonniers qui s’activent automatiquement au bon moment. Obtenez des opérations logistiques précises qui reflètent la couverture réelle pour vos équipes terrain.

#### Pour commencer

* Pour créer et gérer des études, assurez-vous d’avoir les autorisations administratives correctes :
  * Accès au module de configuration
  * Autorisation de créer et de mettre à jour des zones
  * Autorisation de créer et de mettre à jour des études
* Cliquez sur le module Configuration dans la bannière supérieure.

<figure><img src="../.gitbook/assets/image (716).png" alt=""><figcaption></figcaption></figure>

* Sélectionnez le **Gérer les utilisateurs** page.

<figure><img src="../.gitbook/assets/image (717).png" alt=""><figcaption></figcaption></figure>

* Modifiez l’utilisateur spécifique et cliquez sur le **Rôles et droits** .

<figure><img src="../.gitbook/assets/image (718).png" alt=""><figcaption></figcaption></figure>

* Activer les droits pour **Créer et mettre à jour des zones** et **Liste des zones**.
* Cliquez sur le **Enregistrer** bouton pour appliquer les autorisations.

<figure><img src="../.gitbook/assets/image (719).png" alt=""><figcaption></figcaption></figure>

#### Présentation de la fonctionnalité

* **Étude** : Objet structuré définissant comment les territoires de livraison sont organisés.
* **Zone primaire** : Zone géographique de niveau supérieur attribuée à une équipe et liée à des codes postaux.
* **Page de gestion des études** : Votre hub central pour créer et modifier des études et des zones.

#### Mode d’emploi : Créer une étude

1. Accédez à **Études et zones** page sous la **Livraison** section dans **Configuration**.

<figure><img src="../.gitbook/assets/image (720).png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur le **Actions** menu en haut à droite.

<figure><img src="../.gitbook/assets/image (721).png" alt=""><figcaption></figcaption></figure>

3. Sélectionnez **Créer une étude vide**.
4. Saisissez le **Identifiant**, **Nom**, et **Agence**.
5. Définissez le **Date de début de validité** et **Date de fin de validité**.
6. Basculer l’étude sur **Activez**.
7. Sélectionnez les jours actifs de la semaine pour ce plan.
8. Définissez la période d’activation saisonnière spécifique.
9. Cliquez sur le **Enregistrer** bouton.

<figure><img src="../.gitbook/assets/image (722).png" alt=""><figcaption></figcaption></figure>

**Mode d’emploi : Créer une zone principale**

1. Ouvrez le **Zone** onglet dans votre nouvelle étude.

<figure><img src="../.gitbook/assets/image (723).png" alt=""><figcaption></figcaption></figure>

2. Sélectionnez **Ajouter une zone de code postal**.
3. Ouvrez le **Actions** menu de la liste.

<figure><img src="../.gitbook/assets/image (724).png" alt=""><figcaption></figcaption></figure>

4. Renseignez le **Identifiant**, **Nom**, et **Agence**.
5. Sélectionnez le **Pays** et définissez la **Longueur normalisée du code postal**.
6. Sélectionnez **Zone primaire** dans le **Mode d’affectation** champ.

<figure><img src="../.gitbook/assets/image (725).png" alt=""><figcaption></figcaption></figure>

7. Saisissez les codes postaux manuellement à l’aide de l’option **Plus** bouton.

<figure><img src="../.gitbook/assets/image (726).png" alt=""><figcaption></figcaption></figure>

8. Cliquez sur le **Enregistrer** bouton.

<figure><img src="../.gitbook/assets/image (727).png" alt=""><figcaption></figcaption></figure>

**Conseils de productivité**

* 💡 **Importation en masse**: Utilisez le **Importer** dans le **Actions** menu pour téléverser de grandes listes de codes postaux.
* 💡 **Visualisation instantanée** : Regardez la carte à droite pour voir les polygones des codes postaux rendus automatiquement.
* 💡 **Automatisation via API**: Utilisez le **créer une étude** point de terminaison pour déclencher la création d’une étude par programme pour les flux de travail de grande taille.
* ⚠️ **Mode d’affectation** : Sélectionnez toujours **Zone primaire** pour les zones de niveau supérieur afin d’éviter de créer des sous-zones par erreur.

<br>

\
<br>

\
<br>
