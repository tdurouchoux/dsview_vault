---
already_read: false
link: https://developer.chrome.com/blog/speculation-rules-improvements
read_priority: 1
relevance: 0
source: null
tags:
- AI_agent
type: Content
upload_date: '2024-05-23'
---

https://developer.chrome.com/blog/speculation-rules-improvements
## Summary

The blog discusses updates to the Speculation Rules API in Chrome 122, aimed at enhancing navigation performance by allowing prefetching and prerendering of pages. Key improvements include:

1. **Document Rules**: Automatic link finding from the document, allowing a single ruleset for an entire site and reducing deployment complexity.
  
2. **Eagerness Settings**: The new settings (immediate, eager, moderate, conservative) control the timing of speculations. Default eagerness for document rules is conservative, while list rules are immediate.

3. **Speculation Limits**: Chrome imposes limits on the number of simultaneous prefetching/prerendering, based on eagerness levels to conserve resources.

4. **No-Vary-Search Support**: This allows reuse of cached pages regardless of certain URL parameters, improving cache efficiency.

5. **Speculation-Rules HTTP Header**: Speculation rules can be delivered via an HTTP header, facilitating deployment through CDNs without altering HTML.

6. **Caching Improvements**: Enhancements have been made to better use HTTP caching for resources, regardless of whether speculations are used.

7. **Platform Support**: Integration with platforms like WordPress and Akamai, as well as experimental implementations in frameworks like Astro, indicates growing adoption.

Overall, these updates aim to simplify the implementation of performance enhancements while minimizing resource waste, with expectations for broader adoption in the future.
## Links

- [Prerender Pages with Speculation Rules by Akamai](https://techdocs.akamai.com/ion/docs/prerender-pages-with-speculation-rules) : Documentation by Akamai on how to enable and utilize the Speculation Rules API for prerendering pages.
- [Speculation Rules API Documentation by Uxify](https://uxify.com/blog/post/speculation-rules-api) : Overview of Uxify's implementation of the Speculation Rules API and its advantages.
- [Experimental Client Prerender Documentation by Astro](https://docs.astro.build/en/reference/configuration-reference/#experimentalclientprerender) : Astro's guide on enabling prerendering pages using the Speculation Rules API.
- [Web Incubator Community Group (WICG) - Specification for Navigation Speculation](https://wicg.github.io/nav-speculation/no-vary-search.html) : WICG's proposal detailing the navigation speculation API standards.
- [No Vary Search Proposal](https://wicg.io/) : WICG site providing insights and proposals on various web standards, including the No Vary Search feature.

## Topics

![](topics/Concept/Speculation%20Rules%20API)

![](topics/Concept/Prefetching%20and%20Prerendering)

![](topics/Platform/Chrome)

![](topics/Concept/Eagerness%20Settings)

![](topics/Tool/DevTools)