# Gérer les missions

Les champs suivants sont disponibles au niveau de la mission, vous permettant de configurer diverses contraintes de mission en fonction des besoins de votre entreprise.

| Section Mission           | Champ Mission                                          | Description                                                                                                                                                                                                                                                                             |
| ------------------------- | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Informations générales    | Numéro de mission                                      | Un identifiant unique, attribué automatiquement ou manuellement à la mission à des fins de suivi et de référence.                                                                                                                                                                       |
| Informations générales    | Code-barres de l’expéditeur                            | Code-barres associé à l’expéditeur ou à l’envoi, utilisé pour le scan et l’identification rapide pendant les opérations de traitement et de livraison.                                                                                                                                  |
| Informations générales    | ID du conteneur parent                                 | Identifie le conteneur parent auquel appartient la mission ou l’envoi, permettant un suivi hiérarchique des expéditions.                                                                                                                                                                |
| Informations générales    | Clé de regroupement                                    | Une valeur utilisée pour regrouper plusieurs missions dans un but de planification, de routage ou d’exploitation.                                                                                                                                                                       |
| Informations générales    | Type de conteneur                                      | Définit le type de conteneur utilisé pour l’envoi (par exemple : boîte, palette, enveloppe), ce qui peut influencer les contraintes de manutention ou de transport.                                                                                                                     |
| Informations générales    | Type de configuration du statut                        | Spécifie la configuration du workflow de statuts appliquée à la mission, déterminant les états et transitions disponibles de la mission.                                                                                                                                                |
| Informations générales    | Type de configuration de notification                  | Définit les règles de notification associées à la mission, telles que les alertes envoyées aux clients, chauffeurs ou opérateurs pendant l’avancement de la mission.                                                                                                                    |
| Informations générales    | Livreur programmé                                      | La ressource planifiée (chauffeur, technicien ou agent) affectée à l’exécution de la mission.                                                                                                                                                                                           |
| Informations générales    | Origine                                                | Le lieu de départ à partir duquel la mission commence ou où les marchandises sont récupérées.                                                                                                                                                                                           |
| Informations générales    | Priorité                                               | Indique le niveau d’importance de la mission, ce qui peut influencer l’ordre de planification et la programmation de l’exécution.                                                                                                                                                       |
| Informations générales    | Lieu de stockage                                       | Spécifie le lieu de stockage ou l’emplacement d’entrepôt associé à la mission avant l’expédition ou après l’achèvement.                                                                                                                                                                 |
| Informations générales    | Durée fixe de visite                                   | Définit la durée prévue nécessaire pour terminer la mission sur site.                                                                                                                                                                                                                   |
| Informations générales    | Clés                                                   | Identifiants de référence ou balises utilisés à des fins de classification, de filtrage ou d’intégration.                                                                                                                                                                               |
| Informations générales    | Compatibilité avec les ressources                      | Définit des contraintes garantissant que seules des ressources compatibles (en fonction des compétences, du type de véhicule ou de la configuration) peuvent être affectées à la mission.                                                                                               |
| Informations générales    | Exiger que toutes les compétences soient compatibles   | Lorsqu’elle est activée, la ressource affectée doit posséder toutes les compétences requises définies pour la mission.                                                                                                                                                                  |
| Informations générales    | La livraison doit être effectuée avant tout enlèvement | Garantit que les opérations de livraison sont terminées avant les tâches d’enlèvement dans la même séquence de mission.                                                                                                                                                                 |
| Informations générales    | Mot de passe à usage unique                            | Un code de vérification de sécurité requis pour valider l’achèvement de la mission ou la confirmation de livraison.                                                                                                                                                                     |
| Informations générales    | Agence d’origine                                       | L’agence ou l’unité opérationnelle responsable du lancement de la mission.                                                                                                                                                                                                              |
| Informations générales    | Agence de destination                                  | L’agence ou l’unité opérationnelle responsable de la réception ou de l’achèvement de la mission.                                                                                                                                                                                        |
| Informations générales    | Étape                                                  | Représente un segment d’une mission en plusieurs étapes ou d’un itinéraire de transport.                                                                                                                                                                                                |
| Informations générales    | Statut de la mission                                   | Affiche l’état actuel de la mission dans le workflow opérationnel (par exemple : Planifiée, Affectée, En cours, Terminée, Annulée).                                                                                                                                                     |
| Informations de ramassage | Enlèvement (Adresse)                                   | Spécifie l’adresse principale où l’opération d’enlèvement aura lieu.                                                                                                                                                                                                                    |
| Informations de ramassage | Enlèvement (Complément d’adresse)                      | Fournit des détails d’adresse supplémentaires tels que le nom du bâtiment, le numéro d’appartement, l’étage ou les instructions d’accès afin d’aider à localiser précisément le point d’enlèvement.                                                                                     |
| Informations de ramassage | Désignation de l’enlèvement                            | Identifie le lieu d’enlèvement ou le nom de l’organisation associé à l’envoi.                                                                                                                                                                                                           |
| Informations de ramassage | Enlèvement (Prénom)                                    | Prénom de la personne de contact disponible sur le lieu d’enlèvement.                                                                                                                                                                                                                   |
| Informations de ramassage | Enlèvement (Nom)                                       | Nom de la personne de contact responsable de la coordination de l’enlèvement.                                                                                                                                                                                                           |
| Informations de ramassage | Enlèvement (Téléphone portable)                        | Numéro de téléphone mobile de la personne de contact pour l’enlèvement, utilisé pour la communication pendant l’exécution de la mission.                                                                                                                                                |
| Informations de ramassage | Enlèvement (Téléphone fixe)                            | Numéro de téléphone fixe du lieu d’enlèvement ou de la personne de contact.                                                                                                                                                                                                             |
| Informations de ramassage | Enlèvement (E-mail)                                    | Adresse e-mail du contact d’enlèvement pour l’envoi de notifications ou les communications liées à la mission.                                                                                                                                                                          |
| Informations de ramassage | Date demandée pour l’enlèvement                        | La date et l’heure demandées auxquelles l’enlèvement doit commencer.                                                                                                                                                                                                                    |
| Informations de ramassage | Date de fin demandée pour l’enlèvement                 | La dernière date et heure acceptables auxquelles l’enlèvement doit être terminé.                                                                                                                                                                                                        |
| Informations de ramassage | Instructions d’enlèvement                              | Instructions spéciales ou notes opérationnelles fournies à la ressource effectuant l’enlèvement (par exemple : procédures d’accès, exigences de manutention, consignes de sécurité).                                                                                                    |
| Informations de ramassage | Code de conteneur scannable                            | Code-barres ou identifiant scannable associé au conteneur, permettant une vérification et un suivi rapides pendant les opérations d’enlèvement.                                                                                                                                         |
| Informations de livraison | Adresse                                                | Spécifie l’adresse principale de destination où la livraison doit être effectuée.                                                                                                                                                                                                       |
| Informations de livraison | Livraison (Complément d’adresse)                       | Fournit des détails supplémentaires sur le lieu, tels que le numéro d’appartement, le nom du bâtiment, l’étage, le numéro de portail ou les instructions d’accès afin d’aider à localiser précisément le point de livraison.                                                            |
| Informations de livraison | Désignation                                            | Indique le nom du lieu de livraison, de l’entreprise ou de l’organisation recevant l’envoi.                                                                                                                                                                                             |
| Informations de livraison | Prénom                                                 | Prénom du destinataire ou de la personne de contact sur le lieu de livraison.                                                                                                                                                                                                           |
| Informations de livraison | Nom                                                    | Nom du destinataire ou de la personne de contact responsable.                                                                                                                                                                                                                           |
| Informations de livraison | Téléphone portable                                     | Numéro de téléphone mobile du contact de livraison, utilisé pour la communication pendant l’exécution de la livraison.                                                                                                                                                                  |
| Informations de livraison | Téléphone fixe                                         | Numéro de téléphone fixe associé au lieu de livraison ou au destinataire.                                                                                                                                                                                                               |
| Informations de livraison | E-mail                                                 | Adresse e-mail du destinataire utilisée pour les notifications, confirmations ou mises à jour de livraison.                                                                                                                                                                             |
| Informations de livraison | Date demandée pour la livraison                        | La date et l’heure demandées auxquelles la livraison doit commencer ou être effectuée.                                                                                                                                                                                                  |
| Informations de livraison | Date de fin demandée pour la livraison                 | La dernière date et heure acceptables auxquelles la livraison doit être terminée.                                                                                                                                                                                                       |
| Informations de livraison | Contre-remboursement                                   | Spécifie le montant à collecter auprès du destinataire au moment de la livraison, le cas échéant.                                                                                                                                                                                       |
| Informations de livraison | Prix de la livraison                                   | Définit les frais de livraison associés à la mission à des fins de facturation ou de comptabilité.                                                                                                                                                                                      |
| Informations de livraison | Instructions de livraison                              | Notes spéciales ou instructions opérationnelles fournies à la ressource de livraison (par exemple : procédures d’accès, heure de livraison préférée, précautions de manutention).                                                                                                       |
| Informations de livraison | Livraison de repli en PUDO                             | Indique si l’envoi peut être redirigé vers un point Pick-Up and Drop-Off (PUDO) si la tentative de livraison principale échoue ou si le destinataire est indisponible.                                                                                                                  |
| Champs personnalisés      | Champs personnalisés                                   | La section des champs personnalisés permet aux utilisateurs de définir et de saisir des informations supplémentaires spécifiques aux besoins de l’entreprise qui ne sont pas couvertes par les champs de mission standard.                                                              |
| Articles                  | Articles                                               | La section Articles contient des informations détaillées sur les articles ou marchandises associés à une mission. Elle permet aux utilisateurs de définir les caractéristiques, la quantité et les exigences de manutention des produits à récupérer ou à livrer.                       |
| Horaires d’ouverture      | Horaires d’ouverture                                   | La section Horaires d’ouverture définit les périodes durant lesquelles un lieu d’enlèvement ou de livraison est disponible pour les activités opérationnelles. Elle garantit que les missions sont planifiées et exécutées uniquement pendant les heures de travail autorisées du lieu. |
| Informations PUDO         | ID PUDO                                                | Un identifiant unique attribué au point Pick-Up and Drop-Off utilisé pour le suivi et la référence système.                                                                                                                                                                             |
| Informations PUDO         | PUDO (Complément d’adresse)                            | Fournit des détails d’adresse supplémentaires tels que des informations sur le bâtiment, le numéro d’étage ou des instructions d’accès spécifiques afin d’aider à localiser facilement le point PUDO.                                                                                   |
| Informations PUDO         | Adresse PUDO                                           | Spécifie l’adresse physique du lieu Pick-Up and Drop-Off.                                                                                                                                                                                                                               |
| Informations PUDO         | Prénom PUDO                                            | Prénom de la personne de contact responsable sur le lieu PUDO.                                                                                                                                                                                                                          |
| Informations PUDO         | Nom PUDO                                               | Nom de la personne de contact qui gère ou coordonne les opérations au point PUDO.                                                                                                                                                                                                       |
| Informations PUDO         | Téléphone fixe PUDO                                    | Numéro de téléphone fixe du lieu PUDO pour la communication opérationnelle.                                                                                                                                                                                                             |
| Informations PUDO         | Téléphone portable PUDO                                | Numéro de téléphone mobile de la personne de contact PUDO pour une communication en temps réel pendant l’exécution de la mission.                                                                                                                                                       |
| Informations PUDO         | E-mail PUDO                                            | Adresse e-mail associée au lieu PUDO utilisée pour les notifications et la correspondance opérationnelle.                                                                                                                                                                               |
| Informations PUDO         | Durée de visite fixe PUDO                              | Définit le temps standard requis pour effectuer les opérations (enlèvement ou dépose) au lieu PUDO. Cette durée est utilisée par le système de planification pour la programmation et l’optimisation des itinéraires.                                                                   |
| Informations PUDO         | Enlèvement PUDO                                        | Enlèvement PUDO désigne le lieu Pick-Up and Drop-Off (PUDO) désigné comme point d’enlèvement pour une mission au lieu de l’adresse d’enlèvement standard.                                                                                                                               |
| Informations PUDO         | Livraison PUDO                                         | Livraison PUDO désigne le lieu Pick-Up and Drop-Off (PUDO) utilisé comme destination de livraison alternative ou finale au lieu de l’adresse principale du destinataire.                                                                                                                |

### Ajouter une mission

L’ajout d’une mission permet aux utilisateurs de créer une mission en sélectionnant un type de mission, en choisissant une configuration et en saisissant les informations obligatoires de la mission. Le système applique des validations en fonction du type de mission sélectionné.

1. Aller à **Missions**\
   \&#xNAN;_C’est le module principal où toutes les missions sont créées et gérées._

<figure><img src="../../.gitbook/assets/msedge_JJC17nIIsi.png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur **Ajouter** depuis le **Actions** menu \&#xNAN;_Cela ouvre l’écran de création de mission._

<figure><img src="../../.gitbook/assets/image (1030).png" alt=""><figcaption></figcaption></figure>

3. Sélectionnez **Type de mission**, **Agence**\
   \&#xNAN;_(Enlèvement → Livraison ou Livraison → Enlèvement selon votre besoin)_\
   \&#xNAN;_Cela définit le workflow et l’agence responsable._

<figure><img src="../../.gitbook/assets/msedge_0x1udLgLeh.png" alt=""><figcaption></figcaption></figure>

4. Cliquez sur **Suivant** \&#xNAN;_Vous mène à l’étape de sélection de la configuration._

<figure><img src="../../.gitbook/assets/msedge_c3uxaGfnlH.png" alt=""><figcaption></figcaption></figure>

5. Sélectionnez un **Configuration de la mission**:

* Configuration par défaut
* Toute configuration personnalisée créée précédemment \&#xNAN;_Les configurations aident à préremplir ou à contrôler le comportement de la mission._

<figure><img src="../../.gitbook/assets/msedge_4Doaj75evN.png" alt=""><figcaption></figcaption></figure>

4. Entrée **détails obligatoires de la mission** selon le type de mission\
   \&#xNAN;_Les champs varieront selon qu’il s’agit d’un enlèvement ou d’une livraison._
5. Cliquez sur **Ajouter** ou **Ajouter et imprimer** \&#xNAN;_Ajouter → Enregistre la mission_ \&#xNAN;_Ajouter et imprimer → Enregistre et imprime les détails de la mission_

<figure><img src="../../.gitbook/assets/msedge_rnMnGKTENs.png" alt=""><figcaption></figcaption></figure>

### Assistant de mission : un processus guidé étape par étape

L’assistant de création de mission dans Nomadia Delivery offre un processus convivial, étape par étape, pour créer et ajouter des missions sans effort. De la saisie des détails de base de la mission à la spécification des horaires d’ouverture du client, l’assistant simplifie la configuration de la mission tout en garantissant précision et efficacité tout au long du processus.

Suivez ces étapes pour créer une mission à l’aide de l’assistant

1. Ouvrez le système de gestion des livraisons, puis accédez à l’onglet « **Missions** »

<figure><img src="../../.gitbook/assets/msedge_YhHbv3EjAJ.png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur le bouton « **Actions** « et choisissez « **Ajouter** » pour lancer l’assistant de création de mission

<figure><img src="../../.gitbook/assets/msedge_zckGFaFP0y.png" alt=""><figcaption></figcaption></figure>

3. Sélectionnez le type de **mission** et **agence**

<figure><img src="../../.gitbook/assets/msedge_rGbpsqmNa9.png" alt=""><figcaption></figcaption></figure>

4. Détails de l’adresse d’enlèvement :

* **Pour les missions d’enlèvement**: Saisissez les détails de l’adresse d’enlèvement tels que **ligne d’adresse, ville, état/province, code postal**, ainsi que toute instruction supplémentaire ou point de repère afin d’assurer une identification précise.
* **Pour les missions de livraison**: L’adresse de l’agence est utilisée par défaut.

<figure><img src="../../.gitbook/assets/image 52 (1).png" alt=""><figcaption></figcaption></figure>

5. Détails de l’adresse de livraison :

* **Pour les missions de livraison**: Saisissez les **détails de l’adresse de livraison**. Fournir des informations claires et précises garantit des livraisons réussies et ponctuelles.
* **Pour les missions d’enlèvement**: L’adresse de l’agence est utilisée par défaut.

<figure><img src="../../.gitbook/assets/msedge_v8ddiguvpK.png" alt=""><figcaption></figcaption></figure>

6. **Informations sur le colis (facultatif)**: À cette étape, fournissez des détails sur les colis, tels que **dimensions, poids, contenu**, ainsi que toute exigence particulière de manutention. Fournir des informations précises sur le colis contribue à garantir une bonne prise en charge et à préserver l’intégrité de la livraison.

<figure><img src="../../.gitbook/assets/msedge_u5k5hzHUQo.png" alt=""><figcaption></figcaption></figure>

7. **Définition des horaires d’ouverture du client (facultatif)**: Spécifiez les horaires d’ouverture du client afin de planifier les livraisons sur des créneaux appropriés. Cela garantit des horaires de livraison alignés sur la disponibilité du client, réduisant ainsi les risques de livraisons manquées ou de refus.

<figure><img src="../../.gitbook/assets/image (990).png" alt=""><figcaption></figcaption></figure>

8. **Ajouter une mission au système de gestion des livraisons**: Après avoir saisi toutes les informations requises, cliquez sur le bouton « **Ajouter** » pour enregistrer la mission dans le système de gestion des livraisons. La mission a été créée avec succès. Cet assistant simplifie le processus en guidant les utilisateurs étape par étape, en veillant à ce que toutes les informations requises soient saisies avec précision.

<figure><img src="../../.gitbook/assets/image 56.png" alt=""><figcaption></figcaption></figure>

9. La mission a été créée avec succès. Cet assistant simplifie le processus en guidant les utilisateurs étape par étape, en veillant à ce que toutes les informations requises soient saisies avec précision.

<figure><img src="../../.gitbook/assets/msedge_b8NVx8vpXU.png" alt=""><figcaption></figcaption></figure>

### Mapper les champs du fichier d’import de mission

#### Mapper les champs d’adresse

Depuis la **Page Missions**

1. Cliquez sur **Actions**.
2. Sélectionnez **Importer** dans le menu déroulant.
3. Cliquez sur **Parcourir (Excel).**
4. Sélectionnez le **Adresse** à partir des indicateurs de localisation
5. Cliquez sur **Valider**

<figure><img src="../../.gitbook/assets/image (991).png" alt=""><figcaption></figcaption></figure>

6. Les champs d’adresse seront mappés avec succès

<figure><img src="../../.gitbook/assets/image 61.png" alt=""><figcaption></figcaption></figure>

### Colorer les missions

Depuis la **Page Missions**

1. Cliquez sur **Actions**.
2. Sélectionnez **Coloration** dans le menu déroulant.

<figure><img src="../../.gitbook/assets/msedge_vuAK4MfPTB.png" alt=""><figcaption></figcaption></figure>

3. Sélectionnez la condition appropriée parmi les suggestions.
4. Choisissez le **Couleur**
5. Cliquez sur **Enregistrer**

<figure><img src="../../.gitbook/assets/msedge_rB7EHrRyYK.png" alt=""><figcaption></figcaption></figure>

6. La couleur sélectionnée sera appliquée avec succès.

\
<br>
