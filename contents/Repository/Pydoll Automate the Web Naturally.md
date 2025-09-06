---
already_read: false
link: https://github.com/thalissonvs/pydoll
read_priority: 1
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2025-03-11'
---

https://github.com/thalissonvs/pydoll
## Summary

Pydoll is a Python library designed for automating Chromium-based browsers without the need for a WebDriver, offering realistic interactions. It connects directly to the Chrome DevTools Protocol (CDP), eliminating the need for external drivers and providing a clean implementation for realistic interactions.

Key features include:
- **Zero WebDrivers**: No compatibility issues with WebDrivers.
- **Human-like Interaction Engine**: Capable of passing behavioral CAPTCHAs like reCAPTCHA v3 or Turnstile, depending on IP reputation and interaction patterns.
- **Asynchronous Performance**: Supports high-speed automation and multiple simultaneous tasks.
- **Humanized Interactions**: Mimics real user behavior.
- **Simplicity**: Easy installation and immediate automation.

### New Features:
- **Remote Connections via WebSocket**: Control any Chrome instance remotely via its WebSocket address.
- **DOM Navigation**: Methods like `get_children_elements()` and `get_siblings_elements()` for efficient DOM traversal.
- **WebElement State Waiting**: New `wait_until(...)` method to await element states with minimal code.
- **Browser-context HTTP Requests**: Make HTTP requests that automatically inherit the browser's session state.
- **Download Management**: `expect_download()` context manager for robust file downloads.
- **Custom Browser Preferences**: Control hundreds of internal Chrome settings for advanced customization.
- **Concurrent Automation**: Asynchronous implementation allows for simultaneous automation of multiple tabs.

### Installation:
```bash
pip install pydoll-python
```

### Example Usage:
```python
import asyncio
from pydoll.browser import Chrome
from pydoll.constants import Key

async def google_search(query: str):
    async with Chrome() as browser:
        tab = await browser.start()
        await tab.go_to('https://www.google.com')
        search_box = await tab.find(tag_name='textarea', name='q')
        await search_box.insert_text(query)
        await search_box.press_keyboard_key(Key.ENTER)
        await (await tab.find(
            tag_name='h3',
            text='autoscrape-labs/pydoll',
            timeout=10,
        )).click()
        await tab.find(id='repository-container-header', timeout=10)

asyncio.run(google_search('pydoll python'))
```

### Advanced Features:
- **Element Search**: Multiple ways to find elements using attributes, CSS selectors, XPath, etc.
- **Browser-context HTTP Requests**: Inherit browser session state for API calls.
- **Download Management**: Handle file downloads with ease.
- **Custom Browser Preferences**: Control browser settings for advanced customization.
- **Concurrent Automation**: Automate multiple tabs simultaneously.

### Troubleshooting:
- **Browser Not Found**: Specify the binary location.
- **Browser Start Timeout**: Increase the start timeout.
- **Proxy Configuration**: Add proxy server arguments.
- **Docker Configuration**: Use `--no-sandbox` and `--disable-dev-shm-usage`.

### Documentation:
For complete documentation, visit the official documentation, which includes getting started guides, API references, and advanced techniques.

### Contributing:
Contributions are welcome. Follow the contribution guidelines, write tests, and use conventional commits.

### Support:
Support the project by starring the repository, sharing on social media, writing tutorials, or reporting issues. Consider sponsoring for exclusive benefits.

Pydoll is licensed under the MIT License.
## Links

- [Pydoll Documentation](https://pydoll.tech/) : Official documentation for Pydoll, providing detailed guides, API references, and advanced techniques for browser automation.
- [Pydoll Features](https://pydoll.tech/docs/features/#custom-browser-preferences/) : Detailed information on advanced features of Pydoll, including custom browser preferences and other functionalities.

## Topics

![](topics/Library/Pydoll)