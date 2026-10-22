# Gérer les missions

Les champs suivants sont disponibles au niveau de la mission, vous permettant de configurer diverses contraintes de mission en fonction des besoins de votre entreprise.

## Avant de commencer

* Connectez-vous à **Nomadia Delivery** avec un profil utilisateur ayant accès au module **Missions**.
* Connaissez le **Type de mission** et l’**Agence** de la mission que vous souhaitez créer, et ayez à disposition les détails obligatoires de la mission pour ce type de mission.

## Présentation de la fonctionnalité

<table data-header-hidden><thead><tr><th valign="top"></th><th valign="top"></th><th valign="top"></th></tr></thead><tbody><tr><td valign="top">Section Mission</td><td valign="top">Champ Mission</td><td valign="top">Description</td></tr><tr><td valign="top">Informations générales</td><td valign="top">Numéro de mission</td><td valign="top">Un identifiant unique, attribué automatiquement ou manuellement à la mission à des fins de suivi et de référence.</td></tr><tr><td valign="top"></td><td valign="top">Code-barres de l’expéditeur</td><td valign="top">Code-barres associé à l’expéditeur ou à l’envoi, utilisé pour le scan et l’identification rapide pendant les opérations de traitement et de livraison.</td></tr><tr><td valign="top"></td><td valign="top">ID du conteneur parent</td><td valign="top">Identifie le conteneur parent auquel appartient la mission ou l’envoi, permettant un suivi hiérarchique des expéditions.</td></tr><tr><td valign="top"></td><td valign="top">Clé de regroupement</td><td valign="top">Une valeur utilisée pour regrouper plusieurs missions dans un but de planification, de routage ou d’exploitation.</td></tr><tr><td valign="top"></td><td valign="top">Type de conteneur</td><td valign="top">Définit le type de conteneur utilisé pour l’envoi (par exemple : boîte, palette, enveloppe), ce qui peut influencer les contraintes de manutention ou de transport.</td></tr><tr><td valign="top"></td><td valign="top">Type de configuration du statut</td><td valign="top">Spécifie la configuration du workflow de statuts appliquée à la mission, déterminant les états et transitions disponibles de la mission.</td></tr><tr><td valign="top"></td><td valign="top">Type de configuration de notification</td><td valign="top">Définit les règles de notification associées à la mission, telles que les alertes envoyées aux clients, chauffeurs ou opérateurs pendant l’avancement de la mission.</td></tr><tr><td valign="top"></td><td valign="top">Livreur programmé</td><td valign="top">La ressource planifiée (chauffeur, technicien ou agent) affectée à l’exécution de la mission.</td></tr><tr><td valign="top"></td><td valign="top">Origine</td><td valign="top">Le lieu de départ à partir duquel la mission commence ou où les marchandises sont récupérées.</td></tr><tr><td valign="top"></td><td valign="top">Priorité</td><td valign="top">Indique le niveau d’importance de la mission, ce qui peut influencer l’ordre de planification et la programmation de l’exécution.</td></tr><tr><td valign="top"></td><td valign="top">Lieu de stockage</td><td valign="top">Spécifie le lieu de stockage ou l’emplacement d’entrepôt associé à la mission avant l’expédition ou après l’achèvement.</td></tr><tr><td valign="top"></td><td valign="top">Durée fixe de visite</td><td valign="top">Définit la durée prévue nécessaire pour terminer la mission sur site.</td></tr><tr><td valign="top"></td><td valign="top">Clés</td><td valign="top">Identifiants de référence ou balises utilisés à des fins de classification, de filtrage ou d’intégration.</td></tr><tr><td valign="top"></td><td valign="top">Compatibilité avec les ressources</td><td valign="top">Définit des contraintes garantissant que seules des ressources compatibles (en fonction des compétences, du type de véhicule ou de la configuration) peuvent être affectées à la mission.</td></tr><tr><td valign="top"></td><td valign="top">Exiger que toutes les compétences soient compatibles</td><td valign="top">Lorsqu’elle est activée, la ressource affectée doit posséder toutes les compétences requises définies pour la mission.</td></tr><tr><td valign="top"></td><td valign="top">La livraison doit être effectuée avant tout enlèvement</td><td valign="top">Garantit que les opérations de livraison sont terminées avant les tâches d’enlèvement dans la même séquence de mission.</td></tr><tr><td valign="top"></td><td valign="top">Mot de passe à usage unique</td><td valign="top">Un code de vérification de sécurité requis pour valider l’achèvement de la mission ou la confirmation de livraison.</td></tr><tr><td valign="top"></td><td valign="top">Agence d’origine</td><td valign="top">L’agence ou l’unité opérationnelle responsable du lancement de la mission.</td></tr><tr><td valign="top"></td><td valign="top">Agence de destination</td><td valign="top">L’agence ou l’unité opérationnelle responsable de la réception ou de l’achèvement de la mission.</td></tr><tr><td valign="top"></td><td valign="top">Étape</td><td valign="top">Représente un segment d’une mission en plusieurs étapes ou d’un itinéraire de transport.</td></tr><tr><td valign="top"></td><td valign="top">Statut de la mission</td><td valign="top">Affiche l’état actuel de la mission dans le workflow opérationnel (par exemple : Planifiée, Affectée, En cours, Terminée, Annulée).</td></tr><tr><td valign="top">Informations de ramassage</td><td valign="top">Enlèvement (Adresse)</td><td valign="top">Spécifie l’adresse principale où l’opération d’enlèvement aura lieu.</td></tr><tr><td valign="top"></td><td valign="top">Enlèvement (Complément d’adresse)</td><td valign="top">Fournit des détails d’adresse supplémentaires tels que le nom du bâtiment, le numéro d’appartement, l’étage ou les instructions d’accès afin d’aider à localiser précisément le point d’enlèvement.</td></tr><tr><td valign="top"></td><td valign="top">Désignation de l’enlèvement</td><td valign="top">Identifie le lieu d’enlèvement ou le nom de l’organisation associé à l’envoi.</td></tr><tr><td valign="top"></td><td valign="top">Enlèvement (Prénom)</td><td valign="top">Prénom de la personne de contact disponible sur le lieu d’enlèvement.</td></tr><tr><td valign="top"></td><td valign="top">Enlèvement (Nom)</td><td valign="top">Nom de la personne de contact responsable de la coordination de l’enlèvement.</td></tr><tr><td valign="top"></td><td valign="top">Enlèvement (Téléphone portable)</td><td valign="top">Numéro de téléphone mobile de la personne de contact pour l’enlèvement, utilisé pour la communication pendant l’exécution de la mission.</td></tr><tr><td valign="top"></td><td valign="top">Enlèvement (Téléphone fixe)</td><td valign="top">Numéro de téléphone fixe du lieu d’enlèvement ou de la personne de contact.</td></tr><tr><td valign="top"></td><td valign="top">Enlèvement (E-mail)</td><td valign="top">Adresse e-mail du contact d’enlèvement pour l’envoi de notifications ou les communications liées à la mission.</td></tr><tr><td valign="top"></td><td valign="top">Date demandée pour l’enlèvement</td><td valign="top">La date et l’heure demandées auxquelles l’enlèvement doit commencer.</td></tr><tr><td valign="top"></td><td valign="top">Date de fin demandée pour l’enlèvement</td><td valign="top">La dernière date et heure acceptables auxquelles l’enlèvement doit être terminé.</td></tr><tr><td valign="top"></td><td valign="top">Instructions d’enlèvement</td><td valign="top">Instructions spéciales ou notes opérationnelles fournies à la ressource effectuant l’enlèvement (par exemple : procédures d’accès, exigences de manutention, consignes de sécurité).</td></tr><tr><td valign="top"></td><td valign="top">Code de conteneur scannable</td><td valign="top">Code-barres ou identifiant scannable associé au conteneur, permettant une vérification et un suivi rapides pendant les opérations d’enlèvement.</td></tr><tr><td valign="top">Informations de livraison</td><td valign="top">Adresse</td><td valign="top">Spécifie l’adresse principale de destination où la livraison doit être effectuée.</td></tr><tr><td valign="top"></td><td valign="top">Livraison (Complément d’adresse)</td><td valign="top">Fournit des détails supplémentaires sur le lieu, tels que le numéro d’appartement, le nom du bâtiment, l’étage, le numéro de portail ou les instructions d’accès afin d’aider à localiser précisément le point de livraison.</td></tr><tr><td valign="top"></td><td valign="top">Désignation</td><td valign="top">Indique le nom du lieu de livraison, de l’entreprise ou de l’organisation recevant l’envoi.</td></tr><tr><td valign="top"></td><td valign="top">Prénom</td><td valign="top">Prénom du destinataire ou de la personne de contact sur le lieu de livraison.</td></tr><tr><td valign="top"></td><td valign="top">Nom</td><td valign="top">Nom du destinataire ou de la personne de contact responsable.</td></tr><tr><td valign="top"></td><td valign="top">Téléphone portable</td><td valign="top">Numéro de téléphone mobile du contact de livraison, utilisé pour la communication pendant l’exécution de la livraison.</td></tr><tr><td valign="top"></td><td valign="top">Téléphone fixe</td><td valign="top">Numéro de téléphone fixe associé au lieu de livraison ou au destinataire.</td></tr><tr><td valign="top"></td><td valign="top">E-mail</td><td valign="top">Adresse e-mail du destinataire utilisée pour les notifications, confirmations ou mises à jour de livraison.</td></tr><tr><td valign="top"></td><td valign="top">Date demandée pour la livraison</td><td valign="top">La date et l’heure demandées auxquelles la livraison doit commencer ou être effectuée.</td></tr><tr><td valign="top"></td><td valign="top">Date de fin demandée pour la livraison</td><td valign="top">La dernière date et heure acceptables auxquelles la livraison doit être terminée.</td></tr><tr><td valign="top"></td><td valign="top">Contre-remboursement</td><td valign="top">Spécifie le montant à collecter auprès du destinataire au moment de la livraison, le cas échéant.</td></tr><tr><td valign="top"></td><td valign="top">Prix de la livraison</td><td valign="top">Définit les frais de livraison associés à la mission à des fins de facturation ou de comptabilité.</td></tr><tr><td valign="top"></td><td valign="top">Instructions de livraison</td><td valign="top">Notes spéciales ou instructions opérationnelles fournies à la ressource de livraison (par exemple : procédures d’accès, heure de livraison préférée, précautions de manutention).</td></tr><tr><td valign="top"></td><td valign="top">Livraison de repli en PUDO</td><td valign="top">Indique si l’envoi peut être redirigé vers un point Pick-Up and Drop-Off (PUDO) si la tentative de livraison principale échoue ou si le destinataire est indisponible.</td></tr><tr><td valign="top">Champs personnalisés</td><td valign="top"></td><td valign="top">La section des champs personnalisés permet aux utilisateurs de définir et de saisir des informations supplémentaires spécifiques aux besoins de l’entreprise qui ne sont pas couvertes par les champs de mission standard.</td></tr><tr><td valign="top">Articles</td><td valign="top"></td><td valign="top">La section Articles contient des informations détaillées sur les articles ou marchandises associés à une mission. Elle permet aux utilisateurs de définir les caractéristiques, la quantité et les exigences de manutention des produits à récupérer ou à livrer.</td></tr><tr><td valign="top">Horaires d’ouverture</td><td valign="top"></td><td valign="top">La section Horaires d’ouverture définit les périodes durant lesquelles un lieu d’enlèvement ou de livraison est disponible pour les activités opérationnelles. Elle garantit que les missions sont planifiées et exécutées uniquement pendant les heures de travail autorisées du lieu.</td></tr><tr><td valign="top">Informations PUDO</td><td valign="top">ID PUDO</td><td valign="top">Un identifiant unique attribué au point Pick-Up and Drop-Off utilisé pour le suivi et la référence système.</td></tr><tr><td valign="top"></td><td valign="top">PUDO (Complément d’adresse)</td><td valign="top">Fournit des détails d’adresse supplémentaires tels que des informations sur le bâtiment, le numéro d’étage ou des instructions d’accès spécifiques afin d’aider à localiser facilement le point PUDO.</td></tr><tr><td valign="top"></td><td valign="top">Adresse PUDO</td><td valign="top">Spécifie l’adresse physique du lieu Pick-Up and Drop-Off.</td></tr><tr><td valign="top"></td><td valign="top">Prénom PUDO</td><td valign="top">Prénom de la personne de contact responsable sur le lieu PUDO.</td></tr><tr><td valign="top"></td><td valign="top">Nom PUDO</td><td valign="top">Nom de la personne de contact qui gère ou coordonne les opérations au point PUDO.</td></tr><tr><td valign="top"></td><td valign="top">Téléphone fixe PUDO</td><td valign="top">Numéro de téléphone fixe du lieu PUDO pour la communication opérationnelle.</td></tr><tr><td valign="top"></td><td valign="top">Téléphone portable PUDO</td><td valign="top">Numéro de téléphone mobile de la personne de contact PUDO pour une communication en temps réel pendant l’exécution de la mission.</td></tr><tr><td valign="top"></td><td valign="top">E-mail PUDO</td><td valign="top">Adresse e-mail associée au lieu PUDO utilisée pour les notifications et la correspondance opérationnelle.</td></tr><tr><td valign="top"></td><td valign="top">Durée de visite fixe PUDO</td><td valign="top">Définit le temps standard requis pour effectuer les opérations (enlèvement ou dépose) au lieu PUDO. Cette durée est utilisée par le système de planification pour la programmation et l’optimisation des itinéraires.</td></tr><tr><td valign="top"></td><td valign="top">Enlèvement PUDO</td><td valign="top">Enlèvement PUDO désigne le lieu Pick-Up and Drop-Off (PUDO) désigné comme point d’enlèvement pour une mission au lieu de l’adresse d’enlèvement standard.</td></tr><tr><td valign="top"></td><td valign="top">Livraison PUDO</td><td valign="top">Livraison PUDO désigne le lieu Pick-Up and Drop-Off (PUDO) utilisé comme destination de livraison alternative ou finale au lieu de l’adresse principale du destinataire.</td></tr></tbody></table>

