# What the Hack: OSS Database Migration Hackathon
A challenged based, hands-on hack to migrate MySQL, MariaDB and PostgreSQL databases from on-prem or other clouds to Azure equivalents

# Challenges

- [**Challenge 0**](./Student/Guides/challenge00.md) - Setup

  - Provisioning the IaaS Database Instance (MySQL, MariaDB, PostgreSQL)
  - Provisioning Resources for the Web Application and Connecting App to Database Instance
  - Database Status Validation
  - Application Status Validation

- [**Challenge 1**](./Student/Guides/challenge01.md) - Generating the Data (between 1TB to 32TB) into Blob Store/ADLS
- [**Challenge 2**](./Student/Guides/challenge02.md) - Loading Generated Data into IaaS OSS Database Instance
- [**Challenge 3**](./Student/Guides/challenge03.md) - Analyze Source DB Specs and Recommend Destination Sizing in Azure DB (Pick the Right Tier/SKU)
  
  This can be done using [Azure ODSR](https://github.com/izzymsft/AzureOSSDBSKURecommender)
  
- [**Challenge 4**](./Student/Guides/challenge04.md) - Perform Offline/Online Database Migration from IaaS to Azure DB Equivalent
- [**Challenge 5**](./Student/Guides/challenge05.md) - Perform Application Cutover (Blue/Green Deployment)
- [**Challenge 6**](./Student/Guides/challenge06.md) - Perform Validation 
- [**Challenge 7**](./Student/Guides/challenge07.md) - Perform Rollback to Source Database 
