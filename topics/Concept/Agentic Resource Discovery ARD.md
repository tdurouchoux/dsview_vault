---
type: Concept
---

Agentic Resource Discovery (ARD) is an open specification designed to enable AI agents to dynamically discover and utilize tools, skills, and other agents across federated registries. Unlike traditional static catalogs where capabilities must be pre-installed or manually configured, ARD allows agents to search for and integrate capabilities at runtime based on intent-based queries. The specification defines a static manifest format (ai-catalog.json) for publishers to host their capabilities and a dynamic registry API (POST /search) for live discovery. ARD aims to scale agentic systems by reducing the need for manual integration and enabling access to a growing ecosystem of tools and services.