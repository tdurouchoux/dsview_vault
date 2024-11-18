---
already_read: false
link: https://developer.chrome.com/blog/speculation-rules-improvements?hl=fr#demo
read_priority: 1
source: null
type: Content
upload_date: '2024-05-23'
---

https://developer.chrome.com/blog/speculation-rules-improvements?hl=fr#demo
## Summary

L'équipe Chrome a mis à jour l'API Speculation Rules pour améliorer les performances de navigation en facilitant le préchargement et le prérendu des pages. Ces améliorations, disponibles depuis Chrome 122, incluent des règles de spéculation plus dynamiques et moins coûteuses en ressources.

Les nouvelles fonctionnalités permettent d'extraire automatiquement des liens à partir du document ou d'utiliser des sélecteurs CSS pour déterminer les URL à précharger. Un paramètre d'impatience (eagerness) a été introduit pour gérer le moment de la spéculation, avec des options allant de "immediate" à "conservative", permettant ainsi de mieux contrôler l'utilisation des ressources.

Des limites sont imposées pour éviter une utilisation excessive de l'API, et des en-têtes HTTP Speculation-Rules peuvent être utilisés pour déployer des règles sans modifier le contenu HTML. Des améliorations ont également été apportées au stockage en cache pour réutiliser les ressources préchargées.

Des intégrations avec des plateformes comme WordPress et Akamai facilitent l'adoption de cette API. L'équipe Chrome espère une adoption accrue en 2024, avec des perspectives d'amélioration continue des performances utilisateur.
## Links

1. [Akamai Speculation Rules Documentation](https://techdocs.akamai.com/ion/docs/prerender-pages-with-speculation-rules) - Documentation on how to enable and use the Speculation Rules API with Akamai's CDN.
2. [WordPress Speculation Rules Plugin](https://wordpress.org/plugins/speculation-rules/) - A plugin that allows easy integration of Speculation Rules into WordPress sites.
3. [Astro Documentation on Speculation Rules](https://astro.build/blog/astro-420/#experimental-prerendering-pages-using-the-speculation-rules-api) - Information on how Astro integrates the Speculation Rules API for preloading pages.
4. [No-Vary-Search Proposal](https://wicg.github.io/nav-speculation/no-vary-search.html) - A proposal that allows browsers to reuse cached versions of documents with different URL parameters.
5. [Debugging Speculation Rules with DevTools](https://developer.chrome.com/docs/devtools/application/debugging-speculation-rules?hl=fr) - Guide on how to use Chrome DevTools to debug and analyze the implementation of Speculation Rules.
## Topics

![](topics/Concept/API%20Speculation%20Rules)

![](topics/Product/Chrome%20122)

![](topics/Product/WordPress%20Speculation%20Rules%20Plugin)

![](topics/Product/Akamai)

![](topics/Product/NitroPack)