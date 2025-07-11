---
sidebar_position: 1
---

# Introduction to Resource Discovery

You can find resources using our user-friendly search interface or by accessing the data directly through our API.

## User Interface Search

The search page provides two ways to find what you need:

- **Faceted Search**: Use the filters in the sidebar to narrow your results based on specific metadata fields such as `task clusters`, `discipline`, or `preparations`.

- **Full-Text Search**: Use the main search bar at the top of the page to search for keywords across all resource content and metadata.

For a detailed explanation of the search syntax and capabilities, please refer to the [official CKAN search documentation](https://docs.ckan.org/en/latest/user-guide.html#searching-for-datasets).

## Programmatic Access (API)

For developers who wish to integrate our resources into their own applications or automated workflows, the knowledge base offers a comprehensive API. Powered by CKAN, the API allows you to build custom queries targeting specific metadata attributes and returns results in `JSON` format.

To get started, please review the [official CKAN API documentation](https://docs.ckan.org/en/latest/api/index.html). You will need to substitute the base URL in their examples with our endpoint:

```
https://digitizationknowledge/api/3/action/...
```
