---
type: Tool
---

Obscura is a lightweight, stealthy headless browser engine written in Rust, designed specifically for web scraping and AI agent automation. It executes real JavaScript using the V8 engine and supports the Chrome DevTools Protocol (CDP), making it a compatible drop-in replacement for headless Chrome in tools like Puppeteer and Playwright. Key features include low memory usage (~30 MB), small binary size (~70 MB), fast startup (~instant), and anti-detection mechanisms such as anti-fingerprinting and tracker blocking. Obscura is optimized for automation at scale, offering high performance in page load times (~85 ms for static HTML) and parallel scraping capabilities.