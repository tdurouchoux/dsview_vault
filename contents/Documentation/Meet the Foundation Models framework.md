---
already_read: false
link: https://developer.apple.com/videos/play/wwdc2025/286/
read_priority: 2
relevance: 0
source: Alpha Signal
tags:
- Large_Language_Model
type: Content
upload_date: '2025-06-15'
---

https://developer.apple.com/videos/play/wwdc2025/286/
## Summary

The Foundation Models framework provides developers with access to an on-device Large Language Model (LLM) that enhances app functionality on macOS, iOS, iPadOS, and visionOS. Key features and components include:

- **Model Overview**: It's optimized for tasks like content generation, text summarization, and user input analysis, running entirely on-device to maintain privacy.
  
- **Guided Generation**: Introduces macros (@Generable and @Guide) enabling structured output generation, helping create rich Swift objects without needing to specify output format explicitly.

- **Snapshot Streaming**: Instead of traditional token-based streaming, it streams snapshots of partially generated responses, making it easier to handle structured output with optional properties for integration with SwiftUI.

- **Tool Calling**: Allows the model to autonomously execute defined tools within the app, enhancing functionality to access data sources and perform actions based on context, such as querying for weather or restaurants.

- **Stateful Sessions**: Supports multi-turn interactions where previous context is retained. Developers can provide custom instructions to guide the model's behavior while using built-in use cases like content tagging.

- **Developer Experience**: Encourages using Playgrounds for rapid prototyping of prompts, profiling tools to improve performance, and emphasizes the importance of user feedback for model improvement.

The framework promotes a secure and efficient model interaction for various advanced app features while ensuring ease of use for developers through streamlined development tools.
## Links

- [Human Interface Guidelines: Generative AI](https://developer.apple.com/design/human-interface-guidelines/generative-ai) : Apple's design guidelines for implementing generative AI in applications.
- [Feedback Assistant](https://feedbackassistant.apple.com/) : A platform for Apple developers to provide feedback and report issues.
- [Open Source at Apple](https://opensource.apple.com) : Access Apple's open source projects and initiatives, potentially related to frameworks and tools for developers.

## Topics

![](topics/Concept/Guided%20Generation)

![](topics/Tool/Foundation%20Models%20framework)

![](topics/Concept/Tool%20Calling)

![](topics/Concept/Stateful%20Sessions)

![](topics/Concept/Snapshot%20Streaming)