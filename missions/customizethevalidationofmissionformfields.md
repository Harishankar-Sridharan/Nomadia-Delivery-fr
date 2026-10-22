# Personnaliser la validation des champs du formulaire de mission

La personnalisation de la validation obligatoire impose la saisie de données requises dans les champs du formulaire de mission de **Nomadia Delivery**. Les répartiteurs ont besoin de champs obligatoires pour éviter l’envoi de formulaires de mission incomplets lors des opérations quotidiennes. Configurez les champs obligatoires pour garantir des rapports de terrain précis et la conformité complète des données.

## Avant de commencer

Prérequis administratifs et étapes de configuration :

* Un profil de formulaire de mission actif avec des identifiants de champs.

Étapes de configuration initiale :

1. Ouvrez la page **Configuration**.

![Ouvrez la page Configuration](../.gitbook/assets/FormFieldValidation_BeforeBegin_001.gif)

2. Cliquez sur **Champs personnalisés** pour gérer les champs du formulaire.

![Cliquez sur Champs personnalisés pour gérer les champs du formulaire](../.gitbook/assets/FormFieldValidation_BeforeBegin_002.gif)

## Vue d’ensemble de la fonctionnalité

Principaux éléments de l’interface utilisateur :

* **Configuration** : ouvre les préférences système globales et les options de personnalisation.
* **Champs personnalisés** : affiche les champs de formulaire personnalisables pour les profils de mission.
* **Identifiant** : représente un champ de mission précis sélectionné pour les paramètres de validation.
* **Obligatoire** : active ou désactive le statut de validation requise pour forcer la saisie des données avant l’enregistrement.
* **Assigner l’aide** : définit les consignes d’aide aux champs obligatoires pour les opérateurs de terrain.
* **Missions** : affiche la base de données des missions pour tester les validations de champs mises à jour.

## Configurer les règles de validation obligatoire

Configurez la validation obligatoire pour les champs du formulaire de mission :

1. Ouvrez la page **Configuration**.

2. Cliquez sur **Champs personnalisés**.

3. Sélectionnez un **Identifiant** quelconque.

![Sélectionnez un Identifiant quelconque](../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_001.gif)

4. Activez **Obligatoire** pour activer la validation de champ obligatoire.

![Activez Obligatoire pour activer la validation de champ obligatoire](../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_002.gif)

5. Cliquez sur **Enregistrer**.

![Cliquez sur Enregistrer](../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_003.png)

6. Sélectionnez **Assigner un hub** et rendez-le obligatoire.

![Sélectionnez Assigner un hub et rendez-le obligatoire](../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_004.gif)

7. Cliquez sur **Enregistrer**.

![Cliquez sur Enregistrer](../.gitbook/assets/FormFieldValidation_ConfigureMandatoryValidationRules_005.png)

## Appliquer la validation aux enregistrements de mission

Appliquez les règles de validation obligatoire lors de la modification des profils de mission :

1. Accédez à **Missions**.

![Accédez à Missions](../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_001.gif)

2. Cliquez sur **Actions**.

![Cliquez sur Actions](../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_002.gif)

3. Cliquez sur **Ajouter**.
4. Cliquez sur **Agence**.

![Cliquez sur Agence](../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_003.gif)

5. Cliquez sur **Suivant**.

![Cliquez sur Suivant](../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_004.gif)

6. Sélectionnez **Modifier**.

![Sélectionnez Modifier](../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_005.gif)

7. Cliquez sur **Champs personnalisés** et vérifiez si **Hub A** est obligatoire.

![Cliquez sur Champs personnalisés et vérifiez si le Hub A est obligatoire](../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_006.gif)

### Dépannage

Résolvez les erreurs d’envoi du formulaire :

* **Impossible d’enregistrer la mission** : les champs obligatoires non sélectionnés bloquent l’envoi. Sélectionnez **Assigner un hub** avant d’enregistrer.

![Impossible d’enregistrer la mission : les champs obligatoires non sélectionnés bloquent l’envoi](../.gitbook/assets/FormFieldValidation_ApplyValidationMissionRecords_007.png)

## Conseils

Bonnes pratiques et avertissements opérationnels :

{% hint style="info" %}
**Mises à jour automatiques des champs obligatoires** : activez ou désactivez la validation des champs obligatoires pour mettre à jour instantanément les règles obligatoires dans les formulaires de mission.
{% endhint %}

{% hint style="warning" %}
**Champs obligatoires non sélectionnés** : ne laissez pas de champs obligatoires non sélectionnés, sinon le système empêche l’enregistrement de la mission.
{% endhint %}

## Rubriques connexes

* [Ajout d'une mission](adding-a-mission.md)
* [Création d’une adresse ad hoc](adhocaddresscreation.md)
* [Déclarer un colis pour une mission de conteneur](declaringaparcelforacontainermission.md)