## Ajouter une mission

L’ajout d’une mission permet aux utilisateurs de créer une mission en sélectionnant un type de mission, en choisissant une configuration et en saisissant les informations obligatoires de la mission. Le système applique des validations en fonction du type de mission sélectionné.

1. Allez dans **Missions**\
   &#xNAN;_C’est le module principal où toutes les missions sont créées et gérées._

<figure><img src="../../.gitbook/assets/image (11) (1).png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur **Ajouter** dans le menu **Actions**\
   &#xNAN;_Cela ouvre l’écran de création de mission._

<figure><img src="../../.gitbook/assets/en-image (11).png" alt=""><figcaption></figcaption></figure>

3. Sélectionnez le **Type de mission** et l’**Agence**\
   &#xNAN;_(Enlèvement → Livraison ou Livraison → Enlèvement selon votre besoin)_\
   &#xNAN;_Cela définit le workflow et l’agence responsable._

<figure><img src="../../.gitbook/assets/en-image (12).png" alt=""><figcaption></figcaption></figure>

4. Cliquez sur **Suivant**\
   &#xNAN;_Vous mène à l’étape de sélection de la configuration._

<figure><img src="../../.gitbook/assets/en-image (24).png" alt=""><figcaption></figcaption></figure>

5. Sélectionnez une **Configuration de la mission** :
   * Configuration par défaut
   * Toute configuration personnalisée créée précédemment\
     &#xNAN;_Les configurations aident à préremplir ou à contrôler le comportement de la mission._

