---
already_read: true
link: https://github.com/supermemoryai/markdowner
read_priority: 0
relevance: 4
source: null
tags:
- Data_Engineering
type: Content
upload_date: '2026-04-06'
---

https://github.com/supermemoryai/markdowner
## Summary

**Markdowner** is a fast, open-source tool to convert any website into LLM-ready markdown data. It addresses limitations of existing solutions (cost, proprietary constraints, deployment complexity) by leveraging Cloudflare's Browser Rendering and Durable Objects with Turndown for HTML-to-markdown conversion.

**Key Features**:
- Converts websites to markdown (supports text/JSON responses).
- LLM filtering, detailed markdown mode, auto-crawler (no sitemap needed).
- Self-hosting capability (requires Cloudflare Workers paid plan).

**Usage**:
- API endpoint: `https://md.dhr.wtf/?url=<website>`
- Optional parameters: `enableDetailedResponse`, `crawlSubpages`, `llmFilter`.
- Response format controlled via `Content-Type` header.

**Tech Stack**: Cloudflare Workers, Turndown, TypeScript.
**Self-hosting**: Clone repo, configure KV namespace, deploy via `wrangler`.

**License**: MIT. GitHub repo: [supermemoryai/markdowner](https://github.com/supermemoryai/markdowner).
## Links

- [Firecrawl.dev](https://firecrawl.dev) : A competitor tool for converting websites into structured data, mentioned in the Markdowner repository as having limitations like cost or proprietary constraints.
- [Jina AI's r.jina.ai](https://r.jina.ai) : A competitor tool for converting websites into readable formats for LLMs, mentioned in the Markdowner repository as an alternative solution.
- [Cloudflare Browser Rendering](https://developers.cloudflare.com/browser-rendering/) : Documentation for Cloudflare's Browser Rendering technology, which Markdowner uses to spin up browser instances for converting websites to markdown.
- [Cloudflare Durable Objects](https://developers.cloudflare.com/durable-objects/) : Documentation for Cloudflare's Durable Objects, a key technology used by Markdowner for managing stateful connections during the conversion process.
- [Supermemory.ai](https://supermemory.ai) : The website of the company that built Markdowner, providing context about the tool's origin and purpose.

## Topics

![[topics/Tool/Markdowner]]

![[topics/Platform/Cloudflare Workers]]

![[topics/Library/Turndown]]