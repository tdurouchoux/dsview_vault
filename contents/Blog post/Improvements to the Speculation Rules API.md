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

1. **Document Rules**: A new option for automatic link finding using document rules, which allows sourcing URLs from the document itself based on conditions like href matches or CSS selectors. This makes deployment easier and more efficient.

2. **Eagerness Settings**: Four settings (immediate, eager, moderate, conservative) to control when speculations should run, balancing between precision, recall, and lead time. The default eagerness for document rules is conservative.

3. **Chrome Limits**: Limits on speculations to prevent overuse, with different thresholds for immediate/eager and moderate/conservative settings. Speculations are also canceled under certain conditions like Save-Data or memory constraints.

4. **Optional Source**: The source key is now optional, as it can be inferred from the presence of the url or where keys.

5. **Speculation-Rules HTTP Header**: Allows delivering speculation rules via an HTTP header, enabling easier deployment by CDNs without altering document contents.

6. **Better Cache Reuse**: Improvements to caching in Chrome ensure that prefetched or prerendered resources are stored and reused, making re-speculation cheaper.

7. **No-Vary-Search Support**: Allows servers to specify URL parameters that do not affect the delivered resource, improving cache reuse.

8. **Platform Support**: Integration with platforms like WordPress, Akamai, Uxify, and Astro to simplify the implementation of speculation rules.

9. **Demo and Debugging**: A demo and debugging tools are available to help developers understand and implement speculation rules effectively.

The goal is to encourage wider adoption of the Speculation Rules API, leading to better performance for end users. The Chrome team also hints at future opportunities, such as combining prerendering with View Transitions for enhanced user experiences.
## Links

- [Speculation Rules API on Akamai](https://discuss.akamai.com/t/speculation-rules-api-on-akamai/1242) : Discussion on implementing the Speculation Rules API with Akamai, a leading CDN provider.
- [Speculation Rules API Documentation](https://uxify.com/blog/post/speculation-rules-api) : Documentation on Uxify's implementation of the Speculation Rules API, focusing on predictive navigation.

## Topics

![](topics/Concept/Speculation%20Rules%20API)