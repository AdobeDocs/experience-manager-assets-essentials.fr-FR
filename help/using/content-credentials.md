---
title: Intégration de Content Credentials
description: Content Credentials, intégré à AEM Assets et présenté dans l’interface d’utilisation d’AEM Assets Essentials, peut fournir un contexte dans l’historique d’une ressource, y compris la manière dont elle a été créée et les personnes impliquées dans sa création. Tout comme une étiquette nutritionnelle pour le contenu numérique, Content Credentials peut contribuer à accroître la transparence et à établir la confiance du public.
role: User
exl-id: 703f74a6-24d4-4181-8174-9ff4a90ee7aa
TQID: https://experienceleague.adobe.com/witCqgAh8EKfD-hdn8efjZ-M4sypX44KB2ELs3ECInI
product_v2:
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2:
  - id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 474
ht-degree: 100%

---

# Content Credentials {#content-credentials}

Les marques sont plus préoccupées que jamais par la transparence du contenu, la déclaration d’utilisation de l’IA et la prévention de l’altération des ressources. Le Content Authenticity Initiative (CAI) d’Adobe crée des outils conformes à la norme technique [C2PA](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) (Coalition for Content Provenance and Authenticity). Les identifiants de contenu, qui sont un nouveau type de métadonnées chiffrées et inviolables, peuvent aider les visiteurs à comprendre la traçabilité du contenu et garantir l’intégrité des ressources de la marque. Ils peuvent inclure un large éventail de données de provenance qui fournissent des informations dans l’historique d’une ressource numérique.

Cela inclut :

* **Émetteur ou signataire :** informations sur l’entité ou la société qui a émis la signature numérique pour certifier l’élément certifie ou signe l’élément.
* **Date de l’événement :** date à laquelle Content Credential a été appliqué à la ressource.
* **Crédit et utilisation :** informations sur le producteur de la ressource, y compris le nom, les identifiants de médias sociaux ou d’autres informations relatives à l’identité.
* **Processus :** les enregistrements des modifications apportées à la ressource.
* **Détails de l’appareil :** informations sur l’application ou l’appareil utilisé pour créer ou modifier la ressource.
* **Outil d’IA utilisé :** si l’IA générative a été utilisée pour modifier ou créer la ressource, le nom du modèle utilisé peut être inclus.
* **Autres informations pertinentes :** des données supplémentaires peuvent également être incluses pour offrir plus de contexte sur l’historique d’une ressource.

Pour une vue complète, la fonction [Vérifier](https://contentcredentials.org/verify) peut proposer une insight plus complète de l’historique des ressources.

Adobe Experience Manager Assets prend désormais en charge Content Credentials, qui peut s’afficher directement dans l’interface d’utilisation d’Assets Essentials d’AEM. Lorsque vous examinez les détails de la ressource, toute image avec Content Credentials (telle que celles créées avec les services GenAI) affiche les détails du manifeste dans un panneau dédié. Si la ressource est téléchargée, publiée ou partagée, les informations d’identification restent intactes avec la ressource.

![ressources](/help/using/assets/content-credentials.png)

## Accéder à Content Credentials {#access-content-credentials}

1. Accédez à l’interface d’utilisation d’Assets Essentials, puis cliquez sur **Ressources** dans le volet de gauche.
1. Accédez à un dossier et sélectionnez la ressource souhaitée.
1. Cliquez sur **Détails** et sélectionnez `Cr pin` dans le volet le plus à droite. L’onglet Content Credentials affiche les informations suivantes sur la ressource.
   1. **Image générée :** date et heure d’application de Content Credentials.
   1. **Résumé du contenu :** indique si la ressource est partiellement ou entièrement générée par l’IA, ou comment elle a été modifiée.
      ![Résumé du contenu](/help/using/assets/content-credentials1.png)
   1. **Processus :** décrit l’application, l’appareil et l’outil d’IA (comme Adobe Firefly) utilisés pour générer la ressource, ainsi que les modifications apportées ultérieurement.
      ![processus](/help/using/assets/CR-Process.png)
   1. **À propos de ce Content Credentials :** nom de l’émetteur, ainsi que la date et l’heure d’émission.
      ![émetteur](/help/using/assets/CR-issuer.png)
