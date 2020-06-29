# Microsoft.Storage

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## storageAccounts/blobServices/containers

![cleanliness](https://img.shields.io/badge/cleanliness-35.14%25%20(13%20/%2037)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2024)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-11-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.accessTier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.defaultEncryptionScope

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.deleteRetentionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.deleted

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default (false)     | No Swagger            |

### \$.properties.denyEncryptionScopeOverride

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default (false)     | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.publicAccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.remainingRetentionDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default (0)         | No Swagger            |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

## storageAccounts/blobServices

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2026)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.MaxDequeueCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.automaticSnapshotPolicyEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.cors.corsRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.cors.corsRules[*].allowedHeaders

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.cors.corsRules[*].allowedHeaders[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.cors.corsRules[*].exposedHeaders

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.deleteRetentionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.deleteRetentionPolicy.days

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.deleteRetentionPolicy.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default* (false)    | No Swagger            |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

## storageAccounts/fileServices/shares

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(9%20/%2015)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

## storageAccounts/fileServices

![cleanliness](https://img.shields.io/badge/cleanliness-61.54%25%20(8%20/%2013)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.DeleteRetentionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.shareDeleteRetentionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.shareDeleteRetentionPolicy.days

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (0)        | No Swagger            |

## storageaccounts/managementpolicies

![cleanliness](https://img.shields.io/badge/cleanliness-96.15%25%20(25%20/%2026)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.policy.rules[*].enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (true)     | No Swagger            |

## storageAccounts

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(142%20/%20142)-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch          |
| 2016-01-01         | Unknown             | Put-as-patch          |
| 2017-06-01         | Unknown             | Put-as-patch          |
| 2017-10-01         | Unknown             | Put-as-patch          |
| 2018-02-01         | Unknown             | Put-as-patch          |
| 2018-07-01         | Unknown             | Put-as-patch          |
| 2019-04-01         | Unknown             | Put-as-patch          |
| 2019-06-01         | Unknown             | Put-as-patch          |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Put-as-patch          |

### \$.properties.accessTier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-01-01         | Unknown             | Put-as-patch          |
| 2017-10-01         | Unknown             | Put-as-patch          |
| 2018-02-01         | Unknown             | Put-as-patch          |
| 2018-03-01-preview | Unknown             | Put-as-patch          |
| 2018-07-01         | Unknown             | Put-as-patch          |
| 2018-11-01         | Unknown             | Put-as-patch          |
| 2019-04-01         | Unknown             | Put-as-patch          |
| 2019-06-01         | Unknown             | Put-as-patch          |

### \$.properties.accountType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.azureFilesAadIntegration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.azureFilesIdentityBasedAuthentication

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.commentAboutEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.customDomain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.customDomain.useSubDomainName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.dataLakeStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.defaultAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.ecryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.enableHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Put-as-patch          |
| 2016-12-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption.encryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption.keySource

| API version | Detected noise type             | Determined noise type |
| ----------- | ------------------------------- | --------------------- |
| 2017-10-01  | Default* ("Microsoft.Keyvault") | Put-as-patch          |
| 2018-07-01  | Default* ("Microsoft.Keyvault") | Put-as-patch          |
| 2019-04-01  | Default* ("Microsoft.Keyvault") | Put-as-patch          |

### \$.properties.encryption.keyvaultproperties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption.networkAcls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption.services

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-06-01         | Unknown             | Put-as-patch          |
| 2017-10-01         | Unknown             | Put-as-patch          |
| 2018-02-01         | Unknown             | Put-as-patch          |
| 2018-03-01-preview | Unknown             | Put-as-patch          |
| 2018-07-01         | Unknown             | Put-as-patch          |
| 2018-11-01         | Unknown             | Put-as-patch          |
| 2019-04-01         | Unknown             | Put-as-patch          |
| 2019-06-01         | Unknown             | Put-as-patch          |

### \$.properties.encryption.services.blob.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Default (true)      | Put-as-patch          |
| 2016-12-01  | Default (true)      | Put-as-patch          |
| 2018-07-01  | Default (true)      | Put-as-patch          |

### \$.properties.encryption.services.blob.keyType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default ("Account") | Put-as-patch          |

### \$.properties.encryption.services.file

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | Put-as-patch          |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption.services.file.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default (true)      | Put-as-patch          |

### \$.properties.encryption.services.file.keyType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default ("Account") | Put-as-patch          |

### \$.properties.encryption.services.queue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption.services.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Put-as-patch          |

### \$.properties.encryption.services.table

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Put-as-patch          |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.isHnsEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.isVirtualNetworkFilterEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Put-as-patch          |

### \$.properties.largeFileSharesState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.migrationstate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Put-as-patch          |
| 2016-12-01  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls.comments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls.defaultAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls.ipRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01         | Unknown             | Put-as-patch          |
| 2018-02-01         | Unknown             | Put-as-patch          |
| 2018-03-01-preview | Unknown             | Put-as-patch          |
| 2018-07-01         | Unknown             | Put-as-patch          |
| 2019-04-01         | Unknown             | Put-as-patch          |
| 2019-06-01         | Unknown             | Put-as-patch          |

### \$.properties.networkAcls.ipRules[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls.ipRules[*].description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls.iprules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls.virtualNetworkRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.publicAccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Put-as-patch          |

### \$.properties.resources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.storageSupportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.supportHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Put-as-patch          |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2016-01-01  | Unknown             | Put-as-patch          |
| 2016-05-01  | Unknown             | Put-as-patch          |
| 2016-12-01  | Unknown             | Put-as-patch          |
| 2017-06-01  | Unknown             | Put-as-patch          |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch          |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-01-01         | Unknown             | Put-as-patch          |
| 2016-12-01         | Unknown             | Put-as-patch          |
| 2017-06-01         | Unknown             | Put-as-patch          |
| 2017-10-01         | Unknown             | Put-as-patch          |
| 2018-02-01         | Unknown             | Put-as-patch          |
| 2018-03-01-preview | Unknown             | Put-as-patch          |
| 2018-07-01         | Unknown             | Put-as-patch          |
| 2018-11-01         | Unknown             | Put-as-patch          |
| 2019-04-01         | Unknown             | Put-as-patch          |
| 2019-06-01         | Unknown             | Put-as-patch          |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch          |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-01-01         | Unknown             | Put-as-patch          |
| 2016-12-01         | Unknown             | Put-as-patch          |
| 2017-06-01         | Unknown             | Put-as-patch          |
| 2017-10-01         | Unknown             | Put-as-patch          |
| 2018-02-01         | Unknown             | Put-as-patch          |
| 2018-07-01         | Unknown             | Put-as-patch          |
| 2018-11-01         | Unknown             | Put-as-patch          |
| 2019-04-01         | Unknown             | Put-as-patch          |
| 2019-06-01         | Unknown             | Put-as-patch          |
