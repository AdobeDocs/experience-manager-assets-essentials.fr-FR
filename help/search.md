---
title: Rechercher et trouver des ressources dans [!DNL Assets Essentials]
description: Recherchez et trouvez des ressources dans [!DNL Assets Essentials].
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: cfe72bb73493c84dc57a0438817e3868d8a1ed14
workflow-type: ht
source-wordcount: '802'
ht-degree: 100%

---

# Recherche de ressources dans [!DNL Assets Essentials] {#search-assets}

[!DNL Assets Essentials] offre des fonctionnalités de recherche efficaces, qui fonctionnent simplement par défaut. La recherche fonctionne de façon exhaustive car il s’agit d’une recherche de type plein texte. Ses puissantes fonctionnalités de recherche vous permettent de trouver rapidement la ressource appropriée et d’améliorer la vitesse de votre contenu. [!DNL Assets Essentials] fournit une recherche plein texte, ou même des capacités de recherche basées sur les métadonnées telles que les balises intelligentes, le titre, la date de création et le copyright.

Pour rechercher des ressources,

* Cliquez dans la zone de recherche située en haut de la page. Par défaut, la recherche s’effectue dans le dossier que vous êtes en train de parcourir. Utilisez l’une des méthodes suivantes :

   ![Zone de recherche](assets/search-box.png)

   * Effectuez une recherche à l’aide d’un mot-clé ou vous pouvez changer de dossier. Appuyez sur Entrée.

   * Commencez à travailler avec une ressource récemment consultée en la recherchant directement. Cliquez dans la zone de recherche et sélectionnez une ressource récemment consultée parmi les suggestions.

## Filtrer les résultats de la recherche {#refine-search-results}

Vous pouvez filtrer les résultats de la recherche en fonction des paramètres suivants.

![Filtres de recherche](assets/filters1.png)

*Image : filtrage des ressources recherchées en fonction de divers paramètres.*

* Statut de la ressource : filtrez les résultats de recherche à l’aide de `Approved`, `Rejected` ou d’un statut de ressource `No Status`.

* Type de fichier : filtrez les résultats de la recherche selon les types de fichiers pris en charge, à savoir `Images`, `Documents` et `Videos`.
* Type MIME : filtrez un ou plusieurs formats de fichiers pris en charge. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* Taille de l’image : fournissez une ou plusieurs dimensions minimales et maximales pour filtrer les images. Les dimensions sont fournies en pixels et ne correspondent pas à la taille de fichier des images.
* Date de création : date de création de la ressource telle qu’elle figure dans les métadonnées. Le format de date standard utilisé est `yyyy-mm-dd`.
* Date de modification : date de dernière modification des ressources. Le format de date standard utilisé est `yyyy-mm-dd`.

* Date d’expiration : filtrez les résultats de la recherche en fonction du statut d’une ressource `Expired`. En outre, vous pouvez spécifier une période d’expiration pour les ressources afin de filtrer davantage les résultats de votre recherche.

