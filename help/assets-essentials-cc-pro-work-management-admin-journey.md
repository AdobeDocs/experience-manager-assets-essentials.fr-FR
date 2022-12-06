---
title: Configuration d’Assets Essentials pour Creative Cloud Pro avec les solutions de gestion du travail
description: Ce tutoriel présente un parcours d’administrateur pour permettre à l’application Assets Essentials de s’intégrer aux applications de bureau Creative Cloud et à l’application Adobe Workfront. Les applications de bureau Creative Cloud comprennent Adobe Photoshop, Adobe Illustrator, Adobe InDesign et Adobe XD.
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: 8920080944981fc1a990136af46c9258c5e8627c
workflow-type: tm+mt
source-wordcount: '941'
ht-degree: 97%

---

# Assets Essentials pour Creative Cloud Pro avec les solutions de gestion du travail {#creative-cloud-enterprise-user-journeys}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-next-banner-landing-page.png)

## Présentation {#introduction}

Creative Cloud Pro pour entreprise avec solutions de gestion du travail intègre des outils de création, de contenu, et de gestion du travail afin d’accroître votre capacité à produire du contenu créatif et à atteindre rapidement les objectifs de l’entreprise. La solution comprend les composants suivants :

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

Ce tutoriel présente un parcours d’administrateur pour permettre à l’application Assets Essentials de s’intégrer aux applications de bureau Creative Cloud et à l’application Adobe Workfront. Les applications de bureau Creative Cloud comprennent Adobe Photoshop, Adobe Illustrator, Adobe InDesign et Adobe XD.

## Types de déploiements {#deployment-types}

La solution étant composée d’applications et de services issus de Creative Cloud et d’Adobe Experience Cloud, elle peut être déployée dans une ou deux Admin Console Adobe pour votre entreprise.

En cas de déploiement dans deux Admin Console, une étape de configuration supplémentaire est requise :

