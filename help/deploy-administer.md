---
title: Administrer et gérer les utilisateurs
description: Cas pratiques d’administration tels que le déploiement et la gestion des utilisateurs dans  [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: 552dcf43677ac2a95864666faab9938534f70d40
workflow-type: tm+mt
source-wordcount: '1139'
ht-degree: 99%

---

# Administrer [!DNL Assets Essentials] et ajouter des utilisateurs {#administer}

[!DNL Adobe Experience Manager Assets Essentials] est configuré par Adobe pour ses clients. Dans le cadre de la mise en service, [!DNL Assets Essentials] est ajouté à l’organisation d’un client dans [!DNL Adobe Admin Console]. Les administrateurs utiliseront [!DNL Admin Console] pour gérer les droits des utilisateurs à la solution [!DNL Assets Essentials] et affecter des administrateurs d’applications à la configuration d’autorisations et de formulaires de métadonnées dans [!DNL Assets Essentials].

Pour gérer Assets Essentials en fonction des parcours, cliquez sur cette icône [link](adminster-aem-assets-essentials.md).

## Déploiement automatique d’Assets Essentials {#automatic-deployment-assets-essentials}

Une fois la solution Assets Essentials configurée, l’administrateur reçoit un e-mail d’Adobe. L’e-mail contient un message de bienvenue et un lien permettant de commencer. De plus, Adobe lance automatiquement le processus de déploiement d’Assets Essentials. Le processus de déploiement dure une heure.

À partir du lien dans l’e-mail, accédez à l’[Admin Console](https://adminconsole.adobe.com) et connectez-vous. Si vous avez accès à plusieurs comptes d’organisation en tant qu’administrateur, sélectionnez l’organisation concernée ou changez-la à l’aide du sélecteur dans la barre supérieure. Une fois le processus de déploiement automatique terminé, la fiche produit dʼ[!DNL AEM Assets Essentials] est visible dans [!DNL Admin Console].

![Déploiement d’Assets Essentials](assets/assets-essentials-deployment.png)

Les administrateurs doivent effectuer les tâches suivantes après le déploiement réussi de la solution Assets Essentials :

* [Configurez les groupes d’utilisateurs, la structure des dossiers et attribuez les autorisations](manage-permissions.md) pour la solution. Suivez les [bonnes pratiques](permission-management-best-practices.md) pour garantir une configuration des autorisations simple et efficace.
* [Gérer l’](#add-users-to-essentials)accès utilisateur des membres de l’organisation à [!DNL Assets Essentials].
* Éventuellement, [afficher l’état de service et les journaux](#view-logs).

>[!NOTE]
>
>Si Assets Essentials a été configuré avant le 6 janvier 2022, suivez la [procédure de déploiement dans Cloud Manager](#deploy-essentials) avant de gérer l’accès utilisateur des membres de l’organisation.


## Gestion des utilisateurs {#add-users-to-essentials}

Un administrateur gère les utilisateurs qui ont accès à [!DNL Assets Essentials]. Les administrateurs utilisent [!DNL Adobe Admin Console] pour ajouter ou supprimer un accès utilisateur. [!DNL Assets Essentials] Dispose des deux types d’accès utilisateur suivants.

* Les **[!DNL Assets Essentials]administrateurs** ont un accès administratif à l’application ; En plus de toutes les fonctionnalités de l’utilisateur final, les administrateurs d’applications de ce groupe peuvent gérer les autorisations de n’importe quel dossier et groupe/utilisateur dans l’ensemble du référentiel de l’application.
* Les **[!DNL Assets Essentials] utilisateurs** ont accès à l’interface utilisateur complète. Ces utilisateurs peuvent charger, organiser, baliser et rechercher des ressources numériques.
* Les **[!DNL Assets Essentials] utilisateurs consommateurs** : disposent d’un accès à l’expérience de sélection de ressources incorporée dans l’éditeur de modèles d’e-mail [!DNL Adobe Journey Optimizer]. Consultez [Utiliser  [!DNL Assets Essentials]  dans  [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=fr) pour plus d’informations.

Dans [!DNL Admin Console], ces trois types d’accès sont représentés par trois [!UICONTROL Profils de produits]. Pour ajouter et supprimer des membres de votre organisation à l’un des deux profils, procédez comme suit :

1. Accédez à [!DNL Admin Console] pour votre organisation, cliquez sur **[!UICONTROL Produits]** dans la barre supérieure, cliquez sur **[!UICONTROL AEM Assets Essentials]**, puis sur l’environnement [!DNL Assets Essentials]. [!DNL Assets Essentials] possède trois profils de produits qui représentent l’accès pour les administrateurs, les utilisateurs réguliers et les consommateurs.

   ![Trois profils pour trois types d’utilisateurs](assets/admin-console-admin-profile.png)
   <!-- Need to update screenshot to include 3 profiles -->

   *Figure : trois profils sont disponibles pour ajouter les trois types d’utilisateurs.*

1. Pour ajouter un utilisateur à un groupe, cliquez sur le groupe, sélectionnez **[!UICONTROL Ajouter un utilisateur]**, fournissez les détails de l’utilisateur, puis cliquez sur **[!UICONTROL Enregistrer]**. Lorsque vous ajoutez un utilisateur, celui-ci reçoit une invitation par courrier électronique qui lui permet de commencer à l’utilisateur. Vous pouvez désactiver les invitations par e-mail dans les paramètres du profil de produit dans l’[!DNL Admin Console].

   ![Ajout d’un utilisateur à [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Image : ajouter un utilisateur à [!DNL Assets Essentials] partir de l’[!DNL Admin Console].*

1. Pour supprimer un utilisateur d’un groupe, cliquez sur le groupe, sélectionnez un utilisateur existant, puis **[!UICONTROL Supprimer l’utilisateur]**.

>[!TIP]
>
>Dans l’[!DNL Admin Console], vous pouvez gérer les utilisateurs en bloc à l’aide de fichiers CSV. Pour en savoir plus, consultez la documentation [[!DNL Admin Console] ](https://helpx.adobe.com/fr/enterprise/using/accounts.html).

## Affichage de l’état du service et des journaux d’accès {#view-logs}

Après la mise en service, les administrateurs ne déploient [!DNL Assets Essentials] qu’une seule fois. Après le déploiement initial, Adobe effectue la maintenance et les mises à jour du service. Les administrateurs peuvent utiliser l’interface utilisateur de [!DNL Cloud Manager] pour vérifier l’état du service et télécharger les journaux d’accès récents.

1. Lorsque les utilisateurs signalent des problèmes, vérifiez l’état du service [!DNL Assets Essentials] dans l’interface **[!UICONTROL Aperçu du programme]**. Pendant le fonctionnement normal de la solution, l’état est `Running`. Si [!DNL Cloud Manager] affiche un autre état, créez un ticket de support dans la section support de l’[!DNL Admin Console].

   ![État d’[!DNL Assets Essentials] dans [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Image : l’état normal d’[!DNL Assets Essentials] dans [!DNL Cloud Manager] est `Running`.*

1. Pour télécharger les journaux d’accès récents, cliquez sur ![icône d’options](assets/do-not-localize/options-ellipses-icon.png), sélectionnez **[!UICONTROL Télécharger les journaux]** et suivez les instructions à l’écran. Vous pouvez contrôler les demandes d’accès HTTPS à l’aide des journaux.

   ![Option de téléchargement des journaux d’accès](assets/cloudmanager-download-logs.png)

   *Image : option de téléchargement des journaux d’accès.*

## Déploiement dʼ[!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Exécutez les étapes suivantes uniquement dans le cas où Assets Essentials a été configuré avant le 6 janvier 2022.

Après la mise en service, le droit [!DNL Assets Essentials] est ajouté à votre organisation dans [!DNL Admin Console]. Avant que la solution ne soit disponible pour l’utilisateur, l’ administrateur de l’organisation doit la déployer. L’administrateur effectue un déploiement unique à l’aide de l’interface utilisateur [!DNL Cloud Manager]. Après le déploiement initial, Adobe effectue la maintenance et les mises à jour du service. Une fois la solution configurée, l’administrateur reçoit un courrier électronique d’Adobe. L’e-mail contient un message de bienvenue et un lien permettant de commencer. Pour lancer le déploiement, procédez comme suit :

1. À partir du lien dans l’e-mail, accédez à l’[Admin Console](https://adminconsole.adobe.com) et connectez-vous. Si vous avez accès à plusieurs comptes d’organisation en tant qu’administrateur, sélectionnez l’organisation concernée ou changez-la à l’aide du sélecteur dans la barre supérieure. La carte de présentation produit d’[!DNL Assets Essentials] est visible dans l’[!DNL Admin Console].

   ![[!DNL Assets Essentials] dans l’[!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Image : carte d’[!DNL Assets Essentials] dans l’[!DNL Admin Console].*

   >[!NOTE]
   >
   >Si la fiche dʼ&#x200B;**[!UICONTROL AEM Assets Essentials]** est visible dans la section produits au lieu de la fiche dʼ&#x200B;**[!UICONTROL AEM Assets Essentials - Cloud Manager]**, le déploiement d’Assets Essentials est déjà terminé. Vous pouvez ignorer les étapes restantes.

1. Ajoutez-vous en tant qu’administrateur au profil de produit `AEM Assets Essentials - Cloud Manager` dans l’[!DNL Admin Console]. Vous pouvez choisir un autre membre pour être administrateur de votre organisation ou même ajouter plusieurs administrateurs.

1. Cliquez sur ![Ajouter une icône](assets/do-not-localize/add-icon.svg) dans [!UICONTROL Sélectionner les profils de produit], puis sélectionnez [!UICONTROL Gestionnaire de déploiement - Assets Essentials] dans **[!UICONTROL profil de produit]**. L’utilisateur ajouté à cette étape reçoit un courrier électronique d’Adobe lui donnant l’accès à [!DNL Cloud Manager] pour en effectuer le déploiement.

   ![Ajoutez un administrateur et sélectionnez un profil de produit dans [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Image : ajout d’un administrateur et sélection d’un profil de produit dans l’[!DNL Admin Console].*

1. Pour accéder à [!DNL Cloud Manager], cliquez sur le lien contenu dans l’e-mail d’accès à [!DNL Cloud Manager]. Vous pouvez également accéder à [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) dans votre navigateur.

1. Dans l’interface utilisateur de Cloud Manager, cliquez sur **[!UICONTROL Ajouter un programme]** dans le coin supérieur droit.

1. Attribuez un nom à votre convenance et, éventuellement, téléchargez une image (elle représente le programme dans [!DNL Cloud Manager]), puis cliquez sur **[!UICONTROL Créer]**. [!DNL Cloud Manager] A besoin de quelques minutes pour configurer le programme.

1. Lorsque le programme est prêt, pointez sur la mosaïque et cliquez sur ![icône d’ajout d’environnement](assets/do-not-localize/add-environment-icon.png).

1. Pour ajouter le service [!DNL Assets Essentials] à votre organisation, cliquez sur **[!UICONTROL Ajouter un environnement]**, sélectionnez un nom et une région de déploiement, puis cliquez sur **[!UICONTROL Enregistrer]**. Vous ne pouvez pas modifier ultérieurement la région de déploiement. Essayez de faire correspondre la région de déploiement de [!DNL Assets Essentials] avec la région de déploiement de l’autre solution avec laquelle vous envisagez d’utiliser [!DNL Assets Essentials]. Leur correspondance permet de garantir un accès réseau le plus rapide possible aux ressources numériques et une latence la plus faible possible.

   ![Ajout d’un environnement dans [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Image : ajouter un environnement dans [!DNL Cloud Manager] pour commencer à utiliser [!DNL Assets Essentials].*

1. Après quelques minutes, une fois l’environnement créé, vous pourrez accéder à [!DNL Admin Console] et ajouter les utilisateurs de votre entreprise à la solution [!DNL Assets Essentials]. Cliquez sur ![icône d’options](assets/do-not-localize/options-ellipses-icon.png) et sélectionnez l’option **[!UICONTROL Gérer l’accès]**.

   ![Préparer l’environnement dans [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Image : un environnement dans [!DNL Cloud Manager] prêt à l’emploi.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] help](https://helpx.adobe.com/fr/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] help](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=fr)
>* [Documentation Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=fr)
>* [Notes de mise à jour](release-notes.md)
>* [Prise en main d’ [!DNL Assets Essentials]](get-started.md)

