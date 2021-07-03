---
title: Gestion des métadonnées
description: Gestion des métadonnées des ressources dans [!DNL Assets Essentials]
role: User,Leader,Administrator,Architect,Developer
contentOwner: AG
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '559'
ht-degree: 13%

---


# Métadonnées dans [!DNL Assets Essentials] {#metadata}

Les métadonnées sont des données ou une description des données. Par exemple, vos images en tant que ressource peuvent contenir des informations sur l’appareil photo sur lequel l’utilisateur a cliqué ou toute information relative aux droits d’auteur. Ces informations sont des métadonnées de l’image. Les métadonnées sont essentielles pour gérer efficacement des ressources. Les métadonnées sont la collection de toutes les données disponibles pour une ressource, mais elles ne sont pas nécessairement contenues dans cette ressource.

Les métadonnées vous aident à classer davantage les ressources et s’avèrent utiles à mesure que la quantité d’informations numériques augmente. Il est possible de gérer quelques centaines de fichiers uniquement en fonction des noms de fichier, des miniatures et de la mémoire. Pour autant, cette approche n’est pas évolutive. Elle est insuffisante lorsque le nombre de personnes impliquées et le nombre de ressources gérées augmentent.

Avec l’ajout de métadonnées, la valeur d’une ressource numérique augmente, car elle devient :

* plus accessible : les systèmes et les utilisateurs peuvent la trouver facilement ;
* plus facile à gérer : vous pouvez rechercher plus facilement des ressources avec un même ensemble de propriétés et leur apporter des modifications ;
* complète : la ressource contient davantage d’informations et de contexte grâce à un plus grand nombre de métadonnées.

Pour ces raisons, Assets vous fournit les moyens adéquats pour créer, gérer et échanger des métadonnées pour vos ressources numériques.

## Affichage des métadonnées {#view-metadata}

Pour afficher les métadonnées d’une ressource, accédez à la ressource ou recherchez-la, sélectionnez-la, puis cliquez sur **[!UICONTROL Détails]** dans la barre d’outils.

![Affichage des métadonnées d’une ressource](assets/metadata-view1.png)

*Figure : Pour afficher une ressource et ses métadonnées, cliquez sur ****Détails dans la barre d’outils ou double-cliquez sur la ressource.*

Les métadonnées de base telles que le titre, la description et la date de chargement sont disponibles dans l’onglet [!UICONTROL Basic] . L’onglet [!UICONTROL Avancé] contient des métadonnées plus avancées telles que le modèle d’appareil photo, les détails de la loupe et les balises géographiques. L’onglet [!UICONTROL Balises] contient des balises appliquées automatiquement en fonction du contenu de l’image.

## Mettre à jour les métadonnées {#update-metadata}

Vous pouvez mettre à jour quelques champs de métadonnées manuellement. Les champs comprennent [!UICONTROL Titre], [!UICONTROL Description], [!UICONTROL Auteur] et [!UICONTROL Mots-clés].

## Balises {#tags}

[!DNL Assets Essentials] utilise l’intelligence artificielle fournie par  [Adobe ](https://www.adobe.com/fr/sensei.html) Senseito pour appliquer automatiquement les balises pertinentes à toutes vos ressources chargées. Ces balises, bien nommées Balises intelligentes, augmentent la vitesse du contenu de vos projets en vous aidant à trouver rapidement les ressources appropriées. Les balises intelligentes sont un exemple de métadonnées qui ne sont pas contenues dans l’image.

Les balises intelligentes sont appliquées en temps quasi réel et sont générées en fonction du contenu de l’image. Lorsque vous chargez une ressource, l’interface utilisateur affiche [!UICONTROL Traitement] sur la miniature de la ressource pendant un certain temps. Une fois le traitement terminé, vous pouvez [afficher les métadonnées](#view-metadata) et les balises intelligentes.

![Affichage des balises intelligentes d’une ressource](assets/metadata-view-tags.png)

*Figure : Pour afficher les balises intelligentes d’une ressource, cliquez sur ****Détails dans la barre d’outils ou double-cliquez sur la ressource.*

Les balises intelligentes contiennent également un score de confiance en pourcentage. Elle indique le degré de confiance associé à la balise appliquée. Vous pouvez modérer les balises intelligentes appliquées automatiquement.

## Ajout ou mise à jour de balises {#manually-tag}

Vous pouvez ajouter d’autres balises à vos ressources, en plus des balises intelligentes qui sont ajoutées automatiquement à l’aide du service dynamique [!DNL Adobe Sensei] . Ouvrez une ressource à des fins d’aperçu, cliquez sur [!UICONTROL Balises], puis saisissez les mots-clés souhaités dans le champ [!UICONTROL Mots-clés]. Pour ajouter la balise, appuyez sur Entrée. [!DNL Assets Essentials] indexe le mot-clé en temps quasi réel et votre équipe peut bientôt rechercher les ressources mises à jour à l’aide des nouveaux mots-clés.

Vous pouvez également supprimer des balises de la section [!UICONTROL Balises intelligentes] qui sont automatiquement ajoutées par [!DNL Assets Essentials] à toutes les ressources chargées.

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
