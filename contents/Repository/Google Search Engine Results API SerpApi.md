---
already_read: false
link: https://serpapi.com/search-api
read_priority: 1
relevance: 0
source: null
tags:
- Development_tool
type: Content
upload_date: '2024-02-15'
---

https://serpapi.com/search-api
## Summary

The Google Search Engine Results API by SerpApi allows users to scrape Google search results programmatically. Here are the key technical points and takeaways:

### Key Features:
1. **API Endpoint**: The `/search` API endpoint enables scraping Google search results.
2. **Parameters**:
   - **Search Query (`q`)**: Defines the search query (e.g., "coffee").
   - **Geographic Location (`location`, `uule`)**: Specifies the location for the search.
   - **Advanced Google Parameters**: Includes parameters like `ludocid`, `lsig`, `kgmid`, `si`, `ibp`, and `uds` for advanced search functionalities.
   - **Localization**: Parameters like `google_domain`, `gl`, `hl`, `cr`, and `lr` for language and country settings.
   - **Advanced Filters**: Parameters like `tbs`, `safe`, `nfpr`, and `filter` for filtering search results.
   - **Search Type (`tbm`)**: Specifies the type of search (e.g., images, local, videos).
   - **Pagination (`start`, `num`)**: Controls the pagination of search results.
   - **SerpApi Parameters**: Includes `engine`, `device`, `no_cache`, `async`, `zero_trace`, `api_key`, `output`, and `json_restrictor` for customizing the API response.

### API Results:
1. **JSON Results**: Structured data for various types of search results (organic, local, ad results, knowledge graph, etc.).
2. **HTML Results**: Raw HTML results from Google.

### Examples:
1. **Basic Example**: A simple search for "coffee" with default parameters.
2. **Complex Example**: A more complex search for "Fresh Bagels" in Seattle with multiple optional parameters.

### Pagination:
- The API supports pagination with `start` and `num` parameters to navigate through multiple pages of results.

### Additional Information:
- **API Status**: The API has a 100% uptime.
- **Documentation**: Comprehensive documentation is available for all API endpoints and parameters.
- **Support**: Includes GitHub, legal, security, libraries, release notes, public roadmap, and support resources.

This API is designed to provide a robust and flexible way to access Google search results programmatically, making it easier to integrate search functionalities into applications.
## Links

- [Google Business](https://www.google.com/business/) : Google Business provides tools and resources for managing your business presence on Google, including search and maps.
- [SerpApi Plan](https://serpapi.com/plan) : SerpApi Plan page provides information on different subscription plans and pricing for using the SerpApi service.

## Topics

![](topics/Library/SerpApi)