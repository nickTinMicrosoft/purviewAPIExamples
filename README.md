# Overview of Purview API

# All Code Provided are samples and for testing and learning about using Purview's APIs. The Provided code is NOT MEANT for Production ready applications and do not follow best practices. Use at your own risk. 

### With Azure Purview's API, you can programmatically interact with and manage your data governance processes in Azure Purview. Here are key actions and use cases for the Azure Purview API:

1. Data Cataloging & Metadata Management:
    * Register & Manage Data Sources: You can use the API to register new data sources or update existing ones. For example, registering Azure Data Lake, SQL databases, or other cloud/on-premises data sources.
    * Search Data Assets: Programmatically search for data assets within the catalog based on metadata, classification, or other filters.
    * View & Update Metadata: You can retrieve, modify, or annotate metadata associated with data assets, such as descriptions, classifications, and tags.
2. Lineage Tracking:
    * Track Data Lineage: The API enables you to get the lineage information of a data asset, showing how data moves and transforms across different data systems.
    * Create Custom Lineage: If needed, you can add custom lineage links between different data assets.
3. Classification & Scanning:
    * Scan Data Sources: You can trigger data source scans to catalog assets, update metadata, and classify data based on built-in or custom classifiers.
    * Access Scan Results: View the results of scans to see what assets were discovered and which classifications were applied.
4. Business Glossary Management:
    * Create & Manage Terms: Use the API to manage a business glossary by adding, updating, or deleting terms.
    * Associate Terms with Data Assets: Link glossary terms to specific data assets to provide business context to your data.
5. Security & Access Control:
    * Assign Access Policies: Use the API to set role-based access control (RBAC) policies for data assets, restricting access to certain users or roles.
    * Audit Access: Retrieve logs and insights on who accessed specific data assets and when.
6. Data Insights & Reporting:
    * Generate Reports: Query the catalog to get insights about data usage, ownership, classifications, and lineage.
    * Monitor Compliance: Check for data assets that may be out of compliance with company or regulatory policies based on their classification and metadata.


### Example Use Cases:
* Automate Data Governance: Set up workflows that automatically scan new data sources, classify data, and update metadata.
* Metadata Synchronization: Sync metadata from different systems by using the Purview API to regularly update the catalog.
* Automated Lineage Discovery: Track transformations between datasets from ETL jobs or custom applications and push lineage updates to the API.

The API provides great flexibility in managing data governance tasks and ensuring your catalog is always up to date with the latest information.


## Link to Purview Documentation
https://learn.microsoft.com/en-us/rest/api/purview/?view=rest-purview-datamapdataplane-2023-09-01
