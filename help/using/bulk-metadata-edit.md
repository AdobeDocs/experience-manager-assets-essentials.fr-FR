---
title: Modification des métadonnées en bloc dans Assets Essentials
description: Découvrez comment mettre à jour un ensemble prédéfini de champs de métadonnées standard pour plusieurs ressources disponibles simultanément sur Assets Essentials.
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
source-git-commit: 461773235cb2d27d334b5ceb23f959dc9a848716
workflow-type: tm+mt
source-wordcount: '508'
ht-degree: 4%

---


<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="nouveau">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime et Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="nouveau">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="nouveau">
            <a href="http://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>Intégration d’AEM Assets à Edge Delivery Services</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="nouveau">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>Extensibilité de l’interface utilisateur</b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="nouveau">
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-assets-essentials/help/custom-search-filters"><b>Filtres de recherche personnalisés</b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b>Bonnes pratiques de recherche</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b>Bonnes pratiques relatives aux métadonnées</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/fr/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b>Hub de contenus</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b>Fonctionnalités Dynamic Media avec OpenAPI</b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b>Documentation de développement pour AEM Assets</b></a>
        </td>
    </tr>
</table>

# Modification des métadonnées en bloc dans Assets Essentials{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

La fonctionnalité **Modification des métadonnées en bloc** d’Assets Essentials permet aux utilisateurs de modifier simultanément un ensemble prédéfini de champs de métadonnées standard pour plusieurs fichiers de ressources. Sélectionnez plusieurs ressources et mettez à jour en une fois leur ensemble prédéfini de métadonnées standard au lieu de mettre à jour individuellement ces métadonnées standard pour chaque ressource. Cette fonctionnalité améliore l’efficacité, la cohérence et la précision des propriétés de métadonnées standard sur un large ensemble de ressources, améliorant ainsi la capacité de recherche et l’organisation des ressources.

## Modification en masse des métadonnées de ressources {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

Exécutez les étapes suivantes pour modifier en bloc les métadonnées de plusieurs ressources à la fois :

1. Dans Assets Essentials, cliquez sur **Assets**.
1. Recherchez des ressources spécifiques ou recherchez-les à l’aide de mots-clés dans la barre de recherche.
1. Sélectionnez les ressources et cliquez sur **Modification des métadonnées en bloc** dans le menu supérieur.
   ![bulk-metadata-edit](/help/using/assets/bulk-metadata-edit1.png)
1. Sur la page Modifier les métadonnées , modifiez les champs suivants dans le panneau **Propriétés** :
   * **Statut :** sélectionnez un statut pour les ressources sélectionnées.
   * **Date d’expiration :** définissez une date après laquelle les ressources ne sont plus valides ou nécessaires.
   * **Auteur :** indiquez le nom de l’auteur.
   * **Mots-clés :** ajoutez des termes ou des chaînes de texte spécifiques qui fournissent des informations générales sur les ressources afin d’améliorer leur visibilité. Ajoutez un mot-clé et appuyez sur Entrée ou Retour pour ajouter un autre mot-clé à la liste.
   * **Balises :** cliquez sur ![icône des balises](/help/using/assets/tags-icon.svg) pour sélectionner des balises dans les options disponibles. Les balises fournissent des informations plus spécifiques sur les ressources et améliorent leur visibilité. Les balises déjà appliquées aux ressources sélectionnées s’affichent dans le panneau **Propriétés**. Si vous ne trouvez pas les balises appropriées, créez-les et affectez-les aux ressources sélectionnées. Voir [Gérer les balises dans Assets Essentials](/help/using/tagging-management.md) pour plus d’informations sur la création et l’affectation de balises à des ressources.
   * Cliquez sur **Enregistrer** pour appliquer les mises à jour de métadonnées ci-dessus aux ressources sélectionnées. Une fois enregistrés, les mots-clés et les balises sont ajoutés, tandis que les détails mis à jour pour le statut, la date d’expiration et l’auteur remplacent leurs détails existants.

     ![save-bulk-metadata-edit-properties](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >Vous pouvez modifier les métadonnées de 100 ressources à la fois.

Pour afficher les mises à jour des métadonnées appliquées à une ressource, accédez à la page des détails de la ressource (sélectionnez la ressource, cliquez sur **Détails**), puis cliquez sur ![](/help/using/assets/info-icon-solid-black.svg) pour afficher les métadonnées de la ressource dans le panneau **Informations**.

>[!NOTE]
>
>**Statut**, **Date d’expiration**, **Auteur**, **Mots-clés** et **Balises** sont des propriétés de métadonnées standard disponibles pour la modification de métadonnées en bloc, quelles que soient les métadonnées spécifiques au dossier. Ces propriétés de métadonnées s’affichent dans la page des détails de la ressource uniquement si elles sont incluses dans le formulaire de métadonnées appliqué au dossier de la ressource. Si vous ne trouvez pas ces propriétés de métadonnées standard sur la page des détails de la ressource, modifiez le formulaire de métadonnées du dossier de ressources pour les inclure. Consultez [Métadonnées dans Assets Essentials](/help/using/metadata.md) pour savoir comment créer ou modifier un formulaire de métadonnées et l’appliquer à un dossier.
