---
title: Déploiement et gestion des utilisateurs
description: Cas pratiques d’administration tels que le déploiement et la gestion des utilisateurs dans  [!DNL Assets Essentials].
role: Administrator
source-git-commit: a9dfa9cc9e971faf24e5275c843fb1d0247d18c9
workflow-type: tm+mt
source-wordcount: '887'
ht-degree: 2%

---


# Déployer [!DNL Assets Essentials] et ajouter des utilisateurs {#administer}

[!DNL Adobe Experience Manager Assets Essentials] est configurée par Adobe pour ses clients. Dans le cadre de la mise en service, [!DNL Assets Essentials] est ajouté à l’organisation d’un client dans [!DNL Adobe Admin Console]. Les clients ont également accès à [!DNL Experience Manager Cloud Manager] en tant qu’outil de déploiement et à [!DNL Admin Console] pour gérer les droits des utilisateurs à la solution [!DNL Assets Essentials].

Les administrateurs effectuent les tâches suivantes :

* [ [!DNL Assets Essentials]](#deploy-essentials) Déploiement pour leur organisation.
* [Gérez l’](#add-users-to-essentials) accès des utilisateurs aux membres de l’organisation sur  [!DNL Assets Essentials].
* Éventuellement, [afficher l’état du service et les journaux](#view-logs).

## Déploiement [!DNL Assets Essentials] {#deploy-essentials}

Après la mise en service, le droit [!DNL Assets Essentials] est ajouté à votre organisation dans [!DNL Admin Console]. Avant que la solution ne soit disponible pour l’utilisateur, un administrateur d’organisation doit la déployer. L’administrateur effectue un déploiement unique à l’aide de l’interface utilisateur [!DNL Cloud Manager]. Après le déploiement initial, Adobe effectue la maintenance et les mises à jour du service. Une fois la solution configurée, l’administrateur reçoit un courrier électronique de l’Adobe. L’email contient un message de bienvenue et un lien pour commencer. Pour déployer, procédez comme suit :

1. A partir du lien contenu dans l&#39;email, accédez au [Admin Console](https://adminconsole.adobe.com) et connectez-vous. Si vous avez accès en tant qu’administrateur à plusieurs comptes d’organisation, sélectionnez l’organisation appropriée ou basculez-y à l’aide du sélecteur dans la barre supérieure. La carte du produit pour [!DNL Assets Essentials] est visible dans la balise [!DNL Admin Console].

   ![[!DNL Assets Essentials] carte dans  [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Figure :  [!DNL Assets Essentials] dans  [!DNL Admin Console].*

1. Ajoutez-vous en tant qu’administrateur au profil de produit `AEM Assets Essentials - Cloud Manager` dans la section [!DNL Admin Console]. Au lieu de vous-même, vous pouvez ajouter un autre membre de votre organisation ou ajouter plusieurs administrateurs.

1. Cliquez sur ![Ajouter une icône](assets/do-not-localize/add-icon.svg) à [!UICONTROL Sélectionner les profils de produit], puis sélectionnez [!UICONTROL Gestionnaire de déploiement - Assets Essentials] comme **[!UICONTROL profil de produit]**. L’utilisateur ajouté à cette étape reçoit un courrier électronique de l’Adobe ayant accès à [!DNL Cloud Manager] et peut effectuer le déploiement.

   ![Ajoutez un administrateur et sélectionnez un profil de produit dans  [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Figure : Ajoutez un administrateur et sélectionnez un profil de produit dans  [!DNL Admin Console].*

1. Pour accéder à [!DNL Cloud Manager], cliquez sur le lien contenu dans l&#39;email avec accès à [!DNL Cloud Manager]. Vous pouvez également accéder à [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) dans votre navigateur.

1. Dans l’interface utilisateur de Cloud Manager, cliquez sur **[!UICONTROL Ajouter le programme]** dans le coin supérieur droit.

1. Attribuez un nom à votre choix et, éventuellement, téléchargez une image (elle représente le programme dans [!DNL Cloud Manager]), puis cliquez sur **[!UICONTROL Créer]**. [!DNL Cloud Manager] la configuration du programme prend quelques minutes.

1. Lorsque le programme est prêt, placez le pointeur sur la mosaïque et cliquez sur ![icône d’ajout d’environnement](assets/do-not-localize/add-environment-icon.png).

1. Pour ajouter le service [!DNL Assets Essentials] à votre organisation, cliquez sur **[!UICONTROL Ajouter un environnement]**, sélectionnez un nom et une région de déploiement, puis cliquez sur **[!UICONTROL Enregistrer]**. Vous ne pouvez pas modifier la région de déploiement ultérieurement. Essayez de faire correspondre la région de déploiement de [!DNL Assets Essentials] avec la région de déploiement de l’autre solution avec laquelle vous envisagez d’utiliser [!DNL Assets Essentials]. La correspondance est de garantir un accès réseau le plus rapide possible aux ressources numériques et une latence la plus faible possible.

   ![Ajout d’un environnement dans  [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Figure : Ajoutez un environnement dans  [!DNL Cloud Manager] pour commencer à utiliser  [!DNL Assets Essentials].*

1. Après plusieurs minutes, une fois l’environnement créé, vous pouvez accéder à [!DNL Admin Console] et ajouter les utilisateurs de votre entreprise à la solution [!DNL Assets Essentials]. Cliquez sur l’icône ![options](assets/do-not-localize/options-ellipses-icon.png) et sélectionnez l’option **[!UICONTROL Gérer l’accès]** .

   ![Environnement prêt dans  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figure : Un environnement dans  [!DNL Cloud Manager] qui est prêt à l’emploi.*

## Gestion des utilisateurs {#add-users-to-essentials}

Un administrateur gère les utilisateurs qui ont accès à [!DNL Assets Essentials]. Les administrateurs utilisent [!DNL Adobe Admin Console] pour ajouter ou supprimer l’accès utilisateur. [!DNL Assets Essentials] dispose des deux types d’accès utilisateur suivants.

* **[!DNL Assets Essentials]** Les utilisateurs ont accès à l’interface utilisateur complète. Ces utilisateurs peuvent charger, organiser, baliser et rechercher des ressources numériques.
* **[!DNL Assets Essentials]Utilisateurs** consommateurs : ont accès à l’expérience de sélection de ressources incorporée dans l’éditeur de modèles d’ [!DNL Adobe Journey Optimizer] email. Pour plus d’informations, voir [Utilisation [!DNL Assets Essentials] dans [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

Dans [!DNL Admin Console], ces deux types d’accès sont représentés par deux [!UICONTROL Profils de produit]. Pour ajouter et supprimer des membres de votre organisation à l’un des deux profils, procédez comme suit :

1. Accédez à [!DNL Admin Console] pour votre organisation, cliquez sur **[!UICONTROL Produits]** dans la barre supérieure, cliquez sur **[!UICONTROL AEM Assets Essentials]**, puis sur l’environnement [!DNL Assets Essentials]. [!DNL Assets Essentials] comporte deux profils de produit qui représentent l’accès pour les utilisateurs standard et les utilisateurs consommateurs.

   ![Deux profils pour deux types d’utilisateurs](assets/adminconsole-user-types.png)

   *Figure : Deux profils sont disponibles pour ajouter les deux types d’utilisateurs.*

1. Pour ajouter un utilisateur à un groupe, cliquez sur le groupe, sélectionnez **[!UICONTROL Ajouter un utilisateur]**, fournissez les détails de l’utilisateur, puis cliquez sur **[!UICONTROL Enregistrer]**. Lorsque vous ajoutez un utilisateur, celui-ci reçoit une invitation par courrier électronique à démarrer. Vous pouvez désactiver les invitations par e-mail dans les paramètres du profil de produit dans [!DNL Admin Console].

   ![Ajout d’un utilisateur à  [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Figure : Ajoutez un utilisateur à  [!DNL Assets Essentials] partir de  [!DNL Admin Console].*

1. Pour supprimer un utilisateur d’un groupe, cliquez sur le groupe, sélectionnez un utilisateur existant, puis **[!UICONTROL Supprimer l’utilisateur]**.

>[!TIP]
>
>Dans [!DNL Admin Console], vous pouvez gérer les utilisateurs en bloc à l’aide de fichiers CSV. Pour en savoir plus, voir [[!DNL Admin Console] documentation](https://helpx.adobe.com/enterprise/using/accounts.html).

## Affichage de l’état du service et des journaux d’accès {#view-logs}

Après la mise en service, les administrateurs ne déploient [!DNL Assets Essentials] qu’une seule fois. Après le déploiement initial, Adobe effectue la maintenance et les mises à jour du service. Les administrateurs peuvent utiliser l’interface utilisateur [!DNL Cloud Manager] pour vérifier l’état du service et télécharger les journaux d’accès récents.

1. Lorsque les utilisateurs signalent des problèmes, vérifiez l’état du service [!DNL Assets Essentials] dans l’interface **[!UICONTROL Aperçu du programme]** . Pendant le fonctionnement normal de la solution, l’état est `Running`. Si [!DNL Cloud Manager] affiche un autre état, créez un ticket de support dans la section [!DNL Admin Console] support .

   ![État de  [!DNL Assets Essentials] dans  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figure : L’état normal de  [!DNL Assets Essentials] dans  [!DNL Cloud Manager] est  `Running`.*

1. Pour télécharger les journaux d’accès récents, cliquez sur l’icône ![options](assets/do-not-localize/options-ellipses-icon.png), sélectionnez **[!UICONTROL Télécharger les journaux]** et suivez les instructions à l’écran. Vous pouvez contrôler les demandes d’accès HTTPS à l’aide des journaux.

   ![ Option de téléchargement des journaux d’accès](assets/cloudmanager-download-logs.png)

   *Figure : Option de téléchargement des journaux d’accès.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] help](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] help](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=fr)
>* [Documentation Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Notes de mise à jour](release-notes.md)
* [Prise en main de [!DNL Assets Essentials]](get-started.md)

