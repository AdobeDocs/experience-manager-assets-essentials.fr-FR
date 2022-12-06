---
title: Intégrer Assets Essentials à Adobe Workfront
description: Intégrer Assets Essentials à l’application Adobe Workfront afin de pouvoir accéder au référentiel Assets Essentials dans l’application Workfront.
source-git-commit: 8920080944981fc1a990136af46c9258c5e8627c
workflow-type: tm+mt
source-wordcount: '569'
ht-degree: 100%

---

# Intégrer Assets Essentials à Adobe Workfront {#integrate-assets-essentials-workfront}

[[!DNL Adobe Workfront]](https://www.workfront.com/) est une application de gestion du travail qui vous permet de gérer l’ensemble du cycle de vie du travail en un seul endroit. L’intégration native entre [!DNL Adobe Workfront] et [!DNL Assets Essentials] permet aux entreprises d’accroître la vitesse du contenu et le délai de mise sur le marché en établissant des liens intrinsèques entre le travail et la gestion des ressources. Dans le cadre de la gestion de leur travail, les utilisateurs ont accès aux documents et images requis dans la même solution.

Exécutez les tâches suivantes pour intégrer Workfront à Experience Manager Assets Essentials :

* [Ajouter des utilisateurs aux profils de produits Workfront.](#add-users-to-product-profiles)

* [Ajouter des utilisateurs aux profils du produit Assets Essentials](#add-workfront-users-assets-essentials-product-profiles)

* [Configurer l’intégration d’Experience Manager Assets Essentials](#configure-assets-essentials-integration)

## Ajouter des utilisateurs aux profils de produits Workfront. {#add-users-to-product-profiles}

Pour ajouter des utilisateurs aux profils de produits Workfront :

1. Accédez à [Admin Console](https://adminconsole.adobe.com) de votre organisation, cliquez sur **[!UICONTROL Produits]** dans la barre supérieure, cliquez sur **[!UICONTROL Workfront]**, puis cliquez sur la première instance de la liste. Ne cliquez pas sur les deuxième et troisième instances de la liste.

   ![Profil administrateur Admin Console](assets/workfront-instances.png)

   Admin Console affiche le seul profil de produit disponible.

1. Pour ajouter un utilisateur à un profil de produit, cliquez sur le profil, cliquez sur **[!UICONTROL Ajouter un utilisateur]**, fournissez les détails de l’utilisateur, puis cliquez sur **[!UICONTROL Enregistrer]**.

   ![Ajouter le profil administrateur des utilisateurs](assets/add-users-workfront.png)

   Lorsque vous ajoutez un utilisateur, celui-ci reçoit une invitation par courrier électronique qui lui permet de commencer à l’utilisateur. Vous pouvez désactiver les invitations par e-mail dans les paramètres du profil de produit dans l’[!DNL Admin Console].

1. Pour supprimer un utilisateur d’un groupe, cliquez sur le groupe, sélectionnez un utilisateur existant, puis **[!UICONTROL Supprimer l’utilisateur]**.

Pour plus d’informations sur la création d’utilisateurs et d’administrateurs système dans Workfront avec Adobe Admin Console, voir [Gérer les utilisateurs dans Adobe Admin Console](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Ajouter des utilisateurs aux profils du produit Assets Essentials {#add-workfront-users-assets-essentials-product-profiles}

Affectez les utilisateurs de Workfront à l’un des profils de produit Assets Essentials suivants :

*  Les utilisateurs d’**[!DNL Assets Essentials]** ont accès à l’interface utilisateur complète d’Assets Essentials. Ces utilisateurs peuvent charger, organiser, baliser et rechercher des ressources numériques dans l’application Assets Essentials. En outre, les utilisateurs ont accès à l’expérience de sélection des ressources incorporées dans l’application [!DNL Adobe Workfront].
*  Les **[!DNL Assets Essentials] utilisateurs consommateurs** : ont accès à l’expérience de sélection de ressources incorporées dans l’application [!DNL Adobe Workfront].

En outre, il existe également un profil de produit **[!DNL Assets Essentials] Administrateurs** qui fournit un accès administratif à l’application.

Pour plus d’informations sur la manière d’affecter des utilisateurs aux profils de produit Assets Essentials, voir [Affecter des utilisateurs aux profils de produits Assets Essentials](deploy-administer.md#add-users-to-product-profiles).

## Configurer l’intégration d’Experience Manager Assets Essentials {#configure-assets-essentials-integration}

Après avoir ajouté des utilisateurs aux profils de produits Workfront et Assets Essentials à l’aide d’Admin Console, vous pouvez [configurer l’intégration d’Experience Manager Assets Essentials à Adobe Workfront](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

Après avoir configuré l’intégration, vous pouvez :

* [Lier des ressources et des dossiers à partir d’Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Envoyer un document à Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Vérifier une ressource liée pour Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Afficher ou télécharger une ressource liée à partir d’Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