<figure><img src="../../.gitbook/assets/image (14) (1).png" alt=""><figcaption></figcaption></figure>

6. Saisissez les **détails obligatoires de la mission** selon le type de mission\
   &#xNAN;_Les champs varieront selon qu’il s’agit d’un enlèvement ou d’une livraison._

<figure><img src="../../.gitbook/assets/en-image (27).png" alt=""><figcaption></figcaption></figure>

7. Cliquez sur **Ajouter** ou **Ajouter et imprimer**\
   &#xNAN;_Ajouter → Enregistre la mission_\
   &#xNAN;_Ajouter et imprimer → Enregistre et imprime les détails de la mission_

<figure><img src="../../.gitbook/assets/image (16) (1).png" alt=""><figcaption></figcaption></figure>

## Assistant de mission : un processus guidé étape par étape

L’assistant de création de mission dans Nomadia Delivery offre un processus convivial, étape par étape, pour créer et ajouter des missions sans effort. De la saisie des détails de base de la mission à la spécification des horaires d’ouverture du client, l’assistant simplifie la configuration de la mission tout en garantissant précision et efficacité tout au long du processus.

Suivez ces étapes pour créer une mission à l’aide de l’assistant.

1. Ouvrez le système de gestion des livraisons, puis accédez à l’onglet **Missions**.

