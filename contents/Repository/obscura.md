---
already_read: true
link: https://github.com/h4ckf0r0day/obscura
read_priority: 0
relevance: 2
source: Alpha Signal
tags:
- Development_tool
type: Content
upload_date: '2026-04-28'
---

https://github.com/h4ckf0r0day/obscura
## Summary

Obscura is a lightweight, stealthy headless browser engine built in Rust for AI agents and web scraping. Key technical points:

- **Performance**: Uses ~30MB RAM vs 200+MB for headless Chrome, 70MB binary vs 300+MB, faster startup (~instant vs ~2s) and page load (~85ms vs ~500ms).
- **Compatibility**: Supports Chrome DevTools Protocol (CDP) and works as a drop-in replacement for Puppeteer/Playwright.
- **Anti-detection**: Built-in stealth mode with fingerprint randomization, tracker blocking (3,520 domains), and realistic navigator.userAgentData.
- **CLI**: Commands like `obscura fetch`, `obscura serve`, and `obscura scrape` for scraping, parallel processing, and CDP server.
- **Benchmarks**: Faster page loads across static HTML, JS+XHR, and dynamic scripts.
- **License**: Apache 2.0. Requires Rust 1.75+ for building.
## Links

- [GitHub - Obscura Releases](https://github.com/h4ckf0r0day/obscura/releases) : The official releases page for Obscura, providing downloadable binaries for Linux, macOS, and Windows. Essential for users who want to use the tool without building from source.
- [Rustup - Install Rust](https://rustup.rs) : The official Rust toolchain installer. Required for building Obscura from source, as it is written in Rust.

## Topics

![[topics/Tool/Obscura]]

![[topics/Concept/Headless Browser]]

![[topics/Concept/Chrome DevTools Protocol CDP]]

![[topics/Concept/Stealth Mode Anti Detection]]

![[topics/Concept/Anti Fingerprinting]]