# Missions à étapes multiples

**Nomadia Delivery** utilise des missions à plusieurs étapes pour suivre les colis à travers plusieurs hubs et agences, de l’enlèvement en premier kilomètre à la livraison du dernier kilomètre. Cette fonctionnalité offre une visibilité de bout en bout pour les opérations complexes de la chaîne d’approvisionnement en suivant une mission à chaque point de contact. Vous obtiendrez une chaîne de responsabilité complète et traçable pour chaque colis de votre réseau.

#### Pour commencer

Pour utiliser cette fonctionnalité, assurez-vous de disposer d’un compte utilisateur avec les autorisations correspondant à votre agence spécifique.

* Accès au **Nomadia Delivery** back office.
* Compte utilisateur attribué à un **Agence d’origine**.
* Infrastructure de routage configurée pour l’attribution automatique des zones.
* Connectez-vous à **Nomadia Delivery** en tant qu’utilisateur de la **Agence d’origine**.

<figure><img src="../.gitbook/assets/image (917).png" alt=""><figcaption></figcaption></figure>

#### Présentation de la fonctionnalité

* **Agence**: Affiche la position actuelle de la mission et détermine la visibilité de l’utilisateur.
* **Agence d’origine**: Indique le hub où commence l’enlèvement en premier kilomètre.
* **Agence de destination**: Indique le hub final à partir duquel le client reçoit le colis.
* **Étape**: Indique la phase actuelle : Collecte, Distribution ou Livraison.

<figure><img src="../.gitbook/assets/image (918).png" alt=""><figcaption></figcaption></figure>

#### Procédure : Créer une mission à plusieurs étapes

1. Cliquez sur le **Mission**.

<figure><img src="../.gitbook/assets/image (919).png" alt=""><figcaption></figcaption></figure>

2. Sélectionnez **Ajouter** depuis le **Actions** menu de la liste.
3. Sélectionnez **Cross-Docking** comme type de mission, choisissez l’agence requise, puis cliquez sur **Suivant**.

<figure><img src="../.gitbook/assets/image (920).png" alt=""><figcaption></figcaption></figure>

4. Sélectionnez le **Agence d’origine** et le **Agence de destination**.
5. Définissez le **Étape** sur **Collecte**.
6. Saisissez les détails du lieu d’enlèvement et de livraison.
7. Cliquez sur **Ajouter** pour enregistrer la mission.

<figure><img src="../.gitbook/assets/image (921).png" alt=""><figcaption></figcaption></figure>

#### Procédure : Mettre à jour les étapes de mission et la visibilité (API /updateMultiLegStatusInformation)

1. Utilisez le **point de terminaison Mettre à jour les informations d’état multi-étapes** pour passer d’une étape à l’autre.
2. Définissez le **Étape** sur **Distribution** lorsque l’article est prêt pour le transit sur le trajet intermédiaire.

<figure><img src="../.gitbook/assets/image (922).png" alt=""><figcaption></figcaption></figure>

3. Accédez à **Configuration** module pour gérer la visibilité des utilisateurs.
4. Sélectionnez **Modifier** pour un utilisateur spécifique sur le **Gérer les utilisateurs** page.
5. Ouvrez le **Règles et droits** .

<figure><img src="../.gitbook/assets/image (923).png" alt=""><figcaption></figcaption></figure>

6. Activez la **Gérer les missions en transit** droit.
7. Cliquez sur **Enregistrer** pour permettre à l’utilisateur de voir les missions qui ont quitté son hub.

<figure><img src="../.gitbook/assets/image (924).png" alt=""><figcaption></figcaption></figure>

8. Les missions en transit sont désormais affichées dans le **Missions.**

<figure><img src="../.gitbook/assets/image (925).png" alt=""><figcaption></figcaption></figure>

9. Mettez à jour le **Étape** sur **Livraison** lorsque la mission arrive au hub final.
10. Définissez le **Statut** sur **Reçu** pour l’utilisateur de l’agence de destination.

<figure><img src="../.gitbook/assets/image (926).png" alt=""><figcaption></figcaption></figure>

#### Procédure : Auditer l’historique de la mission

1. Ouvrez une mission dans l’onglet **Éditeur**.
2. Sélectionnez le **Journaux** pour afficher chaque changement de statut et chaque transition d’agence.

<figure><img src="../.gitbook/assets/image (927).png" alt=""><figcaption></figcaption></figure>

#### Conseils de productivité

* 💡 **Affectation automatique**: L’infrastructure de routage remplit automatiquement les agents et les sous-zones dès que vous créez la mission.
* 💡 **Saisie flexible**: Créez des missions directement dans un statut de distribution ou de livraison si des sous-traitants ont géré la collecte initiale.
* ⚠️ **Perte de visibilité**: Les missions disparaissent normalement de la vue d’origine une fois qu’elles quittent le hub, sauf si des droits spécifiques sont activés.
