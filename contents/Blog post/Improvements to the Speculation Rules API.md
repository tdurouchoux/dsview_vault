---
already_read: false
link: https://developer.chrome.com/blog/speculation-rules-improvements
read_priority: 1
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2024-05-23'
---

https://developer.chrome.com/blog/speculation-rules-improvements
## Summary

The Chrome team has introduced improvements to the Speculation Rules API, aimed at enhancing navigation performance through prefetching and prerendering. Key updates include:

1. **Document Rules**: A new option for automatic link finding using document rules, which allows sourcing URLs from the document itself based on conditions like href matches or CSS selectors. This makes it easier to deploy speculation rules across an entire site.

2. **Eagerness Settings**: Four settings (immediate, eager, moderate, conservative) to control when speculations should run, balancing between precision, recall, and lead time. The default eagerness for document rules is conservative, while for list rules it is immediate.

3. **Chrome Limits**: Limits on the number of speculations to prevent overuse, with different thresholds for prefetch and prerender based on eagerness settings. Speculations are managed in a First In, First Out (FIFO) manner for moderate and conservative settings.

4. **Optional Source**: The source key is now optional in Chrome 122, as it can be inferred from the presence of the url or where keys.

5. **Speculation-Rules HTTP Header**: Allows delivering speculation rules via an HTTP header, making deployment easier through CDNs without altering document contents.

6. **Better Cache Reuse**: Improvements to caching in Chrome ensure that prefetched or prerendered resources are stored and reused, reducing the cost of re-speculating.

7. **No-Vary-Search Support**: Allows servers to specify URL parameters that do not result in different pages, enabling browsers to reuse cached versions of documents that differ only by these parameters.

8. **Platform Support**: Integration with platforms like WordPress, Akamai, Uxify, and Astro to simplify the implementation of speculation rules.

The updates aim to make prefetching and prerendering easier to deploy and less wasteful, encouraging wider adoption and ultimately improving performance for end users. The Chrome team is also working on standardizing the API through the Web Incubator Community Group (WICG) to allow other browsers to implement it.
## Links

- [Speculation Rules API](https://wicg.github.io/nav-speculation/no-vary-search.html) : The Speculation Rules API is a web API that allows developers to specify rules for prefetching or prerendering pages. This can improve navigation performance by speculating on future navigations and loading resources in advance.
- [No-Vary-Search Proposal](https://wicg.github.io/nav-speculation/no-vary-search.html) : The No-Vary-Search proposal is a web standard that allows servers to specify which URL parameters do not result in a difference to the resource delivered. This can improve cache reuse and reduce unnecessary downloads.

## Topics

![](topics/Concept/Speculation%20Rules%20API)

![](topics/Concept/Prefetching)

![](topics/Concept/Prerendering)

![](topics/Concept/Eagerness%20Setting)

![](topics/Concept/No%20Vary%20Search%20Proposal)