---
already_read: true
link: https://github.com/tadata-org/fastapi_mcp
read_priority: 0
relevance: 3
source: Alpha Signal
tags:
- Development_tool
type: Content
upload_date: '2025-09-17'
---

https://github.com/tadata-org/fastapi_mcp
## Summary

The repository fastapi_mcp by tadata-org allows users to expose FastAPI endpoints as Model Context Protocol (MCP) tools with built-in authentication. Key features include:

- **Authentication**: Uses existing FastAPI dependencies for secure endpoints.
- **FastAPI-native**: Designed as a native extension of FastAPI, not just a converter.
- **Zero/Minimal Configuration**: Works with minimal setup by pointing it at your FastAPI app.
- **Schema Preservation**: Maintains the schemas of request and response models.
- **Documentation Preservation**: Preserves endpoint documentation as seen in Swagger.
- **Flexible Deployment**: Can be mounted to the same app or deployed separately.
- **ASGI Transport**: Uses FastAPI's ASGI interface for efficient communication.

**Installation**:
- Recommended: `uv add fastapi-mcp`
- Alternative: `pip install fastapi-mcp`

**Basic Usage**:
```python
from fastapi import FastAPI
from fastapi_mcp import FastApiMCP

app = FastAPI()
mcp = FastApiMCP(app)
mcp.mount()
```
This makes the auto-generated MCP server available at `https://app.base.url/mcp`.

**Requirements**:
- Python 3.10+ (Recommended 3.12)
- uv

**Community and Contribution**:
- Join the MCParty Slack community for support and discussions.
- Contributions are welcome; see the Contribution Guide for details.

**License**: MIT License.
## Links

- [FastAPI-MCP Documentation](https://fastapi-mcp.tadata.com/) : Official documentation for FastAPI-MCP, providing detailed information on features, installation, and usage.
- [PyPI - fastapi-mcp](https://pypi.org/project/fastapi-mcp/) : PyPI page for fastapi-mcp, where you can find installation instructions and package details.

## Topics

![[topics/Concept/Model Context Protocol MCP)]]

![[topics/Library/fastapi mcp)]]