<figure><img src="../../.gitbook/assets/en-image (141).png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur le bouton **Actions** et choisissez **Ajouter** pour lancer l’assistant de création de mission.

<figure><img src="../../.gitbook/assets/en-image (142).png" alt=""><figcaption></figcaption></figure>

3. Sélectionnez le type de **mission** et l’**agence**.

<figure><img src="../../.gitbook/assets/en-image (143).png" alt=""><figcaption></figcaption></figure>

4.  Détails de l’adresse d’enlèvement :

    * **Pour les missions d’enlèvement** : saisissez les détails de l’adresse d’enlèvement tels que **ligne d’adresse, ville, état/province, code postal**, ainsi que toute instruction supplémentaire ou point de repère afin d’assurer une identification précise.
    * **Pour les missions de livraison** : l’adresse de l’agence est utilisée par défaut.

    <figure><img src="../../.gitbook/assets/en-image (144).png" alt=""><figcaption></figcaption></figure>
5.  Détails de l’adresse de livraison :

    * **Pour les missions de livraison** : saisissez les **détails de l’adresse de livraison**. Fournir des informations claires et précises garantit des livraisons réussies et ponctuelles.
    * **Pour les missions d’enlèvement** : l’adresse de l’agence est utilisée par défaut.

    <figure><img src="../../.gitbook/assets/en-image (145).png" alt=""><figcaption></figcaption></figure>
