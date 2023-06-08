---
title: Administrer Experience Manager Assets Essentials
description: Configurez l’accès à l’application Assets Essentials à l’aide d’Admin Console, puis gérez les tâches qui peuvent être effectuées après s’être connecté à l’application Assets Essentials.
exl-id: ffd65741-21b7-47cd-9779-63a7903879e6
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: ht
source-wordcount: '1399'
ht-degree: 100%

---

# Administrer Experience Manager Assets Essentials {#administer-assets-essentials}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-assets.png)

## Objectif

* **Audience** : administrateurs d’Assets Essentials

* **Objectif** : configurer l’accès à l’application Assets Essentials à l’aide d’Admin Console, puis gérer les tâches qui peuvent être effectuées après s’être connecté à l’application Assets Essentials.

## Présentation {#overview}


[!DNL Adobe Experience Manager Assets Essentials] est configuré par Adobe pour ses clients. Dans le cadre de la mise en service, [!DNL Assets Essentials] est ajouté à l’organisation d’un client dans [!DNL Adobe Admin Console]. Les administrateurs utilisent [!DNL Admin Console] pour gérer les droits d’accès des utilisateurs à la solution [!DNL Assets Essentials] et affecter des administrateurs d’applications à la configuration d’autorisations et de formulaires de métadonnées dans [!DNL Assets Essentials].

Le diagramme de flux de données suivant illustre la séquence des tâches qu’un administrateur doit effectuer pour configurer et gérer Assets Essentials :

![Flux d’administration d’Assets Essentials](assets/permissions-management-cce-next.svg)

## Accéder à Admin Console {#access-admin-console}

Une fois la solution Assets Essentials configurée, l’administrateur reçoit un e-mail d’Adobe. L’e-mail contient un message de bienvenue et un lien permettant de commencer. De plus, Adobe lance automatiquement le processus de déploiement d’Assets Essentials. Le processus de déploiement dure une heure.

