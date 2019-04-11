# Azure Storage

Variety of curated information and links about Azure Storage

## Azure Storage Accounts

| Performance | Description | Account Kind | Replication | Access Tier | Data Lake Storage Gen2 |
|--------------|-------------|-------------|-------------|-------------|------------------------|
|Standard|HDD, good for bulk storage and infrequent access|StorageV2 (general purpose v2)|Locally-redundant storage (LRS)                   |Cool, Hot|Available|
|        |                                                |                              |Zone-redundant storage (ZRS)                       |Cool, Hot|Available|
|        |                                                |                              |Geo-redundant storage (GRS)                       |Cool, Hot|Available|
|        |                                                |                              |Read-access geo-redundant storage (RA-GRS)|Cool, Hot|Available|
|        |                                                |Storage (general purpose v1)  |Locally-redundant storage (LRS)                   |N/A      |N/A      |
|        |                                                |                              |Geo-redundant storage (GRS)                       |N/A      |N/A      |
|        |                                                |                              |Read-access geo-redundant storage (RA-GRS)         |N/A      |N/A      |
|        |                                                |BlobStorage                   |Locally-redundant storage (LRS)                   |Cool, Hot|Available|
|        |                                                |                              |Geo-redundant storage (GRS)                       |Cool, Hot|Available|
|        |                                                |                              |Read-access geo-redundant storage (RA-GRS)         |Cool, Hot|Available|
|Premium |SSD, can only be used with Azure VM disks, best for I/O intensive apps like DBs|StorageV2 (general purpose v2)|Locally-redundant storage (LRS)|N/A|Disabled|
|        | |Storage (general purpose v1)|Locally-redundant storage (LRS)|N/A|Disabled|
|        | |BlockBlobStorage|Locally-redundant storage (LRS)|N/A|Disabled|
|        | |FileStorage|Locally-redundant storage (LRS)|N/A|Disabled|

## Pricing

- [Azure Storage Pricing](https://azure.microsoft.com/en-us/pricing/details/storage/)

## Documentation

- [[Azure Storage Documentation](https://docs.microsoft.com/en-us/azure/storage/)

## Updates

- [Azure Storage Updates](https://azure.microsoft.com/en-us/updates/?product=storage)

## How to create storage

1. Create a "storage account" under an "Azure subscription" and a "resource group".


            
    