6. **Informations sur le colis (facultatif)** : à cette étape, fournissez des détails sur les colis, tels que **dimensions, poids, contenu**, ainsi que toute exigence particulière de manutention. Fournir des informations précises sur le colis contribue à garantir une bonne prise en charge et à préserver l’intégrité de la livraison.

<figure><img src="../../.gitbook/assets/en-image (146).png" alt=""><figcaption></figcaption></figure>

7. **Définition des horaires d’ouverture du client (facultatif)** : spécifiez les horaires d’ouverture du client afin de planifier les livraisons sur des créneaux appropriés. Cela garantit des horaires de livraison alignés sur la disponibilité du client, réduisant ainsi les risques de livraisons manquées ou de refus.

<figure><img src="../../.gitbook/assets/en-image (147).png" alt=""><figcaption></figcaption></figure>

8. **Ajouter la mission au système de gestion des livraisons** : après avoir saisi toutes les informations requises, cliquez sur le bouton **Ajouter** pour enregistrer la mission dans le système de gestion des livraisons. La mission a été créée avec succès. Cet assistant simplifie le processus en guidant les utilisateurs étape par étape, en veillant à ce que toutes les informations requises soient saisies avec précision.

<figure><img src="../../.gitbook/assets/en-image (148).png" alt=""><figcaption></figcaption></figure>

9. La mission a été créée avec succès. Cet assistant simplifie le processus en guidant les utilisateurs étape par étape, en veillant à ce que toutes les informations requises soient saisies avec précision.

<figure><img src="../../.gitbook/assets/en-image (149).png" alt=""><figcaption></figcaption></figure>

## Mapper les champs du fichier d’import de mission

### Mapper les champs d’adresse

Depuis la **page Missions** :

1. Cliquez sur **Actions**.
2. Sélectionnez **Importer** dans le menu déroulant.
3. Cliquez sur **Parcourir (Excel).**
4. Sélectionnez l’**Adresse** parmi les indicateurs de localisation.

<figure><img src="../../.gitbook/assets/en-image (154).png" alt=""><figcaption></figcaption></figure>

5. Cliquez sur **Valider**.

<figure><img src="../../.gitbook/assets/en-image (154).png" alt=""><figcaption></figcaption></figure>

#### Résultat

Les champs d’adresse sont mappés avec succès.

<figure><img src="../../.gitbook/assets/en-image (156).png" alt=""><figcaption></figcaption></figure>

## Colorer les missions

Depuis la **page Missions** :

1. Cliquez sur **Actions**.
2. Sélectionnez **Coloration** dans le menu déroulant.

<figure><img src="../../.gitbook/assets/en-image (186).png" alt=""><figcaption></figcaption></figure>

3. Sélectionnez la condition appropriée parmi les suggestions.
4. Choisissez la **Couleur**.
5. Cliquez sur **Enregistrer**.

<figure><img src="../../.gitbook/assets/en-image (187).png" alt=""><figcaption></figcaption></figure>

### Résultat

La couleur sélectionnée est appliquée avec succès.

## Conseils

{% hint style="info" %}
**Utilisez les configurations** : les configurations aident à préremplir ou à contrôler le comportement de la mission. Sélectionnez donc la configuration par défaut ou une configuration personnalisée créée précédemment lorsque vous ajoutez une mission.
{% endhint %}

{% hint style="warning" %}
**Les champs obligatoires varient selon le type** : le système applique des validations en fonction du type de mission sélectionné, et les champs varient selon qu’il s’agit d’un enlèvement ou d’une livraison.
{% endhint %}

## Rubriques connexes

* [Comprendre les paramètres de mission](README.md)
* [Ajout d’une mission](../adding-a-mission.md)
* [Importer des missions](../import-missions/README.md)
