---
title: Notes de mise à jour
description: Notes de mise à jour et problèmes connus d’ [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: ht
source-wordcount: '303'
ht-degree: 100%

---

# Notes de mise à jour d’[!DNL Assets Essentials] {#release-notes}

La version actuelle d’[!DNL Assets Essentials] est sortie le 30 août 2021. Elle fournit des intégrations avec [!DNL Adobe Workfront] qui permettent aux utilisateurs [!DNL Workfront] de gérer leurs ressources numériques dans le cadre de la gestion de leur travail. Pour plus d’informations, voir [Intégrations avec d’autres solutions Adobe](/help/integration.md).

Pour en savoir plus sur la solution, consultez la [Présentation d’ [!DNL Assets Essentials]](introduction.md). Pour commencer à utiliser les différentes fonctionnalités disponibles, consultez la [Prise en main](/help/get-started.md).

## Problèmes connus {#known-issues}

La liste des problèmes connus de l’offre [!DNL Assets Essentials] est révisée et mise à jour régulièrement :

* Pour charger un ou plusieurs dossiers, lorsque vous faites glisser les éléments dans un dossier contenant des sous-dossiers dans le référentiel, le chargement se fait automatiquement dans l’un des sous-dossiers. La solution consiste à cliquer sur l’option [!DNL Upload assets] et à faire glisser le composant dans la boîte de dialogue. <!-- CQ-4327753 -->
* Après le chargement d’un dossier, les nouveaux dossiers peuvent parfois s’afficher incorrectement dans le rail de gauche au lieu de s’afficher dans l’arborescence. Pour corriger ce problème, actualisez le navigateur. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

Si vous rencontrez des problèmes ou même si vous avez des demandes d’amélioration, [communiquez vos requêtes](#provide-feedback) à l’équipe.

## Versions antérieures {#past-release}

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
