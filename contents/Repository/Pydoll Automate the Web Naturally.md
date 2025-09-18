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

Pydoll is a Python library designed for automating Chromium-based browsers without the need for a WebDriver, offering realistic interactions. It connects directly to the Chrome DevTools Protocol (CDP), eliminating the need for external drivers and simplifying the automation process. Key features include:

- **Zero Webdrivers**: Eliminates compatibility issues associated with WebDriver.
- **Human-like Interaction Engine**: Capable of passing behavioral CAPTCHAs like reCAPTCHA v3 or Turnstile, depending on IP reputation and interaction patterns.
- **Asynchronous Performance**: Supports high-speed automation and multiple simultaneous tasks.
- **Humanized Interactions**: Mimics real user behavior for more realistic automation.
- **Simplicity**: Easy to install and use, with minimal configuration required.

### Key Features and Updates:
- **Remote Connections via WebSocket**: Allows control of any Chrome browser remotely via WebSocket.
- **DOM Navigation**: Methods like `get_children_elements()` and `get_siblings_elements()` for efficient DOM traversal.
- **WebElement State Waiting**: New methods like `wait_until()` to wait for element states (visible, interactable, etc.).
- **Browser-context HTTP Requests**: Makes HTTP requests that inherit the browser's session state, useful for hybrid automation.
- **Download Management**: `expect_download()` context manager for robust file downloads.
- **Custom Browser Preferences**: Advanced control over Chrome settings for customization and security.
- **Concurrent Automation**: Supports multiple tasks simultaneously thanks to its asynchronous implementation.

### Installation and Usage:
- **Installation**: `pip install pydoll-python`
- **Basic Example**: Automating a Google search and clicking on the first result.
- **Data Extraction**: Extracting information like project description, number of stars, forks, issues, and pull requests from a webpage.
- **Custom Configurations**: Configuring browser options like proxy settings, window size, and custom binary paths.

### Advanced Features:
- **Element Search**: Various methods to find elements using attributes, CSS selectors, XPath, etc.
- **Event System**: For reactive automations.
- **Request Interception and Modification**: Advanced control over network requests.

### Troubleshooting:
- **Browser Not Found**: Specify the binary location.
- **Browser Start Issues**: Adjust the start timeout.
- **Proxy Settings**: Configure proxy server settings.
- **Docker Compatibility**: Use `--no-sandbox` and `--disable-dev-shm-usage` flags.

### Documentation and Support:
- **Documentation**: Comprehensive guides, API references, and advanced techniques.
- **Contributing**: Guidelines for contributing to the project.
- **Support**: Options to support the project, including sponsorship, starring the repository, and sharing on social media.

Pydoll is licensed under the MIT License and aims to make browser automation more efficient and realistic.
## Links

- [Pydoll Documentation](https://pydoll.tech/) : Official documentation for Pydoll, providing detailed guides, API references, and advanced techniques for browser automation.
- [GitHub Blog](https://github.blog) : GitHub's official blog featuring updates, announcements, and articles about GitHub features and services.

## Topics

![[topics/Library/Pydoll]]