# Livraison en PUDO

Le flux de livraison PUDO (Pick-Up Drop-Off) permet aux chauffeurs de rediriger les colis vers des points relais locaux lorsque les clients sont indisponibles. Cette fonctionnalité élimine le besoin de tournées de re-livraison coûteuses et maintient votre arriéré d’entrepôt à un niveau gérable. Vous obtiendrez de meilleurs taux de résolution au premier essai et offrirez davantage de flexibilité à vos clients.

#### Pour commencer

Avant d’utiliser cette fonctionnalité, assurez-vous que les exigences suivantes sont remplies :

* Les données du réseau PUDO sont configurées dans le système.
* Le **fallback delivery in PUDO** champ est activé pour la mission spécifique.
* Les sous-statuts pour les dépôts PUDO échoués (par ex. « PUDO full ») sont définis dans le **menu de configuration**.
* Créez un itinéraire dans le back-office.
* Sélectionnez la case à cocher de l’itinéraire que vous souhaitez partager dans le **tableau des itinéraires**.

<figure><img src="../../.gitbook/assets/image (905).png" alt=""><figcaption></figcaption></figure>

* Cliquez sur le **actions** bouton.

<figure><img src="../../.gitbook/assets/image (906).png" alt=""><figcaption></figcaption></figure>

* Sélectionnez **publier sur l’application mobile**.

<figure><img src="../../.gitbook/assets/image (907).png" alt=""><figcaption></figcaption></figure>

* Cliquez sur **OK** pour confirmer la publication.

<figure><img src="../../.gitbook/assets/image (908).png" alt=""><figcaption></figcaption></figure>

#### Présentation de la fonctionnalité

* **page de sélection du point PUDO**: Affiche une liste de lieux relais préchargés près de l’adresse du client.

<figure><img src="../../.gitbook/assets/image (909).png" alt=""><figcaption></figcaption></figure>

* **curseur de rayon de recherche**: Permet au chauffeur d’augmenter ou de diminuer la distance pour trouver davantage de points relais.

<figure><img src="../../.gitbook/assets/image (910).png" alt=""><figcaption></figcaption></figure>

* **ID du lieu de livraison PUDO**: Enregistre automatiquement le point précis où le chauffeur a déposé le colis.

<figure><img src="../../.gitbook/assets/image (911).png" alt=""><figcaption></figcaption></figure>

* **onglet des journaux de mission**: Suit chaque action, de la première tentative de livraison au dépôt final en PUDO.

<figure><img src="../../.gitbook/assets/image (912).png" alt=""><figcaption></figcaption></figure>

#### Mode d’emploi : gérer les livraisons échouées

**Chauffeur : redirection d’un colis**

1. Touchez l’itinéraire partagé dans l’application mobile.
2. Chargez le véhicule et touchez **valider mon chargement**.

<figure><img src="../../.gitbook/assets/image (913).png" alt=""><figcaption></figcaption></figure>

3. Touchez **démarrer mon itinéraire**.
4. À l’adresse du client, sélectionnez **ne pas livrer** si le client est absent.

<figure><img src="../../.gitbook/assets/image (914).png" alt=""><figcaption></figcaption></figure>

5. Sélectionnez le **client indisponible** sous-statut.
6. Faites glisser le curseur pour ajuster le rayon de recherche si nécessaire.
7. Sélectionnez un **point PUDO** dans la liste.
8. Confirmez le statut et poursuivez les autres livraisons.
9. Lorsque vous êtes prêt à déposer, touchez la notification du point relais dans les **détails de l’itinéraire**.
10. Sélectionnez la mission et utilisez le **scanner** pour déposer le colis.

<figure><img src="../../.gitbook/assets/image (915).png" alt=""><figcaption></figcaption></figure>

11. Capturez la **signature** et une **photo** pour valider le dépôt.

**Planificateur : vérifier le dépôt**

1. Cliquez sur le **bouton d’actualisation** dans le back-office pour voir les mises à jour en temps réel.

<figure><img src="../../.gitbook/assets/image (916).png" alt=""><figcaption></figcaption></figure>

2. Ouvrez la mission dans l’ **éditeur** pour vérifier le **ID du lieu de livraison PUDO**.
3. Vérifiez le **onglet des journaux** pour une séquence complète d’actions horodatées.

**Dépannage : problèmes PUDO**

Si un point PUDO est plein ou fermé :

1. Marquez la mission comme **non livrée au point PUDO**.
2. Sélectionnez le sous-statut spécifique, tel que **PUDO full** ou **PUDO closed**.
3. La mission apparaîtra comme **non résolue** pour le planificateur.
4. Incluez la mission dans le prochain **cycle de planification** pour une tentative de re-livraison.

#### Conseils de productivité

* 💡 **Détection automatique**: Le système identifie automatiquement les emplacements PUDO dans un rayon de 5 km autour de l’itinéraire.
* 💡 **Données préchargées**: Les chauffeurs n’ont pas besoin de chercher manuellement, car les options les plus proches sont préchargées avant qu’ils n’ouvrent l’application.
* 💡 **Synchronisation en temps réel**: Les informations se synchronisent avec le back-office immédiatement après que le chauffeur a confirmé le dépôt.
* ⚠️ **Sous-statuts précis**: Utilisez toujours le sous-statut correct pour les points PUDO pleins ou fermés afin de garantir que la mission soit suivie pour une re-livraison.
