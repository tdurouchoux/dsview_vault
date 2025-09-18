---
already_read: true
link: https://github.com/gitleaks/gitleaks
read_priority: 0
relevance: 5
source: Alpha Signal
tags:
- Data_Quality
- Development_tool
type: Content
upload_date: '2025-09-17'
---

https://github.com/gitleaks/gitleaks
## Summary

Gitleaks is a tool designed to detect secrets such as passwords, API keys, and tokens in git repositories, files, and other data sources. It uses regex-based detection and offers several features to customize and enhance its functionality.

### Key Features:
1. **Installation and Usage**:
   - Can be installed via Homebrew, Docker, or from source.
   - Supports scanning git repositories, directories, and stdin.
   - Can be integrated as a pre-commit hook or a GitHub action.

2. **Configuration**:
   - Supports custom configuration files to define detection rules.
   - Rules can be extended or overridden from the default configuration.
   - Allows for composite rules, which combine multiple rules with proximity constraints.

3. **Advanced Features**:
   - **Decoding**: Automatically decodes encoded text (percent, hex, base64) to find secrets.
   - **Archive Scanning**: Extracts and scans contents of archive files (zip, tarballs, etc.).
   - **Allowlists**: Ignores specific findings using `.gitleaksignore` or `gitleaks:allow` comments.
   - **Reporting**: Supports multiple report formats (json, csv, junit, sarif) and custom templates.

4. **Usage Examples**:
   - Scanning a git repository: `gitleaks git -v`
   - Scanning a directory: `gitleaks dir -v path_to_directory`
   - Streaming data to gitleaks: `cat some_file | gitleaks -v stdin`

5. **Exit Codes**:
   - 0: No leaks present.
   - 1: Leaks or error encountered.
   - 126: Unknown flag.

Gitleaks is a versatile tool for enhancing security by detecting and managing secrets in various data sources.
## Links

- [Regex is (almost) all you need](https://lookingatcomputer.substack.com/p/regex-is-almost-all-you-need) : A blog post explaining how regex can be used to detect secrets in code.
- [Gitleaks Blog](https://blog.gitleaks.io/stop-leaking-secrets-configuration-2-3-aeed293b1fbf) : A blog post on Gitleaks, detailing how to stop leaking secrets with configuration.
- [Gitleaks Docker Hub](https://hub.docker.com/r/zricethezav/gitleaks) : The Docker Hub page for Gitleaks, providing information on how to use Gitleaks with Docker.
- [Gitleaks Go Documentation](https://pkg.go.dev/github.com/zricethezav/gitleaks/v8) : The Go documentation for Gitleaks, providing detailed information on how to use Gitleaks with Go.
- [Gitleaks Playground](https://gitleaks.io/playground) : An interactive playground for testing Gitleaks configurations and detecting secrets.

## Topics

![[topics/Tool/Gitleaks]]