# Microsoft.Storage

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## storageAccounts/blobServices/containers

![5.00%25](https://img.shields.io/badge/5.00%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-03-01-preview | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |

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
| 2019-06-01  | Unknown             | Unknown               |

### \$.properties.deleteRetentionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.denyEncryptionScopeOverride

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default (false)     | Default (false)       |

### \$.properties.publicAccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default* ("None")   | Unknown               |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

## storageAccounts/blobServices

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |

### \$.properties.automaticSnapshotPolicyEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |

### \$.properties.cors.corsRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

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
| 2018-07-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.deleteRetentionPolicy.days

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.deleteRetentionPolicy.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default* (false)    | Unknown               |

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

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

## storageAccounts/fileServices

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Unknown               |

## storageAccounts

![100.00%25](https://img.shields.io/badge/100.00%25-%E2%98%85★★★★★★★★★-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Put-as-patch          |
| 2017-06-01  | Unknown             | Put-as-patch          |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

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

### \$.properties.azureFilesAadIntegration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Default* (false)    | Put-as-patch          |
| 2018-07-01  | Default* (false)    | Put-as-patch          |
| 2018-11-01  | Default* (false)    | Put-as-patch          |

### \$.properties.azureFilesIdentityBasedAuthentication

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.customDomain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.dataLakeStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.ecryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |

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
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
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

### \$.properties.isHnsEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |

### \$.properties.largeFileSharesState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.migrationstate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Put-as-patch          |

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

### \$.properties.resources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Put-as-patch          |

### \$.properties.storageSupportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Put-as-patch          |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
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
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |

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

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2016-01-01  | Unknown             | Put-as-patch          |
| 2016-12-01  | Unknown             | Put-as-patch          |
| 2017-06-01  | Unknown             | Put-as-patch          |
| 2017-10-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-07-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-04-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |
