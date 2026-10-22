# Logistique inverse

Nomadia Delivery intègre la logistique inverse directement dans le cycle de vie standard de vos missions. Cette fonctionnalité vous permet de déclencher, planifier et exécuter les retours sans quitter la plateforme. Vous obtiendrez une visibilité complète et un routage optimisé pour chaque trajet de retour.

#### Pour commencer

* Accès au **Back Office Nomadia Delivery**.
* Le **Identifiant de mission** de la livraison échouée ou non collectée.
* Accès API au **Logistique inverse** point de terminaison.
* Ouvrez le **Back Office** et localisez l’itinéraire spécifique contenant la mission à retourner.
* Identifiez si l’article doit retourner au donneur d’ordre initial ou simplement à l’agence.

#### Présentation de la fonctionnalité

* **Identifiant de mission**: Un code unique avec un **\_r** suffixe utilisé pour suivre les retours jusqu’à leur origine.

<figure><img src="../.gitbook/assets/image (942).png" alt=""><figcaption></figcaption></figure>

* **Retour à l’expéditeur**: Un paramètre déterminant si un article est acheminé vers l’expéditeur ou reste à l’agence.
* **Nouveau type de mission**: Utilisez le **Type de mission** paramètre pour classer le retour comme une **Cross Docking**, **Livraison**, ou **Enlèvement** mission.
* **Bouton Modifier**: Cela ouvre les détails de la mission pour vérifier que les adresses de collecte et de livraison ont bien été inversées.

<figure><img src="../.gitbook/assets/image (943).png" alt=""><figcaption></figcaption></figure>

#### Mode d’emploi : créer un retour Cross Docking

Utilisez cette tâche lorsque l’article doit retourner au donneur d’ordre initial via l’agence.

1. Copiez le **Identifiant de mission** de la mission d’origine dans le **Back Office** ou récupérez la liste des missions qui doivent être renvoyées à l’expéditeur via l’API.

<figure><img src="../.gitbook/assets/image (944).png" alt=""><figcaption></figcaption></figure>

2. Incluez la liste des identifiants de mission dans le tableau Mission Ids.
3. Définissez le **Retour à l’expéditeur** paramètre à **Vrai**.
4. Définissez le **Nouveau type de mission** sur **Cross Docking**.
5. Sélectionnez **Exécuter** pour générer la ou les missions de retour**en une seule fois**.

<figure><img src="../.gitbook/assets/image (945).png" alt=""><figcaption></figcaption></figure>

6. **Actualisez** l’ **Back Office** interface pour voir la nouvelle mission avec le **\_r** suffixe.
7. Incluez la nouvelle **Cross-docking** mission dans le prochain cycle de planification pour l’optimisation.

#### Mode d’emploi : créer un retour de livraison

Utilisez cette tâche lorsque l’article doit seulement parvenir à l’agence pour être récupéré par l’expéditeur.

1. Copiez le **Identifiant de mission** pour la mission de livraison échouée ou récupérez la liste des missions qui doivent être renvoyées à l’agence via l’API.
2. Ajoutez la liste des identifiants de mission au tableau **Mission IDs** .
3. Définissez le **Retour à l’expéditeur** paramètre à **Faux**.
4. Définissez le **Nouveau type de mission** sur **Enlèvement**.
5. Sélectionnez **Exécuter** pour créer la mission.
6. Actualisez l’ **Back Office** interface pour voir la nouvelle mission avec le `_r` suffixe..

#### Conseils de productivité

* 💡 **Suivi unifié**: Utilisez le **\_r** suffixe pour relier instantanément tout retour à sa livraison aller d’origine.
* 💡 **Planification fluide**: Traitez les missions de retour comme des missions standard afin de les inclure dans l’optimisation automatisée des itinéraires.
* ⚠️ **Contournements manuels**: Évitez d’utiliser des tableurs pour suivre les retours en dehors du système afin de prévenir le chaos des données.
