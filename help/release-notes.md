---
title: Notes de mise à jour
description: Notes de mise à jour et problèmes connus d’ [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: fd95cf87ae8e5449471cd580405b228c32ede264
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 14%

---


# Notes de mise à jour d’[!DNL Assets Essentials] {#release-notes}

La version actuelle est la première version publique de [!DNL Assets Essentials] disponible le 21 juin 2021. [!DNL Assets Essentials] offre des fonctionnalités légères de gestion des ressources et sa première version prend en charge les principales fonctionnalités suivantes et les opérations CRUD (création, lecture, mise à jour et suppression) :

* Chargement et ajout de ressources, y compris des dossiers imbriqués Aperçu des ressources et versions.
* Recherche en plein texte, filtres de recherche nuancés et enregistrement des paramètres de recherche pour découvrir rapidement de ressources.
* Opérations de base de la gestion des ressources, telles que la mise à jour, la suppression, le téléchargement et la gestion des métadonnées.
* Intégration à [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=fr).

Actuellement, [!DNL Assets Essentials] est disponible pour les clients [[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html).

Pour en savoir plus sur la solution, consultez l’[introduction à [!DNL Assets Essentials]](introduction.md). Pour commencer à utiliser les fonctionnalités, voir [Prise en main](/help/get-started.md).

## Version actuelle {#release-notes-current}

La version actuelle d’Assets Essentials est la version 2021.7.0, publiée le 29 juillet 2021, avec les mises à jour suivantes :

* Vous pouvez créer et gérer des formulaires de métadonnées personnalisés à utiliser pour afficher les propriétés de métadonnées aux utilisateurs dans l’écran des détails de la ressource dans l’option [!UICONTROL Forms de métadonnées] sous [!DNL Settings].
* Divers correctifs de bogues et améliorations de produit, notamment de meilleures performances lors du téléchargement d’un dossier imbriqué avec de nombreux sous-dossiers.

## Problèmes connus {#known-issues}

La liste des problèmes connus de l’offre [!DNL Assets Essentials] est révisée et mise à jour régulièrement :

* Pour charger un ou plusieurs dossiers, lorsque vous faites glisser les éléments dans un dossier contenant des sous-dossiers dans le référentiel, le téléchargement se fait automatiquement dans l’un des sous-dossiers. La solution de contournement consiste à cliquer sur l’option [!DNL Upload assets] et à faire glisser le composant dans la boîte de dialogue. <!-- CQ-4327753 -->
* Après le chargement du dossier, les nouveaux dossiers peuvent parfois s’afficher incorrectement dans le rail de gauche au lieu de s’afficher dans l’arborescence. La solution consiste à actualiser le navigateur. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

Si vous rencontrez des problèmes ou même des demandes d’amélioration, [fournissez des commentaires](#provide-feedback) à l’équipe.
