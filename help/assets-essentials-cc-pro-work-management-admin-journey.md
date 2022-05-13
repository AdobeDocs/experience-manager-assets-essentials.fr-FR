---
title: Configuration d’Assets Essentials pour Creative Cloud Pro avec des solutions de gestion du travail
description: 'Ce tutoriel présente un parcours administrateur pour permettre à l’application Assets Essentials de s’intégrer aux applications de bureau Creative Cloud et à l’application Adobe Workfront. Les applications de bureau Creative Cloud comprennent Adobe Photoshop, Adobe Illustrator, Adobe InDesign et Adobe XD. '
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '900'
ht-degree: 13%

---


# Assets Essentials pour Creative Cloud Pro avec les solutions de gestion du travail {#creative-cloud-enterprise-user-journeys}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-next-banner-landing-page.png)

## Présentation {#introduction}

Creative Cloud Pro pour entreprise avec solutions de gestion du travail intègre des outils de gestion du contenu, des créatifs et du travail afin d’accroître votre capacité à produire du contenu créatif et d’atteindre rapidement les objectifs de l’entreprise. La solution comprend les composants suivants :

* Creative Cloud Pro

* Adobe Workfront

*  dʼExperience Manager Assets Essentials

Ce tutoriel présente un parcours administrateur pour permettre à l’application Assets Essentials de s’intégrer aux applications de bureau Creative Cloud et à l’application Adobe Workfront. Les applications de bureau Creative Cloud comprennent Adobe Photoshop, Adobe Illustrator, Adobe InDesign et Adobe XD.

## Types de déploiements {#deployment-types}

La solution étant composée d’applications et de services de Creative Cloud et de Adobe Experience Cloud, ils peuvent être déployés dans un ou deux Admin Console Adobes pour votre entreprise.

En cas de déploiement en deux Admin Console, une étape de configuration supplémentaire est requise :

* Les services et applications de Creative Cloud (Creative Cloud pour Enterprise Pro et modules facultatifs) sont gérés dans [Adobe Admin Console pour votre déploiement Creative Cloud](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront et Adobe Experience Manager Assets Essentials sont gérés dans [Adobe Admin Console pour les solutions Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

Pour intégrer des applications Creative Cloud et Assets Essentials, les utilisateurs disponibles dans Admin Console pour Creative Cloud doivent être disponibles dans Admin Console pour Experience Cloud. Pour rendre les utilisateurs disponibles dans Experience Cloud Admin Console, créez un annuaire à partir duquel [confiance du répertoire](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) entre les deux consoles d’administration.

![Utilisateurs de Creative Cloud](assets/creative-cloud-users.svg)

Comme illustré dans le diagramme, les utilisateurs Creative Cloud sont automatiquement mis à disposition dans le Admin Console Experience Cloud en fonction d’une relation de confiance entre les deux consoles. Vous pouvez ensuite ajouter les utilisateurs aux profils de produit Assets Essentials. Par conséquent, les utilisateurs Creative Cloud peuvent accéder à l’application Adobe Asset Link qui peut interagir avec le référentiel Assets Essentials. Pour plus d’informations, voir [Intégration d’Assets Essentials à des applications Creative Cloud](integrate-assets-essentials-creative-cloud.md).

## parcours de documentation du Experience Manager {#documentation-journeys}

Un Parcours de documentation relie de nombreux sujets et fonctionnalités différents et peut-être complexes en fournissant un récit qui aide le lecteur, qui peut être novice dans Assets Essentials, à comprendre et à résoudre un problème commercial du début à la fin, tout en assumant un minimum de connaissances préalables ou Assets Essentials.

Les Parcours de documentation sont conçus autour des principes de bonnes pratiques, reposant sur les dernières recherches d’Adobe, l’expérience de mise en oeuvre éprouvée des consultants Adobe et les commentaires des projets clients.

## Conditions préalables

* [Accès à Adobe Admin Console pour les solutions Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Accès à Adobe Admin Console pour le déploiement en entreprise de Creative Cloud](https://helpx.adobe.com/enterprise/admin-guide.html)

## Administration de Experience Manager Assets Essentials {#administer-assets-essentials}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials est une nouvelle édition légère d’Adobe Experience Manager Assets. Assets Essentials offre une gestion et une collaboration des ressources unifiées grâce à une interface utilisateur simplifiée et cohérente. Sa facilité d’utilisation permet de développer l’efficacité des équipes créatives et marketing en leur permettant de stocker, découvrir et distribuer facilement leurs ressources numériques.

Adobe Experience Manager Assets Essentials est configuré par Adobe pour ses clients. Dans le cadre de la mise en service, Assets Essentials est ajouté à l’organisation d’un client dans Adobe Admin Console.

Les administrateurs utilisent le Admin Console pour gérer les droits des utilisateurs au produit Assets Essentials :

* Ajouter des groupes d’utilisateurs

* Ajout d’utilisateurs à des groupes d’utilisateurs

* Ajout d’utilisateurs à des profils de produit Assets Essentials

Après avoir géré les droits des utilisateurs dans Admin Console, les administrateurs peuvent utiliser l’application Assets Essentials pour :

* Créer une structure de dossiers pour mieux prendre en charge les besoins de l’entreprise

* Gestion des autorisations pour la structure de dossiers

* Configuration de formulaires de métadonnées

[![Voir le Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](adminster-aem-assets-essentials.md)

## Intégration des applications Creative Cloud à Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-creative-cloud.png)

[Adobe du panneau intégré à Asset Link](https://www.adobe.com/fr/creativecloud/business/enterprise/adobe-asset-link.html) permet aux professionnels de la création de se connecter à [!DNL Assets Essentials] du référentiel pris en charge ; [!DNL Adobe Creative Cloud] applications de bureau. Le panneau est disponible pour [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] et [!DNL Adobe XD]. Il simplifie l’accès aux ressources, ce qui accroît la vitesse du contenu.

Ce tutoriel vous guide à intégrer [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], et [!DNL Adobe XD] applications avec Experience Manager Assets Essentials.

Objectifs:

* Création d’une confiance d’annuaire entre les Admin Console Creative Cloud et Experience Cloud

* Ajout d’utilisateurs Creative Cloud à des profils de produit Assets Essentials

* Installation d’Adobe Asset Link

* Utilisation d’Adobe Asset Link

[![Voir le Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-creative-cloud.md)

## Intégration d’Adobe Workfront à Experience Manager Assets Essentials {#administer-adobe-workfront}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) est une application de gestion du travail qui vous permet de gérer l’ensemble du cycle de vie du travail en un seul endroit. L’intégration native entre [!DNL Adobe Workfront] et [!DNL Assets Essentials] permet aux entreprises d’améliorer la vitesse du contenu et le temps de mise sur le marché en établissant des liens intrinsèques entre le travail et la gestion des ressources. Dans le cadre de la gestion de leur travail, les utilisateurs ont accès aux documents et images requis dans la même solution.

Ce tutoriel vous guide à administrer Adobe Workfront, puis à l’intégrer à Experience Manager Assets Essentials.

Objectifs:

* Ajout d’utilisateurs aux profils de produit Workfront

* Ajout d’utilisateurs à des profils de produit Assets Essentials

* Configuration de l’intégration de Experience Manager Assets Essentials

[![Voir le Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-workfront.md)


