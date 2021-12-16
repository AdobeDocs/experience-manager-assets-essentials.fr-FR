---
title: Notes de mise à jour
description: Notes de mise à jour et problèmes connus d’ [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 0c849c92562f9102819aaea627f5945030b27a1e
workflow-type: tm+mt
source-wordcount: '382'
ht-degree: 55%

---

# Notes de mise à jour d’[!DNL Assets Essentials] {#release-notes}

La version actuelle de [!DNL Assets Essentials] est publié le 16 décembre 2021. Avec cette version :

* Adobe déploie automatiquement Assets Essentials après avoir terminé le processus de configuration. Les administrateurs n’ont pas besoin d’effectuer des étapes supplémentaires pour déployer Assets Essentials à l’aide de [!DNL Cloud Manager] de l’interface utilisateur. Ce déploiement automatique sera disponible pour les environnements configurés après le 6 janvier 2022.
* De nouvelles versions des modules externes de Creative Cloud utilisant Assets Essentials sont disponibles sur Adobe Exchange - [Adobe Asset Link pour Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) et [Adobe Asset Link pour Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Divers correctifs de bogues et améliorations de produits, notamment les problèmes connus précédents (les dossiers s’affichent désormais correctement dans l’arborescence de navigation de gauche après le chargement).<!-- CQ-4337638 -->, le transfert par glisser-déposer permet à l’utilisateur de sélectionner le dossier actif ou tout sous-dossier lors du dépôt pour le transfert.<!-- CQ-4327753 -->).

Pour en savoir plus sur la solution, consultez la [Présentation d’ [!DNL Assets Essentials]](introduction.md). Pour commencer à utiliser les différentes fonctionnalités disponibles, consultez la [Prise en main](/help/get-started.md).

## Problèmes connus {#known-issues}

La liste des problèmes connus de l’offre [!DNL Assets Essentials] est révisée et mise à jour régulièrement :

* Les ressources individuelles ne peuvent pas être chargées dans le dossier supérieur (Ressources), mais uniquement dans n’importe quel sous-dossier du système. <!-- CQ-4337638 -->

Si vous rencontrez des problèmes ou même si vous avez des demandes d’amélioration, [communiquez vos requêtes](#provide-feedback) à l’équipe.

## Versions antérieures {#past-release}

### Version 2021.8.0 {#august2021}

[!DNL Assets Essentials] La version 2021.8.0 est publiée le 30 août 2021, avec les mises à jour suivantes :

* Intégrations avec [!DNL Adobe Workfront] qui laisse [!DNL Workfront] les utilisateurs gèrent leurs ressources numériques dans le cadre de la gestion de leur travail. Pour plus d’informations, voir [Intégrations avec d’autres solutions Adobe](/help/integration.md).

### Version 2021.7.0 {#july2021}

La version 2021.7.0 d’[!DNL Assets Essentials] est sortie le 29 juillet 2021, avec les mises à jour suivantes :

* Vous pouvez créer et gérer des formulaires de métadonnées personnalisés à utiliser pour afficher les propriétés de métadonnées aux utilisateurs dans l’écran des détails de la ressource dans l’option [!UICONTROL Formulaires de métadonnées] sous [!DNL Settings]. Voir [Formulaires de métadonnées](metadata.md#metadata-forms).
* Divers correctifs de bogues et améliorations de produit, notamment de meilleures performances lors du chargement d’un dossier imbriqué avec de nombreux sous-dossiers.

### Version 2021.6.0 {#june2021}

La première version d’[!DNL Assets Essentials], sortie le 21 juin 2021, offre des fonctionnalités légères de gestion de ressources. Il prend en charge les principales fonctionnalités suivantes et les opérations CRUD (création, lecture, mise à jour et suppression) :

* Chargement et ajout de ressources, y compris des dossiers imbriqués Aperçu des ressources et des versions
* Recherche en plein texte, filtres de recherche nuancés et enregistrement des paramètres de recherche pour découvrir rapidement de ressources
* Opérations de gestion des ressources de base telles que la mise à jour, la suppression, le téléchargement et la gestion des métadonnées
* [!DNL Assets Essentials] permet aux utilisateurs d’[!DNL Adobe Journey Optimizer] de gérer les ressources lors de la création de messages. Pour plus d’informations, voir [Intégrations avec d’autres solutions Adobe](/help/integration.md).