À partir du lien dans l’e-mail, accédez à l’[Admin Console](https://adminconsole.adobe.com) et connectez-vous. Si vous disposez d’un accès administrateur à plusieurs comptes d’organisation, alors sélectionnez l’organisation appropriée ou accédez à celle-ci à l’aide du [sélecteur d’organisation](https://helpx.adobe.com/fr/enterprise/using/admin-console.html). Une fois le processus de déploiement automatique terminé, la fiche produit dʼ[!DNL AEM Assets Essentials] est visible dans [!DNL Admin Console].

![Déploiement d’Assets Essentials](assets/admin-console-cards.png)

## Gérer les tâches d’Admin Console {#manage-admin-console-tasks}

Effectuez les tâches suivantes dans Admin Console :

* [Ajoutez des utilisateurs aux profils de produits.](#add-users-to-product-profiles)

* [Ajouter des groupes d’utilisateurs](#add-user-groups)

* [Ajouter des utilisateurs aux groupes](#add-users-to-user-groups)

### Ajoutez des utilisateurs aux profils de produits. {#add-users-to-product-profiles}

Ajoutez des utilisateurs aux profils de produits afin qu’ils aient accès à l’application Assets Essentials.

Pour ajouter des utilisateurs à des profils de produits :

1. Accédez à [Admin Console](https://adminconsole.adobe.com) de votre organisation, cliquez sur **[!UICONTROL Produits]** dans la barre supérieure, puis sur **[!UICONTROL AEM Assets Essentials]**, et enfin sur l’instance de [!DNL Assets Essentials]. Le nom de l’instance peut être différent de celui de la capture d’écran ci-dessous.
   >[!NOTE]
   >
   >L’instance de [!DNL Cloud Manager] est réservée à un usage administratif spécial, comme la vérification de l’état des services et l’accès aux journaux des services. Elle ne peut pas être utilisée pour ajouter des utilisateurs au produit. Pour plus d’informations, voir le [guide d’administration](deploy-administer.md#view-service-status-and-access-logs-view-logs).

   ![Profil administrateur Admin Console](assets/assets-essentials-instance.png)

   [!DNL Assets Essentials] possède trois profils de produits qui représentent l’accès pour les administrateurs, les utilisateurs réguliers et les consommateurs.

   ![Profil administrateur Admin Console](assets/admin-console-admin-profile.png)

1. Pour ajouter un utilisateur au produit, cliquez sur l’un des trois profils de produit Assets Essentials, sélectionnez **[!UICONTROL Ajouter un utilisateur]**, fournissez les détails de l’utilisateur et cliquez sur **[!UICONTROL Enregistrer]**.

   ![Ajouter le profil administrateur des utilisateurs](assets/add-users-admin-profile.png)

   Lorsque vous ajoutez un utilisateur, celui-ci reçoit une invitation par courrier électronique qui lui permet de commencer à l’utilisateur. Vous pouvez désactiver les invitations par e-mail dans les paramètres du profil de produit dans l’[!DNL Admin Console].

1. Pour supprimer un utilisateur d’un groupe, cliquez sur le groupe, sélectionnez un utilisateur existant, puis **[!UICONTROL Supprimer l’utilisateur]**.

   >[!NOTE]
   >
   >Vous devez ajouter un utilisateur au profil Administrateur du produit Assets Essentials dans Admin Console, afin qu’il puisse effectuer des tâches administratives dans l’application Assets Essentials. Ces tâches comprennent : [Créer une structure de dossiers](#create-folder-structure), [Gérer les autorisations pour les dossiers](#manage-permissions-for-folders) et [Configurer des formulaires de métadonnées](#metadata-forms).

### Ajouter des groupes d’utilisateurs {#add-user-groups}

Créez des groupes d’utilisateurs, puis affectez vos utilisateurs à ces groupes. Ces groupes d’utilisateurs seront disponibles dans l’application Assets Essentials pour définir les autorisations des dossiers.

Vous pouvez ajouter des utilisateurs aux groupes d’utilisateurs (1) et [aux profils de produits Assets Essentials (2)](#add-admin-users). Cependant, vous ne pouvez pas ajouter directement des groupes d’utilisateurs aux profils de produit Assets Essentials (3).

![Ajouter des utilisateurs aux groupes et aux profils de produits](assets/user-groups-product-profiles.svg)

Pour plus d’informations sur la gestion des groupes d’utilisateurs, consultez les sections `Create user groups` et `Edit user groups` sur la page [Gérer les groupes d’utilisateurs](https://helpx.adobe.com/fr/enterprise/using/user-groups.html).

>[!NOTE]
>
>Si Admin Console est configuré pour faire appel à un système de gestion externe des affectations des utilisateurs/groupes, tel que les connecteurs Azure ou Google, l’outil de synchronisation des utilisateurs ou l’API REST User Management, vos affectations de groupes et d’utilisateurs sont configurées automatiquement. Pour plus d’informations, consultez la section [Utilisateurs Adobe Admin Console](https://helpx.adobe.com/fr/enterprise/using/users.html).


### Ajouter des utilisateurs aux groupes {#add-users-to-user-groups}

Une fois que vous avez créé des groupes d’utilisateurs, vous pouvez commencer à y ajouter des utilisateurs.

Pour plus d’informations sur la gestion de l’ajout d’utilisateurs aux groupes d’utilisateurs, consultez la section `Add users to groups` de la page [Gérer les groupes d’utilisateurs](https://helpx.adobe.com/fr/enterprise/using/user-groups.html#add-users-to-groups).

## Gérer les tâches d’administration d’Assets Essentials {#manage-assets-essentials-tasks}

Après avoir effectué les tâches d’Admin Console, vous pouvez maintenant effectuer les tâches d’administration suivantes dans l’application Assets Essentials :

* [Créer une structure de dossiers](#create-folder-structure)

* [Gérer les autorisations des dossiers](#manage-permissions-for-folders)

* [Configurer les formulaires de métadonnées](#metadata-forms)

>[!NOTE]
>
>Pour être en mesure de gérer ces tâches, notamment la gestion des autorisations, votre utilisateur doit avoir des droits d’administration de l’application. Il doit être ajouté au [profil de produit Administrateur Assets Essentials](#add-users-to-product-profiles).


### Créer une structure de dossiers {#create-folder-structure}

Pour créer une structure de dossiers dans le référentiel Assets Essentials, utilisez les méthodes suivantes :

* Cliquez sur lʼoption **[!UICONTROL Créer un dossier]** disponible dans la barre d’outils pour créer un dossier vide.

* Cliquez sur lʼoption **[!UICONTROL Ajouter des ressources]** disponible dans la barre d’outils pour [télécharger une structure de dossiers présente sur votre ordinateur local](add-delete.md).

Créez une structure de dossiers qui correspond aux objectifs commerciaux de lʼorganisation. Si vous téléchargez une structure de dossiers existante vers le référentiel Assets Essentials, vous devez vérifier la structure. Pour plus d’informations, consultez la section [Bonnes pratiques relatives à la gestion efficace des autorisations](permission-management-best-practices.md).

Tenez compte des points suivants lorsque vous commencez à planifier la création d’une structure de dossiers dans le référentiel Assets Essentials :

* Gouvernance future : les dossiers qui sont régis par les administrateurs et les dossiers dont les [autorisations sont délégués à d’autres utilisateurs en tant que propriétaires](manage-permissions.md##manage-permissions-folders).

* Évolutive : la structure des dossiers doit répondre aux besoins futurs de votre entreprise et doit être facilement évolutive.

* Taille : un dossier ne doit pas contenir trop de ressources. Cela pourrait entraîner des problèmes d’utilisation et devenir difficile à gérer.

* Intuitive : la structure du dossier doit être facile à parcourir et intuitive pour les utilisateurs finaux. Les utilisateurs doivent être en mesure d’identifier facilement où charger une nouvelle ressource dans la structure de dossiers.

Il existe plusieurs types de structure de dossiers que vous pouvez utiliser pour votre organisation. Voici quelques exemples de structures de dossiers typiques :

![Structures de dossiers standard](assets/folder-structure.svg)

### Gérer les autorisations des dossiers {#manage-permissions-for-folders}

Grâce à Assets Essentials, les administrateurs peuvent gérer les niveaux d’accès aux dossiers disponibles dans le référentiel. En tant qu’administrateur, vous pouvez créer des groupes d’utilisateurs et leur attribuer des autorisations afin de gérer les niveaux d’accès. Vous pouvez également déléguer les privilèges de gestion des autorisations aux groupes d’utilisateurs au niveau du dossier.

>[!VIDEO](https://video.tv.adobe.com/v/341104)

Pour plus d’informations, voir [Gérer les autorisations pour les dossiers](manage-permissions.md).

### Configurer les formulaires de métadonnées {#metadata-forms}

Assets Essentials fournit par défaut de nombreux champs de métadonnées standard. Les entreprises ont d’autres besoins en métadonnées et ont besoin de davantage de champs de métadonnées pour ajouter des métadonnées spécifiques à leur entreprise. Les formulaires de métadonnées permettent aux entreprises d’ajouter des champs de métadonnées personnalisés à la page [!UICONTROL Détails] d’une ressource. Les métadonnées spécifiques à l’entreprise améliorent la gouvernance et la découverte de ses ressources. Vous pouvez créer des formulaires entièrement ou réutiliser un formulaire existant.

Vous pouvez configurer des formulaires de métadonnées pour différents types de ressources (différents types MIME). Utilisez le même nom de formulaire que le type MIME du fichier. Essentials fait automatiquement correspondre le type MIME des ressources chargées au nom du formulaire et met à jour les métadonnées des ressources chargées en fonction des champs du formulaire.

Par exemple, s’il existe un formulaire de métadonnées portant le nom `PDF` ou `pdf`, les documents PDF chargés contiennent les champs de métadonnées définis dans le formulaire.

Assets Essentials utilise la séquence suivante pour rechercher des noms de formulaires de métadonnées existants afin d’appliquer les champs de métadonnées aux ressources chargées d’un type particulier :

Formulaire de sous-type MIME > Type MIME > `default` > Formulaire prêt à l’emploi

Par exemple, si un formulaire de métadonnées portant le nom `PDF` ou `pdf` existe, les documents PDF chargés contiennent des champs de métadonnées tels que définis dans le formulaire. Si un formulaire de métadonnées du nom de `PDF` ou `pdf` n’existe pas, Assets Essentials vérifie s’il existe un formulaire de métadonnées du nom de `application`. S’il existe un formulaire de métadonnées du nom de `application`, les documents PDF chargés contiennent les champs de métadonnées définis dans le formulaire. Si Assets Essentials ne trouve toujours pas de formulaire de métadonnées correspondant, il recherche le formulaire de métadonnées `default` pour appliquer les champs de métadonnées définis dans le formulaire aux documents PDF chargés. Si aucune de ces étapes ne fonctionne, Assets Essentials applique les champs de métadonnées définis dans le formulaire prêt à l’emploi à tous les documents PDF chargés.

>[!IMPORTANT]
>
>Le nouveau formulaire de métadonnées pour un type de fichier spécifique remplace complètement le formulaire de métadonnées par défaut fourni par [!DNL Assets Essentials]. Si vous supprimez ou renommez un formulaire de métadonnées, les champs de métadonnées par défaut sont à nouveau disponibles pour les nouvelles ressources.

>[!VIDEO](https://video.tv.adobe.com/v/341275)

Pour plus d’informations sur le formulaires de métadonnées, voir [Formulaires de métadonnées dans Assets Essentials](metadata.md#metadata-forms).

## Prochaines étapes

Maintenant que vous avez configuré et géré l’application Assets Essentials, [intégrez les applications Creative Cloud à l’application Experience Manager Assets Essentials](integrate-assets-essentials-creative-cloud.md).