* Les services et applications Creative Cloud (Creative Cloud abonnement Enterprise Pro et modules facultatifs) sont gérés dans [Adobe Admin Console pour votre déploiement Creative Cloud](https://helpx.adobe.com/fr/enterprise/admin-guide.html).

* Adobe Workfront et Adobe Experience Manager Assets Essentials sont gérés dans [Adobe Admin Console pour les solutions Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=fr).

Pour intégrer les applications Creative Cloud et Assets Essentials, les utilisateurs qui sont disponibles dans Admin Console for Creative Cloud doivent être disponibles dans Admin Console for Experience Cloud. Pour rendre les utilisateurs disponibles dans Admin Console Experience Cloud, créez un répertoire pour établir une [confiance de répertoire](https://helpx.adobe.com/fr/enterprise/using/set-up-identity.html) entre les deux consoles d’administration.

![Utilisateurs de Creative Cloud](assets/creative-cloud-users.svg)

Comme illustré dans le diagramme, les utilisateurs de Creative Cloud sont automatiquement mis à disposition dans l’Admin Console Experience Cloud en fonction d’une relation de confiance entre les deux consoles. Vous pouvez ensuite ajouter les utilisateurs aux profils de produits Assets Essentials. Par conséquent, les utilisateurs de Creative Cloud peuvent accéder à l’application Adobe Asset Link qui peut interagir avec le référentiel Assets Essentials. Pour plus d’informations, voir [Intégrer Assets Essentials avec les applications Creative Cloud](integrate-with-creative-cloud.md).

## Parcours de documentation Experience Manager {#documentation-journeys}

Un parcours de documentation relie de nombreux sujets et fonctionnalités différents et peut-être complexes en fournissant un récit qui aide le lecteur, qui peut être nouveau dans Assets Essentials, à comprendre et à résoudre un problème commercial du début à la fin, tout en supposant une connaissance préalable minimale du sujet ou d’Assets Essentials.

Les parcours de documentation sont conçus autour des principes de bonne pratique, reposent sur les dernières recherches d’Adobe, sur l’expérience éprouvée de mise en œuvre des consultants Adobe, ainsi que sur les retours de projets clients.

## Prérequis

* [Accès à Adobe Admin Console pour les solutions Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Accès à Adobe Admin Console pour un déploiement de Creative Cloud abonnement Entreprise](https://helpx.adobe.com/fr/enterprise/admin-guide.html)

## Administrer Experience Manager Assets Essentials {#administer-assets-essentials}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials est une nouvelle édition allégée d’Adobe Experience Manager Assets. Assets Essentials offre une gestion des ressources unifiée et une collaboration avec une interface utilisateur simplifiée et cohérente. Sa facilité d’utilisation permet de développer l’efficacité des équipes créatives et marketing en leur permettant de stocker, découvrir et distribuer facilement leurs ressources numériques.

Adobe Experience Manager Assets Essentials est mis à disposition par Adobe pour ses clients. Dans le cadre de la mise en service, Assets Essentials est ajouté à l’organisation d’un client dans Adobe Admin Console.

Les administrateurs utilisent l’Admin Console pour gérer les droits des utilisateurs sur le produit Assets Essentials :

* Ajouter des groupes d’utilisateurs

* Ajouter des utilisateurs aux groupes d’utilisateurs

* Ajouter des utilisateurs aux profils du produit Assets Essentials

Après avoir géré les droits des utilisateurs dans l’Admin Console, les administrateurs peuvent utiliser l’application Assets Essentials pour :

* Créer une structure de dossiers pour mieux prendre en charge les besoins de l’entreprise.

* Gérer les autorisations pour la structure de dossiers.

* Configurer les formulaires de métadonnées.

[![Voir le Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](deploy-administer.md)

Maintenant que vous avez configuré et géré l’application Assets Essentials, [intégrez les applications Creative Cloud à l’application Experience Manager Assets Essentials](integrate-with-creative-cloud.md).

## Intégrer les applications Creative Cloud à Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-creative-cloud.png)

Le [panneau in-app Adobe Asset Link](https://www.adobe.com/fr/creativecloud/business/enterprise/adobe-asset-link.html) permet aux professionnels de la création de se connecter au référentiel [!DNL Assets Essentials] à partir des applications de bureau [!DNL Adobe Creative Cloud] prises en charge. Le panneau est disponible pour [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] et [!DNL Adobe XD]. Il simplifie l’accès aux ressources, ce qui accroît la vitesse du contenu.

Ce tutoriel vous guide pour intégrer les applications [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], et [!DNL Adobe XD] à Experience Manager Assets Essentials.

Objectifs :

* Créer un répertoire de confiance entre Creative Cloud et Experience Cloud Admin Consoles

* Ajouter les utilisateurs Creative Cloud aux profils de produits Assets Essentials.

* Installez Adobe Asset Link.

* Utilisation d’Adobe Asset Link

[![Voir le Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

Maintenant que vous avez intégré les applications Creative Cloud à Assets Essentials, [Intégrez Adobe Workfront à Experience Manager Assets Essentials](integrate-with-workfront.md).

## Intégrer Adobe Workfront à Experience Manager Assets Essentials {#administer-adobe-workfront}

![Préférence pour changer de thème (sombre ou clair)](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) est une application de gestion du travail qui vous permet de gérer l’ensemble du cycle de vie du travail en un seul endroit. L’intégration native entre [!DNL Adobe Workfront] et [!DNL Assets Essentials] permet aux entreprises d’accroître la vitesse du contenu et le délai de mise sur le marché en établissant des liens intrinsèques entre le travail et la gestion des ressources. Dans le cadre de la gestion de leur travail, les utilisateurs ont accès aux documents et images requis dans la même solution.

Ce tutoriel vous guide pour administrer Adobe Workfront et l’intégrer ensuite à Experience Manager Assets Essentials.

Objectifs :

* Ajouter des utilisateurs aux profils de produits Workfront.

* Ajouter des utilisateurs aux profils du produit Assets Essentials

* Configurer l’intégration d’Experience Manager Assets Essentials.

[![Voir le Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-workfront.md)