* Filtres personnalisés : [ajoutez des filtres personnalisés](#custom-filters) à l’interface utilisateur d’Assets Essentials. Appliquez ces filtres personnalisés en plus des filtres standard pour affiner les résultats de la recherche.

Vous pouvez trier les ressources recherchées par ordre croissant ou décroissant de `Name`, `Relevancy`, `Size`, `Modified` et `Created`.

## Gestion des filtres personnalisés {#custom-filters}

**Autorisations requises :**  `Can Edit`, `Owner` ou administrateur.

Assets Essentials vous permet également d’ajouter des filtres personnalisés à l’interface utilisateur. Vous pouvez ensuite appliquer ces filtres personnalisés en plus des [filtres standard](#refine-search-results) pour affiner vos résultats de recherche.

Assets Essentials fournit les filtres personnalisés suivants :

<table>
    <tbody>
     <tr>
      <th><strong>Nom de filtre personnalisé</strong></th>
      <th><strong>Description</strong></th>
     </tr>
     <tr>
      <td>Titre</td>
      <td>Filtrage des ressources à l’aide du titre de la ressource. Le titre que vous indiquez dans les critères de recherche sensibles à la casse doit correspondre au titre exact de la ressource à afficher dans les résultats.</td>
     </tr>
     <tr>
      <td>Nom</td>
      <td>Filtrez les ressources à l’aide du nom de fichier de la ressource. Le nom que vous indiquez dans les critères de recherche sensibles à la casse doit correspondre au nom de fichier exact de la ressource à afficher dans les résultats.</td>
     </tr>
     <tr>
      <td>Taille de ressource</td>
      <td>Filtrez les ressources en définissant une plage de taille de fichier, en octets, dans les critères de recherche pour afficher une ressource dans les résultats.</td>
     </tr>
     <tr>
      <td>Balises prédites</td>
      <td>Filtrage des ressources à l’aide de la balise dynamique de ressource. Le nom de balise dynamique que vous indiquez dans les critères de recherche sensibles à la casse doit correspondre exactement au nom de balise dynamique de la ressource à afficher dans les résultats. Vous ne pouvez pas spécifier plusieurs balises dynamiques dans les critères de recherche.</td>
     </tr>    
    </tbody>
   </table>

<!--
   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. For example, if you define <b>ma*</b> as the search criteria, Assets Essentials displays assets with title, such as, market, marketing, man, manchester, and so on in the results.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. You can specify multiple smart tags separated by a comma in the search criteria.

   -->

### Ajout de filtres personnalisés {#add-custom-filters}

Pour ajouter des filtres personnalisés :

1. Cliquez sur **[!UICONTROL Filtres]**.

1. Dans la section **[!UICONTROL Filtres personnalisés]**, cliquez sur **[!UICONTROL Modifier]** ou **[!UICONTROL Ajouter des filtres]**.

   ![Ajout de filtres personnalisés](assets/add-custom-filters.png)

1. Dans la boîte de dialogue **[!UICONTROL Gestion des filtres personnalisés]**, sélectionnez les filtres à ajouter à la liste de filtres existants. Sélectionnez **[!UICONTROL Filtres personnalisés]** pour sélectionner tous les filtres.

1. Cliquez sur **[!UICONTROL Confirmer]** pour ajouter les filtres à l’interface utilisateur.

### Suppression de filtres personnalisés {#remove-custom-filters}

Pour supprimer des filtres personnalisés :

1. Cliquez sur **[!UICONTROL Filtres]**.

1. Dans la section **[!UICONTROL Filtres personnalisés]**, cliquez sur **[!UICONTROL Modifier]**.

1. Sans la boîte de dialogue **[!UICONTROL Gestion des filtres personnalisés]**, désélectionnez les filtres que vous devez supprimer de la liste des filtres existants.

1. Cliquez sur **[!UICONTROL Confirmer]** pour supprimer les filtres de l’interface utilisateur.


## Recherches enregistrées {#saved-search}

La fonctionnalité de recherche est assez facile à utiliser dans [!DNL Assets Essentials]. Dans la zone de recherche, vous pouvez non seulement saisir un mot-clé et appuyer sur Entrée pour afficher les résultats, mais vous pouvez également rechercher rapidement vos mots-clés recherchés récemment en un seul clic.

Vous pouvez également filtrer les résultats de la recherche en fonction de critères spécifiques relatifs aux métadonnées et au type de ressources. Pour les filtres fréquemment utilisés, [!DNL Assets Essentials] permet d’enregistrer les paramètres de recherche afin d’améliorer l’expérience de recherche. Vous pouvez ensuite sélectionner la recherche enregistrée pour l’utiliser et appliquer le filtre, en un seul clic.

Pour créer une recherche enregistrée, recherchez une ressource, appliquez un ou plusieurs filtres, puis cliquez sur [!UICONTROL Enregistrer la recherche] dans le panneau [!UICONTROL Filtres].

![Recherche enregistrée dans le panneau Filtres](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->

## Étapes suivantes {#next-steps}

* [Regardez une vidéo pour rechercher des ressources dans Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/using.html?lang=fr).

* Faites des commentaires sur le produit en utilisant l’option [!UICONTROL Commentaires] disponible dans l’interface utilisateur d’Assets Essentials.

* Faites des commentaires sur la documentation en utilisant l’option [!UICONTROL Modifier cette page] ![modifier la page](assets/do-not-localize/edit-page.png) ou [!UICONTROL Enregistrer un problème] ![créer un problème GitHub](assets/do-not-localize/github-issue.png) disponible dans la barre latérale droite.

* Contactez l’[assistance clientèle](https://experienceleague.adobe.com/?support-solution=General&amp;lang=fr#support).
