---
title: Notes de mise à jour
description: Notes de mise à jour et problèmes connus d’ [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 2b1b6d3503f8c96ac250d4b0ff7dd5b7c2b81d64
workflow-type: tm+mt
source-wordcount: '1269'
ht-degree: 87%

---

# Notes de mise à jour d’[!DNL Assets Essentials] {#release-notes}

La version actuelle d’Assets Essentials est publiée le 22 août 2022.

Cette version fournit les éléments suivants :

**Notifications pour les collections**

Les notifications Assets Essentials vous permettent désormais de surveiller les opérations effectuées sur les collections disponibles dans le référentiel. Vous devez sélectionner et vous abonner aux collections pour lesquelles les notifications vous sont envoyées. Vous pouvez également configurer les opérations pour lesquelles les notifications sont envoyées, telles que la suppression, le partage de lien, le déplacement, le changement de nom et la mise à jour des opérations effectuées sur les collections.

**Modification des collections dynamiques**

Assets Essentials permet désormais également de modifier les critères de recherche utilisés lors de la création d’une collection dynamique.  Enregistrez les nouveaux critères de recherche pour mettre à jour dynamiquement le contenu de la collection.

<!--

**View live statistics for storage account**

Assets Essentials now also enables you to view real-time storage account data for your Assets Essentials environment with the Live Statistics dashboard. You can view real-time event metrics for the last 30 days or for the last 12 months.

-->

**Affichage des rapports de chargement**

Les rapports de ressources offrent désormais aux administrateurs une visibilité sur les ressources chargées dans le déploiement Adobe Experience Manager Assets Essentials. Les administrateurs ont déjà la possibilité de générer des rapports pour les ressources téléchargées à partir du déploiement Assets Essentials. Ces données fournissent des informations utiles sur la façon dont les utilisateurs interagissent avec le contenu et le produit.

**Améliorations basées sur les commentaires des clients**

Améliorations et correctifs de bugs basés sur les commentaires des clients.


## Problèmes connus {#known-issues}

La liste des problèmes connus de l’offre [!DNL Assets Essentials] est révisée et mise à jour régulièrement :

<!--

* Assets Essentials does not support creating Private collections.

-->


* Les collections privées sont disponibles pour les créateurs et les utilisateurs disposant de droits d’administrateur. En tant qu’administrateur, vous ne pouvez pas déléguer les autorisations d’accès à la collection à d’autres utilisateurs.

Si vous rencontrez des problèmes ou même si vous avez des demandes d’amélioration, [communiquez vos requêtes](#provide-feedback) à l’équipe.

## Versions antérieures {#past-release}

### 2022.6.0 {#june-2022}

La version de juin de [!DNL Assets Essentials] est publié le 14 juillet 2022.

Cette version fournit les éléments suivants :

**Collections dynamiques**

Enregistrez les résultats de recherche en tant que collecte dynamique pour mettre à jour dynamiquement le contenu de la collection. Si des ressources sont ajoutées au référentiel Assets Essentials et celles-ci correspondent aux critères de recherche définis lors de la [création de la collecte dynamique](manage-collections.md#create-smart-collection), le contenu de la collecte dynamique sera automatiquement mis à jour.

**Notifications**

Les notifications d’Assets Essentials vous permettent de [surveiller les opérations effectuées sur les ressources ou dossiers disponibles dans le référentiel](manage-notifications.md). Pour recevoir les notifications, vous devez sélectionner le contenu et vous y abonner. Vous pouvez également configurer les catégories pour lesquelles les notifications vous sont envoyées.

**Création de rapports**

Les rapports de ressources permettent aux administrateurs d’évaluer l’activité des utilisateurs dans Adobe Experience Manager Assets Essentials. Les rapports et les statistiques dynamiques fournissent des informations utiles sur la façon dont les utilisateurs interagissent avec les ressources disponibles dans votre déploiement. [Utilisez les informations figurant dans les rapports](manage-reports.md) de manière à obtenir des mesures de succès essentielles pour évaluer l’adoption d’Assets au sein de votre entreprise et par les clients.

Consultez les rapports sur les téléchargements de ressources et le module de tableau de bord des statistiques dynamiques pour déterminer quelles ressources sont téléchargées ainsi que la fréquence des téléchargements.

### 2022.5.0 {#may-2022}

La version de mai de [!DNL Assets Essentials] est publié le 16 juin 2022.

Cette version fournit les éléments suivants :

**Améliorations du statut des ressources**

* Assets Essentials vous permet désormais de [définir une date d’expiration pour une ressource](manage-organize.md#set-asset-status). En outre, vous pouvez [filtrer les ressources](search.md#refine-search-results) en fonction du statut de la ressource `Expired` et de la période d’expiration.

* Vous pouvez désormais afficher l’indicateur de statut de toutes les ressources disponibles dans la corbeille. Par conséquent, vous pouvez prendre une décision pour restaurer une ressource en fonction de son statut.

**Améliorations des filtres de recherche**

* Assets Essentials vous permet désormais de [filtrer les ressources](search.md#refine-search-results) en utilisant le statut de la ressource `No Status`.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**Améliorations des collections**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials prend désormais en charge le [téléchargement d’une collection](manage-collections.md).

* Vous pouvez désormais modifier le champ de métadonnées Description d’une collection.

**Améliorations de la documentation**

* Une nouvelle version de la fonction [Documentation de présentation d’Assets Essentials](introduction.md) est désormais disponible.

**Améliorations basées sur les commentaires des clients**

* Améliorations et correctifs de bugs basés sur les commentaires des clients.

### 2022.4.0 {#april-2022}

La version actuelle d’[!DNL Assets Essentials] est sortie le 12 mai 2022. Cette version fournit les éléments suivants :

* [!DNL Assets Essentials] prend désormais en charge la [création de collections](manage-collections.md). Une collection est un ensemble de ressources dans Experience Manager Assets Essentials. Vous pouvez utiliser des collections pour partager des ressources entre utilisateurs. Contrairement aux dossiers, une collection peut comporter des ressources provenant de différents emplacements.

* Assets Essentials vous permet désormais de [rajouter des filtres personnalisés](search.md#custom-filters) à l’interface utilisateur. Vous pouvez ensuite appliquer ces filtres personnalisés en plus des filtres standard pour affiner les résultats de la recherche.

* Assets Essentials vous permet désormais de [définir le statut](manage-organize.md#set-asset-status) des ressources disponibles dans le référentiel. Définissez le statut d’une ressource pour mieux gouverner et gérer la consommation en aval des ressources numériques.

* Améliorations et correctifs de bugs basés sur les commentaires des clients.

#### Mode Incognito dans Chrome {#incognito-mode}

Avec cette version, nous optimisons les performances de diffusion de l’interface utilisateur et des fonctionnalités spécifiques d’Assets Essentials (les commentaires sur les ressources et la modification d’images). Dépend de l’activation de l’espace de stockage local du navigateur et des cookies tiers. Le mode incognito dans le navigateur web Chrome bloque par défaut les cookies tiers. Les utilisateurs disposent de plusieurs options pour continuer à accéder à toutes les fonctionnalités :

* Utilisez des profils Chrome au lieu du mode Incognito lorsque l’utilisateur doit séparer les sessions de navigateur.

* Désactivez la fonction `Block third-party cookies` dans l’écran Mode Incognito dans Chrome.

### 2022.2.0 {#march-2022}

d’[!DNL Assets Essentials] est sortie le 9 mars 2022, avec les mises à jour suivantes :

* [!DNL Assets Essentials] vous permet désormais de [générer un lien et partager des ressources avec des parties prenantes externes](share-links-for-assets.md) qui n’ont pas accès à l’application [!DNL Assets Essentials]. Vous pouvez définir une date d’expiration pour le lien, puis le partager avec d’autres utilisateurs en utilisant votre méthode de communication préférée, comme les e-mails ou les services de messagerie. Les destinataires du lien peuvent prévisualiser les ressources et les télécharger.

* [!DNL Assets Essentials] comprend maintenant [un profil produit administrateur](deploy-administer.md#add-users-to-essentials) sur l’Admin Console en plus des profils de produits standard et consommateurs existants. Un administrateur peut désormais affecter d’autres utilisateurs au profil de produit administrateur.

* Assets Essentials permet désormais aux administrateurs de [gérer les niveaux d’accès des dossiers disponibles dans le référentiel](manage-permissions.md). En tant qu’administrateur, vous pouvez créer des groupes d’utilisateurs et leur attribuer des autorisations afin de gérer les niveaux d’accès. Vous pouvez également déléguer les privilèges de gestion des autorisations aux groupes d’utilisateurs au niveau du dossier.

* Améliorations et correctifs de bugs basés sur les commentaires des clients.

En outre, l’extension d’[!DNL Adobe Asset Link] pour Creative Cloud (Photoshop, Illustrator et InDesign) a publié une [nouvelle version 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) avec des performances améliorées au niveau de l’heure de démarrage du panneau et de la vitesse de téléchargement.


### Version 2022.1.0 {#january-2022}

[!DNL Assets Essentials] est sorti le 3 février 2022, avec les mises à jour suivantes :

* Améliorations des performances de l’opération [!UICONTROL Créer un dossier]. <!-- CQ-4338818 -->

### Version 2021.11.0 {#november-2021}

[!DNL Assets Essentials] est sortie le 16 décembre 2021, avec les mises à jour suivantes :

* Adobe déploie automatiquement Assets Essentials à la fin du processus dʼapprovisionnement. Aucune action supplémentaire ne doit être effectuée par les administrateurs dans le cadre du déploiement dʼAssets Essentials par le biais de lʼinterface utilisateur [!DNL Cloud Manager]. Ce déploiement automatique sera disponible pour les environnements approvisionnés après la date du 6 janvier 2022.
* De nouvelles versions de plugins pour Creative Cloud fonctionnant avec Assets Essentials sont disponibles sur Adobe Exchange : [Adobe Asset Link pour Adobe XD version 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) et [Adobe Asset Link pour Photoshop/InDesign/Illustrator version 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Divers correctifs de bugs et améliorations de produits, concernant notamment les problèmes connus précédents (les dossiers s’affichent désormais correctement dans l’arborescence de navigation de gauche après le téléchargement<!-- CQ-4337638 -->, le transfert par glisser-déposer permet à l’utilisateur de sélectionner le dossier actif ou un autre sous-dossier lors du dépôt pour le transfert.<!-- CQ-4327753 -->).

### Version 2021.8.0 {#august2021}

La version 2021.8.0 d’[!DNL Assets Essentials] est sortie le 30 août 2021 et comprend les mises à jour suivantes :

* Intégrations à [!DNL Adobe Workfront] qui permettent aux utilisateurs de [!DNL Workfront] de gérer leurs ressources numériques dans le cadre de la gestion de leur travail. Pour plus d’informations, voir [Intégrations avec d’autres solutions Adobe](/help/integration.md).

### Version 2021.7.0 {#july2021}

La version 2021.7.0 d’[!DNL Assets Essentials] est sortie le 29 juillet 2021, avec les mises à jour suivantes :

* Vous pouvez créer et gérer des formulaires de métadonnées personnalisés à utiliser pour afficher les propriétés de métadonnées aux utilisateurs dans l’écran des détails de la ressource dans l’option [!UICONTROL Formulaires de métadonnées] sous [!DNL Settings]. Voir [Formulaires de métadonnées](metadata.md#metadata-forms).
* Divers correctifs de bogues et améliorations de produit, notamment de meilleures performances lors du chargement d’un dossier imbriqué avec de nombreux sous-dossiers.

### Version 2021.6.0 {#june2021}

La première version d’[!DNL Assets Essentials], sortie le 21 juin 2021, offre des fonctionnalités légères de gestion de ressources. Il prend en charge les principales fonctionnalités suivantes et les opérations CRUD (création, lecture, mise à jour et suppression) :

* Chargement et ajout de ressources, y compris des dossiers imbriqués. Aperçu des ressources et des versions.
* Recherche en plein texte, filtres de recherche nuancés et enregistrement des paramètres de recherche pour découvrir rapidement de ressources.
* Opérations de gestion des ressources de base telles que la mise à jour, la suppression, le téléchargement et la gestion des métadonnées.
* [!DNL Assets Essentials] permet aux utilisateurs d’[!DNL Adobe Journey Optimizer] de gérer les ressources lors de la création de messages. Pour plus d’informations, voir [Intégrations avec d’autres solutions Adobe](/help/integration.md).
