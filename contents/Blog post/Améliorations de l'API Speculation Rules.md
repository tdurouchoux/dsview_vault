---
already_read: false
link: https://developer.chrome.com/blog/speculation-rules-improvements?hl=fr#demo
read_priority: 1
source: null
tags:
- Cloud_Computing
type: Content
upload_date: '2024-05-23'
---

https://developer.chrome.com/blog/speculation-rules-improvements?hl=fr#demo
## Summary

L'équipe Chrome a mis à jour l'API Speculation Rules pour améliorer les performances de navigation en préchargeant et prérendant des pages. Ces améliorations, disponibles depuis Chrome 122, facilitent le déploiement et réduisent le gaspillage de ressources. 

Les principales nouveautés incluent :
- **Règles de document** : Les URL peuvent maintenant être extraites directement du document, simplifiant ainsi la gestion des règles de spéculation.
- **Paramètre eagerness** : Permet de contrôler le moment d'exécution des spéculations, avec des options allant de "immediate" à "conservative", afin de réduire le gaspillage de bande passante.
- **Limites de spéculation** : Chrome impose des limites pour éviter l'abus de l'API, avec des seuils différents selon le type de spéculation.
- **En-tête HTTP Speculation-Rules** : Permet de transmettre les règles de spéculation via un en-tête HTTP, facilitant le déploiement par les CDN.
- **Améliorations de mise en cache** : Optimisation de la réutilisation des ressources mises en cache pour réduire les coûts de bande passante.

Des intégrations avec des plateformes comme WordPress et Akamai sont en cours, et l'adoption de cette API est attendue pour 2024. Les développeurs sont encouragés à utiliser ces nouvelles fonctionnalités pour améliorer l'expérience utilisateur.
## Links

1. [API Speculation Rules](https://developer.chrome.com/docs/web-platform/prerender-pages?hl=fr) - Documentation on the Speculation Rules API, which enhances navigation performance by preloading and prerendering future navigations.
2. [No-Vary-Search](https://wicg.github.io/nav-speculation/no-vary-search.html) - Proposal for a server to specify URL parameters that do not affect the resource served, allowing better cache reuse.
3. [FIFO (computing and electronics)](https://en.wikipedia.org/wiki/FIFO_(computing_and_electronics)) - Explanation of the First In, First Out (FIFO) principle, relevant to the speculation limits discussed in the article.
4. [Save Data](https://web.dev/articles/optimizing-content-efficiency-save-data?hl=fr) - Article discussing the Save Data feature, which can impact speculation rules and resource usage.
5. [NitroPack Speculation Rules API](https://nitropack.io/blog/post/speculation-rules-api) - Documentation on how NitroPack utilizes the Speculation Rules API for performance optimization.
## Topics

- [[topics/Concept/API Speculation Rules]]
- [[topics/Library/Workbox]]
- [[topics/Platform/Chrome]]
- [[topics/Platform/WordPress]]
- [[topics/Platform/Akamai]]