# Microsoft.DBforPostgreSql

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## serverGroups

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.Mode

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.mode

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

## servers/configurations

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.isConfigPendingRestart

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.isDynamicConfig

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |

## servers/databases

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.charset

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |

## servers/firewallRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

## servers/securityAlertPolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.creationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.disabledAlerts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |

### \$.properties.storageAccountAccessKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |

## servers/virtualNetworkRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.ignoreMissingVnetServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (false)    | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

## servers

![16.22%25](https://img.shields.io/badge/16.22%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.administratorLoginPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.byokEnforcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Read-only             |
| 2017-12-01         | Unknown             | Read-only             |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.infrastructureEncryption

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Read-only             |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.minimalTlsVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties.previewFeature

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Read-only             |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties.sourceServerId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties.sslEnforcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Default ("Enabled") | Default ("Enabled")   |
| 2017-12-01         | Default ("Enabled") | Default ("Enabled")   |

### \$.properties.storageMB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.storageProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.storageProfile.backupRetentionDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (7)        | Unknown               |

### \$.properties.storageProfile.geoRedundantBackup

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2017-12-01-preview | Default* ("Disabled") | Unknown               |
| 2017-12-01         | Default* ("Disabled") | Unknown               |

### \$.properties.storageProfile.storageAutoGrow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.storageProfile.storageAutogrow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Default* (11)       | Unknown               |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |

### \$.sku.size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.sku.tier

| API version        | Detected noise type         | Determined noise type |
| ------------------ | --------------------------- | --------------------- |
| 2017-12-01-preview | Default* ("GeneralPurpose") | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

## serversv2/firewallRules

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.endIpAddress

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.startIpAddress

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

## serversv2

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.Role

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.VCores

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.administratorLoginPassword

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.displayName

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.fullyQualifiedDomainName

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.publicIpAddressRequested

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.role

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.standbyCount

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Default* (0)        | No Swagger            |

### \$.properties.userVisibleHAState

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.userVisibleState

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.vCores

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Default* (4)        | No Swagger            |

### \$.sku

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |
