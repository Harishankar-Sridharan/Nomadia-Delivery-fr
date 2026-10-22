# Personnalisation des modèles Word

Ce guide fournit des instructions étape par étape pour personnaliser votre modèle Word utilisé dans la fonctionnalité d’export PDF, vous permettant de télécharger des documents liés à la livraison tels que les feuilles de tournée, les feuilles de chargement, les eCMR, les rapports de mission, les feuilles d’autocollants et les rapports de visite.

Suivez ces étapes pour gérer les modèles de documents :

1. Ouvrez l'application Nomadia Delivery et accédez à l'onglet **Configuration** .
2. Dans le menu déroulant, sélectionnez **Modèles de documents.**

<figure><img src="../.gitbook/assets/msedge_oLxIUCzari.png" alt=""><figcaption></figcaption></figure>

La page affichera tous les modèles par défaut que Nomadia Delivery utilise pour générer des PDF, notamment les feuilles de tournée, les feuilles de chargement, les eCMR, les rapports de mission, les feuilles d’autocollants et les rapports de visite.

<figure><img src="../.gitbook/assets/msedge_gv2zyWwLhM.png" alt=""><figcaption></figcaption></figure>

Les modèles par défaut de Nomadia Delivery sont activés par défaut et ne peuvent ni être désactivés, ni modifiés, ni supprimés. Toutefois, si vous souhaitez personnaliser un modèle, vous pouvez télécharger l’existant et apporter les modifications nécessaires afin qu’il réponde à vos besoins.

Suivez ces étapes pour télécharger un modèle existant :

1. Sélectionnez le **modèle(s)** que vous souhaitez télécharger.

<figure><img src="../.gitbook/assets/msedge_hqQJujWpU8.png" alt=""><figcaption></figcaption></figure>

2. Ouvrez le **Actions** menu et choisissez **Télécharger**.

<figure><img src="../.gitbook/assets/msedge_X2a7IOcJG6.png" alt=""><figcaption></figcaption></figure>

3. Un fichier ZIP sera généré, contenant tous les modèles sélectionnés.

<figure><img src="../.gitbook/assets/msedge_mlmstJMwJB.png" alt=""><figcaption></figcaption></figure>

Suivez ces étapes pour modifier un modèle existant :

1. Ouvrez le modèle téléchargé dans Microsoft Word.

<figure><img src="../.gitbook/assets/image (571).png" alt=""><figcaption></figcaption></figure>

2. Référez-vous au document d’accompagnement FieldsMaster\_DocumentTemplate, qui répertorie tous les champs disponibles pouvant être utilisés dans le modèle.
3. Personnalisez le modèle pour répondre à vos besoins en ajoutant ou en supprimant des champs du document maître des champs selon आवश्यकता. Lors de l’ajout de champs, veillez à les insérer sous forme de champs fusionnés plutôt qu’en texte brut afin d’éviter des problèmes lors de la génération du PDF. Les champs fusionnés (par ex., «${ (contractor.name)!}») sont mis en évidence par un fond gris lorsqu’ils sont sélectionnés, alors que les champs en texte brut ne le sont pas.

| <p><br>Texte brut</p> | Champ fusionné          |
| --------------------- | ----------------------- |
| ${(contractor.name)!} | «${(contractor.name)!}» |

Suivez ces étapes pour convertir du texte brut en champ de fusion :

1. Copiez le texte brut du champ, par exemple : ${(contractor.name)!}.
2. Aller à **Insertion → Quick Parts → Champ.**

<figure><img src="../.gitbook/assets/image (572).png" alt=""><figcaption></figcaption></figure>

3. Dans la liste déroulante Catégories, sélectionnez **Fusion de courrier**, puis choisissez **Champ de fusion** sous Noms de champs
4. Collez le **nom du champ** que vous avez copié dans la zone de texte Nom du champ et cliquez sur **OK**.
5. Le texte brut sera désormais converti en champ de fusion, apparaissant sous la forme : «${(contractor.name)!}»

<figure><img src="../.gitbook/assets/image (573).png" alt=""><figcaption></figcaption></figure>

«Suivez ces étapes pour activer un nouveau modèle.»

1. Une fois le nouveau modèle prêt, rendez-vous dans la section Modèles de documents pour le téléverser.
2. Allez dans le module Configuration et sélectionnez **Modèles de documents** dans le menu.
3. Cliquez sur le **Actions** menu et choisissez **Importer**.

<figure><img src="../.gitbook/assets/msedge_DEnm9UTpNL.png" alt=""><figcaption></figcaption></figure>

4. Parcourez votre ordinateur et sélectionnez le **modèle** que vous venez de créer.

<figure><img src="../.gitbook/assets/msedge_8EnMdZANzT.png" alt=""><figcaption></figcaption></figure>

5. Si nécessaire, mettez à jour l’identifiant ou le nom du fichier.

<figure><img src="../.gitbook/assets/msedge_F0ZOK9hpOM.png" alt=""><figcaption></figcaption></figure>

6. Choisissez le **type de modèle** dans le menu déroulant (par ex., modèle de bon de livraison).

<figure><img src="../.gitbook/assets/image 101.png" alt=""><figcaption></figcaption></figure>

7. Sélectionnez le **agence** ou les agences où le modèle doit être disponible (par ex., Louisiane).
8. Cliquez sur **Enregistrer** pour téléverser le modèle.

<figure><img src="../.gitbook/assets/msedge_edoqtqZmn5.png" alt=""><figcaption></figcaption></figure>

Le modèle nouvellement téléversé apparaîtra désormais dans le tableau des modèles.

<figure><img src="../.gitbook/assets/msedge_LdcjaZYTLf.png" alt=""><figcaption></figcaption></figure>

Par défaut, les nouveaux modèles sont désactivés. Pour activer le modèle :

10. Sélectionnez le modèle téléversé et cliquez sur le **Actions** menu de la liste.
11. Choisir **Activer/Désactiver** pour activer le modèle.

<figure><img src="../.gitbook/assets/msedge_G981n5pKJC.png" alt=""><figcaption></figcaption></figure>

12. Une notification confirmera que le modèle a été mis à jour avec succès, et la colonne Activé affichera Oui.

<figure><img src="../.gitbook/assets/image 102.png" alt=""><figcaption></figcaption></figure>

Suivez ces étapes pour générer un PDF à l’aide du nouveau modèle activé :

1. Accédez à **Missions** onglet et sélectionnez un itinéraire qui a été publié sur le livreur mobile.

<figure><img src="../.gitbook/assets/msedge_roImfaro29.png" alt=""><figcaption></figcaption></figure>

2. Cliquez sur le **Actions** menu et choisissez **Bon de livraison**.

<figure><img src="../.gitbook/assets/msedge_sFBKi5lNNz.png" alt=""><figcaption></figcaption></figure>

3. Cliquez sur le bouton Télécharger pour télécharger le bon de livraison.

<figure><img src="../.gitbook/assets/msedge_mbIs4wIjgn.png" alt=""><figcaption></figcaption></figure>

4. Le PDF téléchargé sera généré à l’aide du nouveau modèle activé.

<figure><img src="../.gitbook/assets/image 103.png" alt=""><figcaption></figcaption></figure>

Suivez ces étapes pour supprimer un modèle

1. Ouvrez l'application Nomadia Delivery et accédez à l'onglet **Configuration** .
2. Dans le menu déroulant, sélectionnez **Modèles de documents.**

<figure><img src="../.gitbook/assets/msedge_YvmdAxOnnB.png" alt=""><figcaption></figcaption></figure>

3. Dans le tableau, choisissez n’importe quel modèle non par défaut, puis cliquez sur le **Actions** menu de la liste.
4. Sélectionnez **Supprimer** pour retirer le modèle.

<figure><img src="../.gitbook/assets/msedge_ifJQhYLhLV.png" alt=""><figcaption></figcaption></figure>

5. Confirmez la suppression en cliquant sur **Oui**.

<figure><img src="../.gitbook/assets/msedge_SfrINmFk2K.png" alt=""><figcaption></figcaption></figure>

6. Le modèle sélectionné sera définitivement supprimé de l’application.

<figure><img src="../.gitbook/assets/msedge_s34nqIFLdc.png" alt=""><figcaption></figcaption></figure>

Suivez ces étapes pour modifier les paramètres du modèle.

Les paramètres du modèle incluent le type de document auquel le modèle est associé — tel que Feuille de tournée, Feuille de chargement, Feuille d’autocollants, Bon de livraison, Rapport de visite ou Rapport de mission — ainsi que les agences pour lesquelles le modèle est disponible

1. Pour modifier les paramètres, cliquez sur le **Modifier** bouton à côté du nom du modèle.

<figure><img src="../.gitbook/assets/msedge_bJiWkKs0cj.png" alt=""><figcaption></figcaption></figure>

2. Vous pouvez mettre à jour le type de document et les agences associées au modèle.
3. Une fois les modifications effectuées, cliquez sur **Enregistrer** pour appliquer et enregistrer les paramètres mis à jour.

<figure><img src="../.gitbook/assets/msedge_rPyc85lVSs.png" alt=""><figcaption></figcaption></figure>

### Type de configuration personnalisé

Nomadia Delivery propose désormais une affectation automatique basée sur des règles pour les types de configuration — couvrant à la fois le sous-statut et la notification — en fonction des paramètres de mission. Cette amélioration permet aux planificateurs de personnaliser le cycle de livraison selon les besoins opérationnels, d’automatiser les décisions récurrentes et de maintenir des workflows cohérents entre différents types de mission.

Type de configuration du sous-statut

Les types de configuration du sous-statut définissent les étapes intermédiaires ou les conditions au sein du cycle de vie d’une mission. Alors qu’ils étaient auparavant limités à BASIC, INTERMEDIATE et ADVANCED, les planificateurs peuvent désormais créer un nombre illimité de types de sous-statut personnalisés, adaptés à des processus métier spécifiques.

Type de configuration de notification

Les types de configuration de notification déterminent comment et quand les clients sont informés pendant le cycle de vie de la mission. Au lieu de s’appuyer sur un seul modèle, les planificateurs peuvent désormais configurer plusieurs modèles de notification pour répondre à différents scénarios.

Les deux types de configuration peuvent être affectés automatiquement en fonction des attributs de la mission, tels que le type de client ou la valeur du colis.

Suivez ces étapes pour configurer le type

1. Ouvrez l’application Nomadia Delivery et accédez à la **Configuration** .
2. Dans la liste déroulante, sélectionnez **Types de configuration.**
3. Par défaut, Nomadia Delivery fournit trois types de configuration : BASIC, INTERMEDIATE et ADVANCED. Vous pouvez soit utiliser ces types existants, soit en créer un nouveau à partir de zéro.
4. Pour modifier un type de configuration existant, cliquez sur l’icône Crayon à côté de celui-ci.

<figure><img src="../.gitbook/assets/msedge_usuFRiPbuV.png" alt=""><figcaption></figcaption></figure>

5. Dans l’onglet Général, activez les interrupteurs en fonction de vos besoins :

* Activez les deux interrupteurs si le type de configuration doit s’appliquer au sous-statut et à la notification.
* Activez-les ou désactivez-les individuellement si vous souhaitez des configurations séparées pour le sous-statut et la notification.

6. Vous pouvez définir des règles d’affectation automatique afin que les types de configuration soient appliqués sans intervention manuelle. Ces règles sont basées sur les champs de l’objet mission :

* Si une condition est remplie, le type de configuration est automatiquement appliqué au sous-statut et/ou à la notification.
* Plusieurs conditions peuvent être définies, et vous pouvez choisir si toutes les conditions doivent être remplies ou si une seule suffit en activant le **Suivre toutes les règles** interrupteur.

7. Si plusieurs types de configuration répondent aux conditions, le système attribuera celui ayant la priorité la plus élevée (1 étant la plus élevée).

<figure><img src="../.gitbook/assets/msedge_NMTNkI9zRY.png" alt=""><figcaption></figcaption></figure>

8. Le tableau ci-dessous illustre comment différents types de configuration, conditions et règles influencent l’affectation automatique des valeurs dans l’objet mission.

| Configurationtype | Applicableà                 | Règles                                                                                     | Affectation automatique surl’objet mission                                                                                           |
| ----------------- | --------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ |
| BASIC             | Sous-statut et notification | Valeur du colis < 49 €Priorité = 4Suivre toutes les règles = NON                           | Si la valeur du colisde la mission = 39 €Type de configuration du statut = BASICType de configuration de notification =BASIC         |
| INTERMEDIATE      | Sous-statut et notification | Valeur du colis < 100 € Valeur du colis > 50 € Priorité = 3Suivre toutes les règles = OUI  | Si la valeur du colisvaleur = 99 €Type de configuration du statut = INTERMEDIATEType de configuration de notification = INTERMEDIATE |
| ADVANCED          | Sous-statut et notification | Valeur du colis < 500 € Valeur du colis > 100 € Priorité = 2Suivre toutes les règles = OUI | Si la valeur du colisvaleur = 499 €Type de configuration du statut = ADVANCEDType de configuration de notification = ADVANCED        |
| LUXURY            | Sous-statut et notification | Valeur du colis > 500 €Priorité = 1Suivre toutes les règles = NON                          | Si la valeur du colisvaleur = 500 €Type de configuration du statut = LUXURYType de configuration de notification =LUXURY             |

Remarque : Le type de configuration du sous-statut attribué à l’objet mission prend la priorité la plus élevée, sauf si une configuration de zone le remplace explicitement.

9. Une fois les règles configurées, toute mission nouvellement créée ou importée héritera automatiquement des types de configuration correspondants, et les valeurs de mission seront renseignées en conséquence.

<figure><img src="../.gitbook/assets/msedge_Uuoe7RVqrB.png" alt=""><figcaption></figcaption></figure>

10. Dans des cas exceptionnels, les utilisateurs peuvent mettre à jour manuellement les types de configuration du sous-statut ou de la notification. Si ces modifications sont en conflit avec les affectations basées sur des règles, une fenêtre contextuelle de confirmation apparaîtra

Si confirmé, les modifications manuelles seront conservées.

Si refusé, le système reviendra aux configurations attribuées automatiquement.

<figure><img src="../.gitbook/assets/image 106.png" alt=""><figcaption></figcaption></figure>

<br>
